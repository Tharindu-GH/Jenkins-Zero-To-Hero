# Use Java 17 runtime
FROM eclipse-temurin:17-jre-alpine

# Artifact path
ARG artifact=target/spring-boot-web.jar

WORKDIR /opt/app

# Copy the built jar
COPY ${artifact} app.jar

# Start the app
ENTRYPOINT ["java","-jar","app.jar"]
