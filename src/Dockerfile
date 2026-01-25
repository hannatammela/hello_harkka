#Runtime stage
FROM eclipse-temurin:17-jdk
WORKDIR /app
COPY --from=builder /app/target/*.jar app.jar
EXPOSE  8000
ENTRYPOINT ["java", "-jar", "app.jar"]