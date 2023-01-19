FROM openjdk:8-jdk-alpine
ADD customer-service/target/customer-service.jar customer-service.jar
EXPOSE 3333
ENTRYPOINT ["java", "-jar", "/customer-service.jar"]
