FROM maven:3.9.5-sapmachine-21
COPY . .
RUN mvn clean install
ENTRYPOINT [ "java", "-jar",  "target/demo-0.0.1-SNAPSHOT.jar" ] 