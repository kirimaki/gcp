FROM openjdk:17-alpine
EXPOSE 8081
ADD ./target/Catalogs-0.0.1-SNAPSHOT.jar catalog.jar
ENTRYPOINT ["java","-jar","catalog.jar"]