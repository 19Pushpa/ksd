FROM dockerfile/java:oracle-java8

VOLUME /tmp
ADD ksd.jar /opt/ksd/
EXPOSE 8080
WORKDIR /opt/ksd/
CMD ["java", "-Djava.security.egd=file:/dev/./urandom", "-Xms512m", "-Xmx1g", "-jar", "ksd.jar"]
