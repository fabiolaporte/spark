FROM debian

RUN apt-get update && apt-get install -y openjdk-17-jre wget procps

RUN wget https://dlcdn.apache.org/spark/spark-3.2.0/spark-3.2.0-bin-hadoop3.2.tgz

RUN tar xzf spark-3.2.0-bin-hadoop3.2.tgz

RUN /spark-3.2.0-bin-hadoop3.2/sbin/start-master.sh

CMD bash
