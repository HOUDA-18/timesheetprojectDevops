FROM openjdk:8-jdk-alpine
EXPOSE 8082

# Copier le fichier JAR dans l'image
COPY target/timesheet-devops-1.0.jar /timesheet-devops-1.0.jar

ENTRYPOINT ["java", "-jar", "/timesheet-devops-1.0.jar"]
