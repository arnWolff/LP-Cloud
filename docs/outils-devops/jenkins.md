# <img src="Jenkins_logo.svg.png" alt="Jenkins" width="200" style="float: left"/>

Jenkins est un outil open source de serveur d'automatisation. Il aide à automatiser les parties du développement logiciel liées au build, aux tests et au déploiement, et facilite l'intégration continue et la livraison continue. Écrit en Java, Jenkins fonctionne dans un conteneur de servlets tel qu’Apache Tomcat, ou en mode autonome avec son propre serveur Web embarqué.

Il s'interface avec des systèmes de gestion de versions tels que CVS, Git et Subversion, et exécute des projets basés sur Apache Ant et Apache Maven aussi bien que des scripts arbitraires en shell Unix ou batch Windows.

Les générations de projets peuvent être amorcées par différents moyens, tels que des mécanismes de planification similaires au cron, des systèmes de dépendances entre générations, ou par des requêtes sur certaines URL spécifiques.

##Interface

<img src="Ansible-playbook-output-jenkins.png" alt="Jenkins interface" width="300"/>

## La notion d'intégration continue

L'intégration continue est un ensemble de pratiques utilisées en génie logiciel consistant à vérifier à chaque modification de code source que le résultat des modifications ne produit pas de régression dans l'application développée. Le concept a pour la première fois été mentionné par Grady Booch1 et se réfère généralement à la pratique de l'extreme programming. Le principal but de cette pratique est de détecter les problèmes d'intégration au plus tôt lors du développement. De plus, elle permet d'automatiser l'exécution des suites de tests et de voir l'évolution du développement du logiciel.

L'intégration continue est de plus en plus utilisée en entreprise afin d'améliorer la qualité du code et du produit final.

## Intérêt

L'intégration continue repose souvent sur la mise en place d'une brique logicielle permettant l'automatisation de tâches : compilation, tests unitaires et fonctionnels, validation produit, tests de performances… À chaque changement du code, cette brique logicielle va exécuter un ensemble de tâches et produire un ensemble de résultats, que le développeur peut par la suite consulter. Cette intégration permet ainsi de ne pas oublier d'éléments lors de la mise en production et donc ainsi améliorer la qualité du produit3.

Pour appliquer cette technique, il faut d'abord que :

* le code source soit partagé (en utilisant des logiciels de gestion de versions tels que CVS, Subversion, git, Mercurial, etc.) ;
* les développeurs intègrent (commit) quotidiennement (au moins) leurs modifications ;
* des tests d'intégration soient développés pour valider l'application (avec JUnit par exemple).

Un outil d'intégration continue est ensuite nécessaire tel que Jenkins. D'autres outils, comme SonarQube ou Jacoco, peuvent être mis en place afin de superviser la qualité du code2.

Les principaux avantages d'une telle technique de développement sont :

* le test immédiat des modifications ;
* la notification rapide en cas de code incompatible ou manquant ;
* les problèmes d'intégration sont détectés et réparés de façon continue, évitant les problèmes de dernière minute ;
* une version est toujours disponible pour un test, une démonstration ou une distribution.

## Cadre projet web app

{{à définir!}}