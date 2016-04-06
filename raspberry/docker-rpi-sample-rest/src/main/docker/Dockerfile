FROM marhan/rpi-java8
VOLUME /tmp
ADD build/libs/dockerrpisamplerest-0.0.1-SNAPSHOT.jar app.jar
EXPOSE 8080
RUN bash -c 'touch /opt/app.jar'
ENTRYPOINT ["java", "-Djava.security.egd=file:/dev/./urandom", "-jar","/app.jar"]
