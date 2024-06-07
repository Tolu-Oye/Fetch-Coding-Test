FROM openjdk:17

WORKDIR /app

COPY target/receiptprocessor-0.0.1-SNAPSHOT.jar receiptprocessor.jar

EXPOSE 8080

ENTRYPOINT ["java", "-jar", "receiptprocessor.jar"]