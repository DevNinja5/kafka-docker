FROM openjdk:8-jre-slim

WORKDIR /kafka-server

ADD kafka/ /kafka-server/

EXPOSE 9092

CMD [ "./bin/kafka-server-start.sh","config/server.properties" ]