#### 1-) Attaques et types d'attaques informatiques
L'informatique, bien qu'elle ait facilité le travail des humains, 
rencontre elle aussi des menaces. Cette dernière fait face à des attaques et à des types d'attaque multiples à savoir:
|Attaques informatiques            |    Types d'attaques informatiques             |
|----------------|-----------------|
|Attaque TCP SYN flood, Attaque teardrop, Attaque smurf, Ping of death, Botnets|Attaque par déni de service (DoS/DDoS)|
|Vers, virus, bombe logique, chevaux de troie|Attaque par logiciels malveillants|
| Écoute clandestine passive, écoute clandestine active | Attaque par écoute illicite  |
| Les attaques par force brute, les attaques par dictionnaire                       |   Attaque par mot de passe                  |
|Detournement de session, Usurpation d'IP, Relecture|Attaque de l’homme du milieu (man-in-the-middle)|
||Attaque par injection SQL|

  Une base de données est un ensemble d'informations qui est organisé de manière à être facilement accessible, géré et mis à jour. Cette dernière fait face à des attaques. Les attaques et les types d'attaque dont elle fait face sont multiples. Voici les attaques et les types d'attaque dont une base de données fait face:
  Attaque par déni de service (DoS/DDoS), Attaque par injection SQL
  
  2-) 	Les fichiers de données de MySQL se trouvent :  
Dans Windows 8.1, les bases de données MySQL sont stockées (par défaut) ici:
Le dossier C:\ProgramData est un dossier caché. Vous devez donc le saisir dans l’adresse de l’explorateur Windows pour y accéder. Dans ce dossier de données, les bases de données sont nommées /{database_name_folder}/{database_tables_and_files}. 
Par exemple, 
C:\ProgramData\MySQL\MySQL Server 5.6\data\mydatabase\mytable.frm  
C:\ProgramData\MySQL\MySQL Server 5.6\data\mydatabase\mytable.ibd
  
Extension des fichiers MySQL :  
.sql    
Les fichiers de données de PostgreSQL se trouvent :  
Les fichiers de données sont les fichiers occupant la majeure partie de la base de données, leur taille peut osciller entre quelques Mégaoctets et plusieurs gigaoctets. Ceux-ci contiennent en effet toutes les données relatives à la base Oracle dans un format propriétaire. Ainsi pour modifier les informations contenues dans la base de données il est impossible d'intervenir directement sur ces fichiers; la bonne procédure à adopter consiste à modifier le contenu de la base de données par l'intermédiaire d'ordres SQL.
Les fichiers de données contiennent des informations de deux types :  

Le dictionnaire de données et de travail:  
 Les données des utilisateurs,  
 La lecture de ces fichiers de données est faite à l'aide des * processus utilisateurs tandis que l'écriture est assuré par le processus DBWR (Database Writer)  
Extension des fichiers PostgreSQL :  
.psql  
Les fichiers de données d’Oracle se trouvent :    
Extension des fichiers Oracle :    
       .dbf    
Les fichiers de données Ms SQL server se trouvent :    
Au minimum, chaque base de données SQL Server a deux fichiers de système d’exploitation : un fichier de données et un fichier journal. Les fichiers de données contiennent des données et des objets tels que des tables, des index, des procédures stockées et des vues. Les fichiers journaux contiennent les informations nécessaires pour récupérer toutes les transactions de la base de données. Les fichiers de données peuvent être regroupés dans des groupes de fichiers à des fins 
d'allocation et d'administration.   Les fichiers de données se situent généralement dans un répertoire enfant nommé « Data ». Par exemple, spécifiez C:\Program Files\Microsoft SQL Server\MSSQL{nn}.<nom_instance>\ comme chemin racine du répertoire de données des bases de données système durant la mise à niveau quand les fichiers de données se trouvent sous C:\Program Files\Microsoft SQL Server\MSSQL{nn}.<nom_instance>\MSSQL\Data.  

Extension des fichiers Ms SQL server :  
.mdf    
3-) La politique de sécurité selon l’ITSEC est la suivante :  
 Les ITSEC définissent la politique de sécurité comme l’ensemble des lois règles ou pratiques qui régissent la façon dont l’information sensible et les autres ressources sont gérées, protégées et distribuées à l’intérieur d’un système d’information.

4-)
   |Principes de sécurité           |    Attaques             |
|----------------|-----------------|
|Intégrité|Modification, Rejeu, usurpation d’identité, répudiation|
|Disponibilité|Déni de service               |
|Confidentialité       | Espionnage, analyse du trafic  |
| Authentification                       |  Cassage du mot de passe                    |



