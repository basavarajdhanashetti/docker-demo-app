
#use openjdk
FROM openjdk:8-jdk

# Set the working directory to /app
WORKDIR /app

# Copy the current directory contents into the container at /app
COPY ./target/demo-app-0.0.1-SNAPSHOT.jar /app


# Make port 8080 available to the world outside this container
EXPOSE 8080

RUN sh -c 'touch /demo-app-0.0.1-SNAPSHOT.jar'

ENTRYPOINT ["java","-jar","demo-app-0.0.1-SNAPSHOT.jar"]



