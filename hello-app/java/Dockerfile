FROM openjdk:11
COPY . /usr/src/demo
WORKDIR /usr/src/demo
RUN ./gradlew build
CMD ["java", "-jar", "build/libs/demo-0.0.1-SNAPSHOT.jar"]
