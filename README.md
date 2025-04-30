# P6-App-Full-Stacks

SpringBoot : 2.7.3  
Java : 11  
Maven : 4.0.0  
Angular CLI : 14.1.3  

Par Franck N

## Installations

1. [Angular CLI](https://angular.io/cli)
2. [Node.js](https://nodejs.org/)
3. [Java 11](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html)
4. [MySQL Server and MySQL Workbench](https://dev.mysql.com/downloads/)
5. [Maven](https://maven.apache.org/)

## Téléchargement du projet

```sh
git clone https://github.com/ShaiD9/P6-Full-Stack-reseau-dev.git
```

## Configuration et exécution 
### Back-end et MySQL

1. Rendez-vous sur l'adresse suivante : localhost
2. Connectez-vous puis créez une base de données avec le nom de votre choix
3. Ouvrez le fichier application.properties situé dans back/src/main/resources.
4. Insérez votre url de base de données, identifiant, mot de passe et clé secrete, (utiliser un .env si possible) SQL Server pour les lignes suivantes :

```sh
spring.datasource.url=jdbc:mysql://localhost:3306/nom_de_votre_db
spring.datasource.username=user
spring.datasource.password=mot_de_passe
jwt.secret=clé_secrète
```

5. Naviguez vers le dossier back :
```sh
cd back
```
5. Installez les dépendences :
```sh
mvn clean install
```
7. Exécutez le back-end :
```sh
mvn spring-boot:run
```

### Front-end

1. Naviguez vers le dossier front :
```bash
cd front/
```

2. Installez les dépendences :
```bash
npm install
```

3. Exécutez le front-end :
```bash
npm run start
```