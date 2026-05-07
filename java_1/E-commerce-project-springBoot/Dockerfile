FROM eclipse-temurin:17-jre-alpine
WORKDIR /app
# This matches your project path: /home/jenkins/agent/workspace/java/java_1/E-commerce-project-springBoot/target/
COPY target/JtSpringProject-*.jar app.jar
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "app.jar"]
