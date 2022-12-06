FROM openjdk:11

RUN mkdir /app

COPY src/Client.java /app
COPY src/ClientProtocol.java /app

WORKDIR /app

CMD java Client