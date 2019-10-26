Before jumping into Docker, let us first build and package the application locally and test if the application works.

Run this command to build the SpringBoot application and package the application binaries as `jar` and `war` archive files.

`gradle clean build`{{execute}}

Wait, how would `gradle` know how to build and package my application? The answer to that is in `build.gradle` file: `docker-springboot-hello-world/build.gradle`{{open}}

To view the package files created: `ls -l docker-springboot-hello-world/build/libs`{{execute}}