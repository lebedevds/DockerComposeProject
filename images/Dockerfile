FROM ubuntu:18.04
RUN apt update && apt install git maven default-jdk -y
WORKDIR /tmp/
RUN git clone https://github.com/boxfuse/boxfuse-sample-java-war-hello.git
RUN mvn package -f /tmp/boxfuse-sample-java-war-hello/pom.xml