# Use a base image with Java and other dependencies suitable for BWCE
FROM tibco/bwce:2.6.0

# Set the working directory
WORKDIR /app

# Copy the BWCE application JAR file into the image
COPY /home/runner/work/sm.baseSchema/sm.baseSchema/src/sm.baseSchemas/target/sm.baseSchemas_1.0.0.202303271123.jar /app/app.bwapp

# Expose the port if your BWCE application needs it
# EXPOSE 8080

# Command to run the BWCE application
CMD ["tibco/tibco-bwce/2.6.0/bwce-container/docker/execs/app.bwapp"]
