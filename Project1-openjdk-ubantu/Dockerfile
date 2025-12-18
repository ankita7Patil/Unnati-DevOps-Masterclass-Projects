FROM ubuntu:22.04

ENV DEBIAN_FRONTEND=noninteractive

RUN apt-get update && \
    apt-get install -y openjdk-17-jdk && \
    apt-get clean && \
    rm -rf /var/lib/apt/lists/*


ENV JAVA_HOME=/usr/lib/jvm/java-17-openjdk-amd64
ENV PATH=/usr/lib/jvm/java-17-openjdk-amd64/bin:\$PATH


CMD ["/usr/lib/jvm/java-17-openjdk-amd64/bin/java", "-version"]
