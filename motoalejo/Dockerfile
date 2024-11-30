FROM openjdk:21-jdk-slim

WORKDIR /app

COPY target/motoalejo-0.0.1.jar /app/motoalejo.jar
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "/app/motoalejo.jar"]