# Employing an openjdk base image
FROM openjdk:11-jre-slim

# Specifying the working directory
WORKDIR /app

# Replicating the JAR file into the container
COPY target/conversion-0.0.1-SNAPSHOT.jar app.jar

# Exposing the port on which the app will run
EXPOSE 8080

# Command to execute the application
ENTRYPOINT ["java", "-jar", "app.jar"]
