FROM openjdk:21
VOLUME /tmp
EXPOSE 8081
ADD build/libs/ms-register-0.0.1-SNAPSHOT.jar ms-register.jar
ENTRYPOINT ["java", "-jar", "/ms-register.jar"]
