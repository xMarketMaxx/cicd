How to build application:
1. Gradle:
1.1) Open console in the current directory
1.2) Enter the command:gradle jar war
		.jar location: admin/build/libs/admin.jar
		.war location: web/build/libs/web.war
1.3) To launch tests as a part of build process, you need to enter following command:gradle test jar war

2. Maven:
2.1) Open console in the current directory
2.2) Enter the command:mvn package
		.jar location: admin/target/admin.jar
		.war location: web/target/web.war
2.3) Tests run as a part of build process

3. Ant:
3.1) Open console in the current directory
3.2) Enter the command:ant all
		.jar location: admin/buildAnt/jar/admin.jar
		.war location: web/buildAnt/war/web.war
3.3) Tests run as a part of build process