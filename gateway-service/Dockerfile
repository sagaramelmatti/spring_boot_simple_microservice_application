FROM openjdk:11-jre-slim
ADD target/gateway-service-*.jar app.jar
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]
