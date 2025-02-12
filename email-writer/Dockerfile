# Use OpenJDK as base image
FROM openjdk:17-jdk-slim

# Set working directory
WORKDIR /app

# Copy project files
COPY target/*.jar app.jar

# Expose the port
EXPOSE 7002

# Run the application
CMD ["java", "-jar", "app.jar"]
