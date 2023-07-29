#From openjdk:8-jdk-alpine3.9
FROM ubuntu
RUN apt update
RUN apt install -y openjdk-8-jdk
WORKDIR /myapp
COPY HelloWorld.class .
CMD java HelloWorld