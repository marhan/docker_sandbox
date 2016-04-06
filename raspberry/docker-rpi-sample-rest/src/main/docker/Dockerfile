FROM marhan/rpi-java8
VOLUME /tmp
EXPOSE 8080
RUN bash -c 'touch /opt/app.jar'
ENTRYPOINT ["java", "-Djava.security.egd=file:/dev/./urandom", "-jar","/app.jar"]
