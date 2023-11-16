FROM eclipse-temurin:17-jdk-alpine
ARG JAR_FILE=./fullstack-backend\target/*.jar
EXPOSE 8081
COPY ${JAR_FILE} app.jar
ENTRYPOINT ["java","-jar","/app.jar"]
