FROM eclipse-temurin:21-jdk-alpine
WORKDIR /app
ADD target/ati2microservicio-GreetingMicroservice-0.0.1-SNAPSHOT.jar app.jar
EXPOSE 8001
ENTRYPOINT ["java","-jar","/app/app.jar"]