FROM java:8
ADD /target/eureka-server.jar /eureka-server.jar
EXPOSE 8090
ENTRYPOINT ["java", "-jar", "eureka-server.jar"]