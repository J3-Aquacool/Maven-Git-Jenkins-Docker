FROM openjdk:17
EXPOSE 8383
COPY target/dockersjenkinsintegration  dockersjenkinsintegration.jar
ENTRYPOINT ["java","-jar","/dockersjenkinsintegration.jar"]
