FROM openjdk:8-jdk-alpine
MAINTAINER BHARGAV
VOLUME /tmp
ADD target/api-gateway-*.jar app.jar
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]