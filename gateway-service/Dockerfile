# Usar una imagen base con JDK
FROM openjdk:17-jdk-slim

# Configurar el directorio de trabajo
WORKDIR /app

# Copiar el archivo JAR generado
COPY target/gateway-service-1.0.jar app.jar

# Exponer el puerto del servicio
EXPOSE 8080

# Comando para ejecutar la aplicación
ENTRYPOINT ["java", "-jar", "app.jar"]
