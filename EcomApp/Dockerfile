FROM openjdk:17
EXPOSE 8383
ADD target/dockersjenkinsintegration dockersjenkinsintegration.jar
ENTRYPOINT ["java","-jar","/dockersjenkinsintegration.jar"]
