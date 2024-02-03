# Use the base image of BW6
FROM tibco/bwce:latest

# Set the working directory inside the container
WORKDIR /app

# Copy the JAR file from the host into the container
COPY /home/runner/work/sm.baseSchema/sm.baseSchema/src/sm.baseSchemas/target/sm.baseSchemas_1.0.0.202303271123.jar /app/

# Expose any necessary ports (if applicable)
# EXPOSE 8080

# Define the command to run your application when the container starts
# For example, if your JAR file is executable, you can use the java -jar command
CMD ["java", "-jar", "sm.baseSchemas_1.0.0.202303271123.jar"]
