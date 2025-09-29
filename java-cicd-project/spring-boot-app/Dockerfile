FROM adoptopenjdk/openjdk11:alpine-jre

WORKDIR /opt/app

# Copy the JAR built by Maven
COPY target/spring-boot-web.jar app.jar

ENTRYPOINT ["java", "-jar", "app.jar"]
