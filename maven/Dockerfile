FROM ubuntu:18.04
RUN apt update && apt install git maven default-jdk -y
RUN git clone https://github.com/boxfuse/boxfuse-sample-java-war-hello.git
RUN mvn package -f ./boxfuse-sample-java-war-hello/pom.xls