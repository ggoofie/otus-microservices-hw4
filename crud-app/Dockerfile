FROM bellsoft/liberica-openjdk-alpine-musl:21
COPY target/CrudApp-0.0.1-SNAPSHOT.jar app.jar
EXPOSE 8080
ENTRYPOINT ["java","-jar","/app.jar"]