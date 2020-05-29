FROM openjdk:8
ADD target/producer.jar /producer.jar
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "producer.jar"]