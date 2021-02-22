FROM openjdk:8-oraclelinux7
WORKDIR /opt/
COPY build.jar /opt/
COPY start.sh /opt/
ENTRYPOINT ["/bin/sh", "/opt/start.sh"]