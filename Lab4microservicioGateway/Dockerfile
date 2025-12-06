FROM eclipse-temurin:21-jdk-alpine
WORKDIR /app
ADD target/ati2microservicio-0.0.1-SNAPSHOT.jar app.jar
EXPOSE 7000
ENTRYPOINT ["java","-jar","/app/app.jar"]
