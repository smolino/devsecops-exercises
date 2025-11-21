FROM eclipse-temurin:8

RUN apt-get update && \
    apt-get install build-essential maven default-jdk cowsay netcat-traditional -y && \
    update-alternatives --auto javac
COPY . .

CMD ["mvn", "spring-boot:run"]
