FROM java:openjdk-8
LABEL authors="ozr"
ADD hello-word-0.0.1-SNAPSHOT.jar /app/app.jar
WORKDIR /
ENTRYPOINT exec java -jar /app/app.jar
