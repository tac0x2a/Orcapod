FROM adoptopenjdk/openjdk8-openj9
LABEL maintainer="tac@tac42.net"

ENV EMBULK_VERSION 0.9.23
RUN curl -L https://bintray.com/artifact/download/embulk/maven/embulk-${EMBULK_VERSION}.jar -o /opt/embulk.jar

WORKDIR /work
RUN ["java", "-jar", "/opt/embulk.jar", "gem", "install", \
  "embulk-input-clickhouse", \
  "embulk-output-clickhouse", \
  "embulk-output-mysql" \
  ]

ENTRYPOINT ["java", "-jar", "/opt/embulk.jar"]
CMD ["--help"]