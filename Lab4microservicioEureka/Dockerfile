FROM eclipse-temurin:21-jdk-alpine
WORKDIR /app
ADD target/ati2microservicio-Spring-Cloud-GatewayService-0.0.1-SNAPSHOT.jar app.jar
EXPOSE 8761
# Configuración de entrada
ENTRYPOINT ["java","-jar","/app/app.jar"]