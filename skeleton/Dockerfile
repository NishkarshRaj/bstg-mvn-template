FROM openjdk:8-jdk-alpine@sha256:94792824df2df33402f201713f932b58cb9de94a0cd524164a0f2283343547b3
LABEL maintainer="nishkarshraj000@gmail.com"
COPY target/*.jar app.jar
ENTRYPOINT ["java","-jar","/app.jar"]
