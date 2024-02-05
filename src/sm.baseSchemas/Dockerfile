
FROM tibco/bwce:latest

WORKDIR /app

COPY /home/runner/work/sm.baseSchema/sm.baseSchema/src/sm.baseSchemas/target/sm.baseSchemas-1.2-SNAPSHOT.jar/app/

EXPOSE 8080

CMD ["java", "-jar", "sm.baseSchemas_1.0.0.202303271123.jar"]
