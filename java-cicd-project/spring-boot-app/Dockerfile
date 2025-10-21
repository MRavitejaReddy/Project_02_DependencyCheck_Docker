FROM adoptopenjdk/openjdk11:alpine-jre

WORKDIR /opt/app

# Accept the JAR file as a build argument
ARG JAR_FILE
COPY ${JAR_FILE} app.jar

EXPOSE 8080
ENTRYPOINT ["java", "-jar", "app.jar"]
