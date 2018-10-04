1. What is gradle : Build and dependency management tool (is is open source)

2. https://gradle.org/install/ : Install Manuall : Download binary only version

3. Unzip 

4. Set environment variable for Gradle
	GRADLE_HOME
	PATH
	JAVA_HOME will be there already (assumption)
	
5. Confirm in cmd : gradle -version : you can see your gradle version : mine is 4.10.2

6. Why do we use gradle : 
	Highly customizable : you can use gradle for java/android/python/JavaScript/etc projects.. : Just apply plugin for that particular language : This configuration is made in build.gradle file
	Gradle is Fast : Gradle completes tasks quickly by reusing outputs from previous executions, processing only inputs that changed, and executing tasks in parallel.
	
7. Projects and Tasks in Gradle : Everything in gradle sits on top of two basic concepts, projects and tasks
	Every gradle build is made up of on or more projects
	
8. Gradle Projects : A project might represent a library JAR or a web application
		It might represent a distribution ZIP assembled from the JARS produced by another projects.
		A project could be deploying your application to staging or production environment.
		Each project is made up of one or more tasks, A task represents some atomic piect of work which a build performs
		
9. Gardle Task : task could be compiling some classes
		creating a JAR
		Generating JavaDoc
		publishing some archives to some repository
		
10. dot gradle folder : c/users/Anand/.gradle : local repository for gardle

11. Gardle plugin for eclipse : 
		use latest version of ecclipse, gradle plugin will be pre installed , or else go to marketplace and download
		
12. Create gradle project in eclipse : new-> gradle -> gradle project 		