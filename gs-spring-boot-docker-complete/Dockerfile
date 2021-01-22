Dockerfile
FROM openjdk:8-jdk-alpine
RUN cd / && mkdir target && chmod 777 -R /target
COPY  ./target/gs-spring-boot-docker-0.1.0.jar /target/
EXPOSE 3000
ENTRYPOINT ["java","-jar","/target/gs-spring-boot-docker-0.1.0.jar"]