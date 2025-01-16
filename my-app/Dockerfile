FROM openjdk:8
ADD target/my-app-1.0-SNAPSHOT.jar my-app.jar
RUN echo "This is a Docker Build Jenkins Step" > out.txt
ENTRYPOINT ["java", "-jar","my-app.jar"]
EXPOSE 8080

