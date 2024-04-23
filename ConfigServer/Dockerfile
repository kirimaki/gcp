FROM openjdk:17-alpine
EXPOSE 8888
ADD ./target/ConfigServer-0.0.1-SNAPSHOT.jar configserver.jar
ENTRYPOINT ["java","-jar","configserver.jar"]