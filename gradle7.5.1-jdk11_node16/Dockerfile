FROM  gradle:7.5.1-jdk11

RUN apt-get update
RUN mkdir /node && cd /node
RUN curl -sL https://deb.nodesource.com/setup_16.x | bash -
RUN apt -y install nodejs