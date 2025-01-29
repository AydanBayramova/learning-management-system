FROM openjdk:21
VOLUME /tmp
EXPOSE 8084
ADD build/libs/ ms-login-0.0.1-SNAPSHOT.jar
ENTRYPOINT ["java", "-jar", "/ms-login.jar"]
