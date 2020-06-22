FROM flink:1.9
EXPOSE 6123
RUN apt-get update && apt-get install -y \
    python3-pip
RUN ["pip3", "install", "apache-flink>=1.9.0,<1.10.0"]