from ubuntu:16.04

run apt-get -y update
run apt-get -y install vim
run apt-get -y install iputils-ping
run apt-get -y install net-tools
run apt-get -y install curl
run apt-get -y install default-jdk
run apt-get -y install git
run apt-get -y install subversion
run apt-get -y install mc
run apt-get -y install wget
run apt-get -y install screen
run apt-get -y install maven
run apt-get -y install libstdc++5

run wget https://fastdl.mongodb.org/linux/mongodb-linux-x86_64-ubuntu1604-3.6.0.tgz
run tar -zxf ./mongodb-linux-x86_64-ubuntu1604-3.6.0.tgz
run rm ./mongodb-linux-x86_64-ubuntu1604-3.6.0.tgz
run mv ./mongodb-linux-x86_64-ubuntu1604-3.6.0 /etc/mongo
run mkdir --parents /data/db
ENV PATH="/etc/mongo/bin:${PATH}"

ENV JAVA_HOME="/usr/lib/jvm/default-java"
