FROM openjdk:8u181-jdk-alpine

RUN mkdir -p /maven/acmeair/

COPY ./*-exec.jar  /maven/acmeair/

ENTRYPOINT java $JAVA_OPTS -jar /maven/acmeair/$JAR_NAME-exec.jar
