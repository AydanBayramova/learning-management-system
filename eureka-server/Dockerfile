FROM openjdk:21
VOLUME /tmp
EXPOSE 8761
COPY build/libs/eureka-server-0.0.1-SNAPSHOT.jar eureka-server.jar
ENTRYPOINT ["java", "-jar", "/eureka-server.jar"]
