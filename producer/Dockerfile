FROM openjdk:8-jre-slim

WORKDIR /kafka-server

ADD kafka/ /kafka-server/

ENTRYPOINT ["./bin/kafka-console-producer.sh","--bootstrap-server","server:9092","--topic"]
# CMD ./bin/kafka-console-producer.sh --bootstrap-server server:9092 --topic test
CMD [ "test" ]