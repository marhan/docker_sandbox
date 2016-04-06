FROM marhan/rpi-java8
VOLUME /tmp
EXPOSE 8080
ADD ./dockerrpisamplerest-0.0.1-SNAPSHOT.jar app.jar
RUN bash -c 'touch /opt/app.jar'
ENTRYPOINT ["java", "-Djava.security.egd=file:/dev/./urandom", "-jar","/app.jar"]
