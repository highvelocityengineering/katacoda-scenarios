Before jumping into docker, let us first build and test application locally.

To build the SpringBoot application and package the application as binary `jar` and `war` archive files run the following command:

`cd docker-springboot-hello-world && gradle clean build`{{execute}}

Wait, how would `gradle` know how to build and package my application? The answer to that is in `build.gradle` file: `docker-springboot-hello-world/build.gradle`{{open}}

To view the package files created: `ls -l build/libs`{{execute}}

Start the application: `java -jar build/libs/docker101_springboot-boot.jar`{{execute}}

To test if the application works locally, open a new terminal window and run `curl localhost:8080`{{execute T2}}

To open this in browser: https://[[HOST_SUBDOMAIN]]-8080-[[KATACODA_HOST]].environments.katacoda.com/
