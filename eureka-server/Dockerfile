FROM openjdk:11
COPY ./target/microservices-0.0.1-SNAPSHOT.jar app.jar
EXPOSE 9092
ENTRYPOINT ["java","-jar","app.jar"]