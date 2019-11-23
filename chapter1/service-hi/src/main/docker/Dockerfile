FROM openjdk:8-jdk-alpine
VOLUME /tmp
ADD service-hi.jar app.jar
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]