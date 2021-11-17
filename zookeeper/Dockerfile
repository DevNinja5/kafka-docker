FROM openjdk:8-jre-slim

WORKDIR /kafka-server

ADD kafka/ /kafka-server/

EXPOSE 2181

CMD ./bin/zookeeper-server-start.sh config/zookeeper.properties

# CMD [ "./bin/kafka-server-start.sh","config/server.properties" ]