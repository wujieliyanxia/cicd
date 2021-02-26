FROM openjdk:8-oraclelinux7
WORKDIR /opt/
COPY build.jar /opt/
COPY start.sh /opt/
RUN ssh-add /root/.ssh/id_rsa
ENTRYPOINT ["/bin/sh", "/opt/start.sh"]