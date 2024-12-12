FROM openjdk:17-jdk-alpine

MAINTAINER "Ashu"
EXPOSE 9093

# Copy the JAR file from the host to the container, assuming the JAR is located in ./target/
COPY ./target/patient-service.jar patient-service.jar

# Set the command to run the JAR file when the container starts
CMD ["java", "-jar", "patient-service.jar"]
