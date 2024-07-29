FROM registry.access.redhat.com/openjdk/openjdk-11-rhel7

ENV JAVA_APP_DIR=/deployments
COPY target/*.jar $JAVA_APP_DIR/app.jar

EXPOSE 8080
CMD ["java", "-jar", "/deployments/app.jar"]
