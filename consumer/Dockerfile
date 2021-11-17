FROM openjdk:8-jre-slim

WORKDIR /kafka-server

ADD kafka/ /kafka-server/


ENTRYPOINT [ "./bin/kafka-console-consumer.sh","--bootstrap-server","server:9092","--from-beginning","--topic" ]

# CMD ./bin/kafka-console-consumer.sh --bootstrap-server server:9092 --topic test --from-beginning
CMD [ "test" ]