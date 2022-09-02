# Projet JAVA et base de données

### Création d'une programme JAVA pour consulter un annuaire

1. Créez un projet Java avec votre IDE favori

### Ajout du driver de MySQL

1. Téléchargez le driver pour MySQL et dézippez-le. Vous trouverez le lien ici :

`https://dev.mysql.com/downloads/connector/j/`

2. Ajoutez le fichier jar dans votre classpath (en faisant par exemple, clic droit sur votre projet > Propriétés > Java Build Path > Librairies > Ajouter JARs)

### Ecrire un programme affichant la liste de toutes les personnes

1. Connectez-vous a la base de données :

```java
Connection conn = DriverManager.getConnection("jdbc:mysql://machine:port/database_name", username, password);
```

avec les informations suivantes sur la base de données et son SGBDR :

```
Machine : remotemysql.com
Port : 3306
Nom de la base de données : PHLNFTXzxE
Username : PHLNFTXzxE
Mot de passe : G3GzbM0OC7
```

2. Construire une requete SQL pour récupérer toutes les personnes de la base de données :


