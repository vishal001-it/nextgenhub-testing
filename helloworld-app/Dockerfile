# Use an official OpenJDK runtime as a parent image
FROM openjdk:17-jdk-alpine

# Set the working directory in the container
WORKDIR /app

# Copy the JAR file from the target folder to the container
COPY target/hello-0.0.1-SNAPSHOT.jar  hello-0.0.1-SNAPSHOT.jar

# Command to run the JAR file
ENTRYPOINT ["java", "-jar", " hello-0.0.1-SNAPSHOT.jar"]
