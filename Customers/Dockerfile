FROM openjdk:17-alpine
EXPOSE 8082
ADD ./target/Customers-0.0.1-SNAPSHOT.jar customers.jar
ENTRYPOINT ["java","-jar","customers.jar"]