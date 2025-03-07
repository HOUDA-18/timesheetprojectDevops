FROM openjdk:8-jdk-alpine
EXPOSE 8082

# Télécharger le JAR depuis Nexus
ADD http://192.168.65.129:8081/repository/maven-releases/tn/esprit/spring/services/timesheet-devops/1.0/timesheet-devops-1.0.jar timesheet-devops-1.0.jar

# Lancer l'application
ENTRYPOINT ["java", "-jar", "/timesheet-devops-1.0.jar"]
