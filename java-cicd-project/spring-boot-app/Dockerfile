FROM adoptopenjdk/openjdk11:alpine-jre

WORKDIR /opt/app

# Define the artifact name as a build argument
ARG springBootJar=spring-boot-web.jar

# Copy the artifact into the container
COPY target/${springBootJar} app.jar

EXPOSE 8080

ENTRYPOINT ["java", "-jar", "app.jar"]
