# Use a imagem base do OpenJDK 17
FROM openjdk:17-jdk-slim

# Defina a pasta de trabalho no contêiner
WORKDIR /app

# Copie o arquivo .jar para o contêiner
COPY jar/demo-authorizationserver-v1.3.0-SNAPSHOT.jar /app/demo-authorizationserver.jar

# Exponha a porta 9000
EXPOSE 9000

# Comando para iniciar a aplicação
ENTRYPOINT ["java","-jar","/app/demo-authorizationserver.jar"]
