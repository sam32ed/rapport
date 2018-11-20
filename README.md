# Rapport 

-AbdelAli AbdeSamed

-Remadna Mouadh

# L’ARCHITECTURE DE L’APPLICATION

  ## Utilise l’architecture MICROSERVICE
     
**_ Micro Service _:** est une architecture qui permet aux développeurs de développer et de
    
déployer des services indépendamment. Chaque service exécutant a son propre processus et

cela atteint le modèle léger pour soutenir les applications métier.

Dans cette architecture en décomposé l’application en plusieurs petite service chaque

service de ce service appelé microservice et chaque microservice contient ça proche base de

donnée et chaque microservice il a un code et implémentation déférant

Alors si un service tombe en panne, les autres service marche normale et les développeurs

corrige cette service sans touché les autres service et le site marche normale

Et peut-être modifier ou supprimé ou ajouté un service « microservice » sans modifier tout

le système et sans touche les autres services

Alors décomposé le travaille a des groupes défirent chaque groupe développe un

microservice

Après mettons les microservice dans des « container » le container délivré le code vers ça proche place

Placé chaque microservice dans ça place

Et chaque microservice peut être contacté les autres par utilise API

Le client envoi un requête vers le site

La requête envoi vers le API Gateway après l’API choisi le service qui traité cette requête

après le traitement envoi la réponse vers l’API Gateway et envoi vers le client

-Si vous êtes amenés à travailler sur une application développée autour de l'architecture Microservices en Java, vous aurez 

tôt ou tard affaire à Spring Boot . Dans ce chapitre, nous allons donc prendre le temps de comprendre ce que fait ce

framework et surtout lever l'ambiguïté sur la différence avec les autres framework

Spring, qui à première vue font la même chose.

## L'outil utilisé

**Spring boot :** Spring Boot est un framework qui facilite le développement d'applications fondées sur Spring

### Problemes :

-beaucoup de configurations Spring et Spring MVC sont de formidables outils quand on

essaye de développer une application web. Néanmoins, un de leurs plus gros problèmes est

la configuration. Si vous avez déjà développé une application avec ces outils, vous avez dû

remarquer que votre application est bardée de fichiers XML qui indiquent les configurations

des servlets, des vues, des contenus statiques, etc. Ces fichiers de configuration deviennent

un vrai challenge lorsque vous avez une application complexe. Pour resouder les problemes

dans spring en n’utilse spring boot


Pour simplifier cette configuration, Spring Boot propose 2 fonctionnalités principales

que nous allons voir dans la suite de ce chapitre :

1. **l'auto-configuration** :

Cette fonctionnalité est la plus importante de Spring Boot. Elle permet de configurer

automatiquement votre application à partir des jar trouvés dans votre Classpath

2. **les starters** :

Les starters viennent compléter l'auto-configuration et font gagner énormément de

temps, notamment lorsqu'on commence le développement d'un Microservice. Un

starter va apporter à votre projet un ensemble de dépendances, communément

utilisées pour un type de projet donné. Ceci va vous permettre de créer un

"squelette" prêt à l'emploi très rapidement.


