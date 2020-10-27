Pour installer postgreSql en local : 
-------------------------------------
1 - Télécharger l'install suivants : 
	postgreSql version 13 : la base de données 
	https://www.enterprisedb.com/downloads/postgres-postgresql-downloads
		
2 - Lancer l'installation de postgreSql téléchargé à partir du premier lien.
	Dans le mot de passe saisir : blasacar (Pour être synchrone)
	Dans le port : 5432
	Tous le reste par defaut
	Ne pas installer stackbuilder dans la derniere étape (Ne sert à rien pour le moment)
	
Pour lancer le serveur postgreSql
---------------------------------

Lancer le script pg_env.bat qui est dans le répertoire de postgreSql
Le répertoire par defaut est C:\Program Files\PostgreSQL\13

Pour lancer pgAdmin
-------------------
Dans la recherche windows chercher pgAdmin et cliquer dessus.
Créer un nouveau serveur qui utilise les informations d'installation :
	Host : localhost
	Port : 5432
	Maintenace database : postgres
	Username : postgres
	Password : blasacar