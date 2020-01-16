FROM openjdk:latest

RUN java -version
COPY . .
RUN ./mvnw package
CMD java -jar ./target/docker-example-1.1.3.jar