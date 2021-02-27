FROM openjdk:8-oraclelinux7
WORKDIR /opt/
COPY build.jar /opt/
COPY start.sh /opt/
RUN yum install git -y
ENTRYPOINT ["/bin/sh", "/opt/start.sh"]
