FROM openjdk:8
ADD target/zuul-server.jar /zuul-server.jar
EXPOSE 8762
ENTRYPOINT ["java", "-jar", "zuul-server.jar"]