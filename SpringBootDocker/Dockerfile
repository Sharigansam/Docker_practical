FROM openjdk:17
WORKDIR /usr/app
COPY target/SpringBoot-docker.jar /usr/app
EXPOSE 8080
ENTRYPOINT ["java","-jar","SpringBoot-docker.jar"]
