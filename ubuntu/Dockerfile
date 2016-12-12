FROM  	ubuntu:trusty
RUN 		apt-get update && apt-get install -y openjdk-7-jre
ADD 		slave.jar /root/slave.jar
ADD 		jenkins-slave /usr/local/bin/jenkins-slave
ENTRYPOINT ["/usr/local/bin/jenkins-slave"]
