FROM openjdk:11-jre-alpine
COPY maven /opt/app/
WORKDIR /opt/app
ENTRYPOINT java -jar ./app.jar
EXPOSE 8080