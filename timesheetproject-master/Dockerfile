FROM openjdk:8-jdk-alpine
EXPOSE 8082

# Télécharger avec authentification
RUN wget --user=admin --password=hadouchti30072020 \
    -O timesheet-devops-1.0.jar \
    http://192.168.65.129:8081/repository/maven-releases/tn/esprit/spring/services/timesheet-devops/1.0/timesheet-devops-1.0.jar

ENTRYPOINT ["java", "-jar", "/timesheet-devops-1.0.jar"]
