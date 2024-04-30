FROM openjdk:21-oracle
ARG JAR_FILE=*.jar
COPY ${JAR_FILE} reversi-server.jar
EXPOSE 8080
CMD apt-get update -y
ENTRYPOINT ["java","-jar","reversi-server.jar"]
