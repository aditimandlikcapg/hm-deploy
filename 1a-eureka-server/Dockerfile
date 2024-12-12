FROM openjdk:17-jdk-alpine

MAINTAINER "Ashu"
EXPOSE 8761

# Copy the JAR file from the host to the container, assuming the JAR is located in ./target/
COPY ./target/eureka-app.jar eureka-app.jar

# Set the command to run the JAR file when the container starts
CMD ["java", "-jar", "eureka-app.jar"]
