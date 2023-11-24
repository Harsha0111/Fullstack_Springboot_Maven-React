
FROM eclipse-temurin:17-jdk-alpine
VOLUME /tmp
ARG JAR_FILE
COPY ${JAR_FILE} app.jar
ENTRYPOINT ["java","-jar","/app.jar"]


# FROM openjdk:17

# WORKDIR /var/www/app

# COPY mvnw .
# COPY .mvn .mvn
# COPY pom.xml .
# COPY .  .

# RUN ./mvnw package -Dmaven.test.skip

# EXPOSE 8081

# COPY var/www/app/target/*.jar app.jar

# CMD ["java", "-jar", "app.jar"]
# # Fetching latest version of Java
# FROM openjdk:17
 
# # Setting up work directory
# WORKDIR /app

# # Copy the jar file into our app
# COPY app/target/*.jar app.jar

# # Exposing port 8081
# EXPOSE 8081

# # Starting the application
# CMD ["java", "-jar", "app.jar"]
# # fullstack-backend-maven\fullstack-backend\target\fullstack-backend-0.0.1-SNAPSHOT.jar