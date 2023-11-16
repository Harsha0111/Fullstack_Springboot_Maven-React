# AS <NAME> to name this stage as maven
FROM maven:3.6.3 AS maven

WORKDIR /app
COPY . .
# Compile and package the application to an executable JAR
CMD mvn package





# Exposing port 8080
EXPOSE 8081

