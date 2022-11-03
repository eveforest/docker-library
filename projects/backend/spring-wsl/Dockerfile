FROM openjdk:8
MAINTAINER evef
ENV LANG=C.UTF-8 LC_ALL=C.UTF-8 APP_HOME=/opt/spring-wsl
VOLUME /tmp
RUN mkdir -p $APP_HOME
WORKDIR $APP_HOME
ADD spring-wsl-0.0.1-SNAPSHOT.jar spring-wsl.jar
ENTRYPOINT java -jar spring-wsl.jar
EXPOSE 8082
