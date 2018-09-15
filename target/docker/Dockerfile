FROM dockerfile/java:oracle-java8

VOLUME /tmp
ADD Helloindia.jar /opt/Helloindia/
EXPOSE 8080
WORKDIR /opt/Helloindia/
CMD ["java", "-Djava.security.egd=file:/dev/./urandom", "-Xms512m", "-Xmx1g", "-jar", "Helloindia.jar"]
