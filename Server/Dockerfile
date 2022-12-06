FROM openjdk:11

RUN mkdir /app

COPY src/Server.java /app
COPY src/ServerProtocol.java /app
COPY mysql-connector.jar /app

WORKDIR /app

CMD java Server