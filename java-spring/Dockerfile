FROM openjdk:11-jre-slim
EXPOSE 8080
ADD target/demo-0.0.1-SNAPSHOT.jar app.jar
ENTRYPOINT ["java", "-jar", "app.jar"]
