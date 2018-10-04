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
	
7. Projects and Tasks in Gradle :  	