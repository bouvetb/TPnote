Web

	Permet de communiquer facilement avec des apis web
	
JPA

	Permet d'utiliser le sql et les bdd
	
Hibernate

	Permet une connexion et une relation avec la bdd plus facilement
	
H2

	syst�me de gestion de base de donn�es relationnelles �crit en Java
	
DevTools

	offre des outils en plus pour le d�veloppement
	
Thymeleaf

	permet de generer du HTML en java
	
Etape 13 

	Q1 @GetMapping("/greeting")
	
	Q2 return "greeting";
	
	Q3 @RequestParam(name="nameGET", required=false, defaultValue="World")
	
Etape 17

	La table adresse a été créé
	
Etape 18

	Hibernate permet grâce aux annotations d'acceder a la base de donnée et vue que la table n'éxistait pas il l'a créée
	
Etape 20

	Oui on voit tous le contenus de la table adresse ajouté dans le fichier Data.sql
	
Etape 23

	C’est une annotation qui nous permet de faire l’injection de dépendances entre les beans de l’application
	
Etape 30 

 	ajout de dépendance :
 	<dependency>
	    <groupId>org.webjars</groupId>
	   	<artifactId>bootstrap</artifactId>
		<version>3.3.6</version>
	</dependency>

	<dependency>
	    <groupId>org.webjars</groupId>
	    <artifactId>bootstrap-datepicker</artifactId>
	    <version>1.0.1</version>
	</dependency>

	<dependency>
	    <groupId>org.webjars</groupId>
	    <artifactId>jquery</artifactId>
	    <version>1.9.1</version>
	</dependency>