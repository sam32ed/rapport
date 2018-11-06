# Rapport 

-AbdelAli AbdeSamed

-Remadna Mouadh

**Spring boot :** makes it easy to create stand alone « ne besoin pas un server container comme tomcat

ou glasfish pour excuté ton app»application à base de spring de production que vous pouvez juste excuté .


**Spring "web MVC" :** application framework (build enterprise-grade java applications ) 

laissez-vous concentrer sur l'écriture de code et le spring gère d'autres choses comme :
   
   -bd connection
   
   -running query 
   
   -handle http requests(mvc layer) 
   
   pour faire ça **spring** utilise  **annotation**
   
   ** problèmes : **
   
       -étreinte framework 
       
       -beaucoup de configurations
  
  Pour resouder les problemes dans spring en n’utilse **spring boot** 

-Easy deployment

-Simple scalability

-Compatible with Containers

-Minimum configuration

-Easy to understand and develop spring applications

-Increases productivity

-Reduces the development time

#SpringBoot Framework MVC Model View Controller :

      Composante de :
          
          -Dispatcher servlet
          
          -Handler mapping

          -Model and view

          -View 
Controller view Resolver


1. Le client envoi un requête vers l’app 

2. Dispatcher c’est le premier interface recus la requete « front Controller »

3. Le dispatcher trouver les input a partir le handler (Le handler il existe dans un fichier xml )

4. Après le dispatcher cheminée la requête vers le controler qui return le MV « model and view »

5. le dispatcher faire un check aprtir le view  resolver dans le fichier xml

  Si la request il existe dans le view resolver 

6. Le dispatcher appelle le view **affiché le résultat**

```
pour traité polusieur demande de plusieur clint nous doivent utilise les threads **serveur concurrent**

pour chaque client crée un thread ce thread traité la demende et return le Résultat 
```
