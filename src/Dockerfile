from ubuntu

run						\
		apt-get -y update		\
	&&      apt-get -y install vim		\
	&&	apt-get -y install iputils-ping	\
	&&      apt-get -y install net-tools	\
	&&	apt-get -y install curl		\
	&&	apt-get -y install default-jdk	\
	&&      apt-get -y install git		\
	&&      apt-get -y install subversion	\
	&&      apt-get -y install mc		\
	&&      apt-get -y install wget		\
	&&      apt-get -y install screen	\
	&&      apt-get -y install maven

run wget https://fastdl.mongodb.org/linux/mongodb-linux-x86_64-ubuntu1604-3.6.0.tgz
run tar -zxf ./mongodb-linux-x86_64-ubuntu1604-3.6.0.tgz
run rm ./mongodb-linux-x86_64-ubuntu1604-3.6.0.tgz
run mv ./mongodb-linux-x86_64-ubuntu1604-3.6.0 /etc/mongo
run mkdir --parents /data/db
ENV PATH="/etc/mongo/bin:${PATH}"
