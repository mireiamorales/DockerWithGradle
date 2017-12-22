FROM alpine:latest
RUN apk --update add openjdk8-jre
COPY '/Users/Mireia/Docker/docker-hello-world-example/build/libs/docker-hello-world-example.jar' app.jar
ENTRYPOINT ["java", "-Djava.security.egd=file:/dev/./urandom", "-jar", "app.jar"]