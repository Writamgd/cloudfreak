FROM openjdk:17-jdk-slim

# Set a working directory
WORKDIR /app

# Copy the built jar (already copied via Jenkins stage)
COPY *.jar app.jar

# Run the application
ENTRYPOINT ["java", "-jar", "app.jar"]
