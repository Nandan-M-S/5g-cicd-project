FROM ubuntu:20.04

RUN apt update && apt install -y software-properties-common
RUN add-apt-repository ppa:open5gs/latest -y
RUN apt update && apt install -y open5gs

CMD ["sleep", "infinity"]
