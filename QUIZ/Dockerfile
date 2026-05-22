# 1. Cambiamos openjdk por una imagen mantenida y oficial (Eclipse Temurin)
FROM eclipse-temurin:21-jre-alpine

# 2. Creamos un directorio de trabajo limpio
WORKDIR /app

# 3. Copiamos tu JAR usando el nombre exacto que se ve en tu captura
COPY target/QUIZ-1.jar app.jar

# 4. Exponemos el puerto
EXPOSE 8097

# 5. Comando para arrancar
ENTRYPOINT ["java", "-jar", "app.jar"]