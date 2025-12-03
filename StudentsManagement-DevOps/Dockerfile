# Utiliser une image JDK 17 officielle fonctionnelle
FROM eclipse-temurin:17-jdk

# Copier le jar compilé dans le conteneur
COPY target/StudentsManagement-DevOps-1.0-SNAPSHOT.jar app.jar

# Définir la commande par défaut pour lancer l'application
ENTRYPOINT ["java", "-jar", "/app.jar"]
