# <img src="Docker_logo.svg.png" alt="Docker" width="200" style="float: left"/>

Docker est une plateforme permettant de lancer certaines applications dans des conteneurs logiciels.

Selon la firme de recherche sur l'industrie 451 Research, « Docker est un outil qui peut empaqueter une application et ses dépendances dans un conteneur isolé, qui pourra être exécuté sur n'importe quel serveur ». Il ne s'agit pas de virtualisation, mais de conteneurisation, une forme plus légère qui s'appuie sur certaines parties de la machine hôte pour son fonctionnement. Cette approche permet d'accroître la flexibilité et la portabilité d’exécution d'une application, laquelle va pouvoir tourner de façon fiable et prévisible sur une grande variété de machines hôtes, que ce soit sur la machine locale, un cloud privé ou public, une machine nue, etc.

Techniquement, Docker étend le format de conteneur Linux standard, LXC, avec une API de haut niveau fournissant une solution pratique de virtualisation qui exécute les processus de façon isolée. Pour ce faire, Docker utilise entre autres LXC, cgroups et le noyau Linux lui-même1. Contrairement aux machines virtuelles traditionnelles, un conteneur Docker n'inclut pas de système d'exploitation, mais s'appuie au contraire sur les fonctionnalités du système d’exploitation fournies par la machine hôte.

La technologie de conteneur de Docker peut être utilisée pour étendre des systèmes distribués de façon à ce qu'ils s'exécutent de manière autonome depuis une seule machine physique ou une seule instance par nœud. Cela permet aux nœuds d'être déployés au fur et à mesure que les ressources sont disponibles, offrant un déploiement transparent et similaire aux PaaS pour des systèmes comme Apache Cassandra, Riak, ou d'autres systèmes distribués.

## La notion de conteneur <a class="lbLink" href="#container-what-is-container" style="float: right"><img src="container-what-is-container.png" width="300"></a>

<div class="lb" id="container-what-is-container">
	<a href="#" onclick="window.history.back(-1)"><img src="container-what-is-container.png" alt=""/></a>
</div>
L'objectif d'un conteneur est le même que pour un serveur dédié virtuel : héberger des services sur un même serveur physique tout en les isolant les uns des autres. Un conteneur est cependant moins figé qu'une machine virtuelle en matière de taille de disque et de ressources allouées.

Un conteneur permet d'isoler chaque service : le serveur web, la base de données, des applications pouvant être exécutées de façon indépendante dans leur conteneur dédié, contenant uniquement les dépendances nécessaires. Chaque conteneur peut être relié aux autres par des réseaux virtuels. Il est possible de monter des volumes de disque de la machine hôte dans un conteneur. Si aucun processus n'est démarré dans le conteneur, alors celui-ci s'arrête. On parle parfois de virtualisation d'OS : contrairement à la virtualisation qui émule par logiciel différentes machines sur une machine physique, la conteneurisation émule différents OS sur un seul OS.

## Cadre projet web app

{{à définir!}}