FROM eclipse-temurin:17

LABEL mentainer="ahmed.kamel1798@yahoo.com"

WORKDIR /app

COPY target/springboot-docker-demo-0.0.1-SNAPSHOT.jar /app/springboot-docker-demo.jar

ENTRYPOINT ["java", "-jar", "springboot-docker-demo.jar"]