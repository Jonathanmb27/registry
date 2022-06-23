FROM openjdk:8
VOLUME /temp
EXPOSE 8761
ADD ./target/service-registry-0.0.1-SNAPSHOT.jar registry.jar
ENTRYPOINT ["java","-jar","registry.jar"]