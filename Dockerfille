# Dockerfile (Spring Boot + JDK 17 runtime)
FROM eclipse-temurin:17-jre-alpine

WORKDIR /app

# expects the jar to be created by: mvn clean package (target/*.jar)
COPY target/*.jar app.jar

EXPOSE 8080

ENTRYPOINT ["java","-jar","app.jar"]
