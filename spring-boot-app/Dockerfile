# Use a base image with JRE 21 to run the application
FROM eclipse-temurin:21-jre

# Set the working directory inside the container
WORKDIR /app

# Copy the JAR file from your local machine (assumes it is in the target folder)
COPY target/*.jar app.jar

# Run the Java application
ENTRYPOINT ["java", "-jar", "app.jar"]
