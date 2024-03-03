FROM openjdk:17-jdk-slim
VOLUME /tmp
ARG JAR_FILE
COPY target/alquilatusvehiculos-0.0.1-SNAPSHOT.jar app.jar
ENTRYPOINT ["java","-jar","/app.jar"]