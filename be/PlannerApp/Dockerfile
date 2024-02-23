FROM adoptopenjdk/openjdk21:alpine-jre

# Set the working directory in the container
WORKDIR /app

# Copy the packaged JAR file into the container at /app
COPY build/libs/PlannerApp-1.jar /app/PlannerApp.jar

# Expose the port that the Spring Boot application will run on
EXPOSE 8080

# Run the JAR file
CMD ["java", "-jar", "PlannerApp.jar"]