FROM openjdk:8
ADD target/consumer.jar /consumer.jar
EXPOSE 8091
ENTRYPOINT ["java", "-jar", "consumer.jar"]