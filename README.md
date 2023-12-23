# PayMyBuddy
Openclassrooms Project6s

## Description

Pay My Buddy est une application conçue pour faciliter les transactions financières entre amis. Elle permet aux utilisateurs de payer, de se faire rembourser et de gérer leurs finances personnelles de manière simple et sécurisée

## Fonctionnalités

Transferts d'argent : Envoyez et recevez de l'argent de vos amis instantanément.
Gestion de compte : Suivez vos dépenses et visualisez votre historique de transactions.

## Technologies et Dépendances

Le projet est construit avec les technologies suivantes :

Spring Boot (version 3.1.5)
Java (version 17)
Spring Data JPA
Spring Boot Security & OAuth2 Client
Thymeleaf
MySQL Connector/J
JaCoCo (version 0.8.7)
Maven Surefire Report Plugin (version 3.1.2)

## Livrables:
- Le diagramme de classe UML:   

  ![image](https://github.com/DAVID-EL-CHAAR/New-Project-5/assets/80713536/5a101b38-abf5-4c52-9439-963eddf90dc7)

  
- Le modèle physique de données:   

  ![Capture d’écran (214)](https://github.com/DAVID-EL-CHAAR/New-Project-5/assets/80713536/75631255-f42b-40d4-88cc-4f7c54d24abf)


### Interface web:
- Login:
  
  <img width="424" alt="icon" src="https://user-images.githubusercontent.com/65612959/138293033-2d091f37-3bf8-4fdd-9f28-f91c07e4ca38.png">
  
- Home:
  
  <img width="1236" alt="home" src="https://user-images.githubusercontent.com/65612959/139069938-70d5e3d6-baf1-4072-8435-4d301efabce9.png">

  

#### Note: 
- Une fois un compte a été créé, il faut mettre au moins 1€ dedans pour activer le compte.  

- Pour démarrer l'application, ajouter `application.properties` sous `resources`:
  ```properties
  spring.jpa.database-platform=org.hibernate.dialect.MySQL8Dialect
  spring.jpa.hibernate.ddl-auto=update
  spring.datasource.driverClassName=com.mysql.cj.jdbc.Driver
  spring.datasource.url=jdbc:mysql://localhost:3306/pay_my_buddy?createDatabaseIfNotExist=true&allowPublicKeyRetrieval=true&characterEncoding=utf8&useSSL=false&useJDBCCompliantTimezoneShift=true&useLegacyDatetimeCode=false&serverTimezone=UTC
  spring.datasource.username=your_username
  spring.datasource.password=your_password
  spring.jpa.open-in-view=false
  server.error.whitelabel.enabled=false
  ```
  
#### Jacoco test couverture sur la couche du service:   
  
  <img width="1035" alt="jacoco_p6" src="https://user-images.githubusercontent.com/65612959/139065464-314d74c7-1de9-48da-bac9-161729bd1ef0.png">

  
- Le modèle physique de données:   

  <img width="883" alt="modele_p6" src="https://user-images.githubusercontent.com/65612959/138292655-e71c6c53-4ba5-4758-8f59-ea7f3b42351f.png">


