# Docker

## Contexte

<img src="../../../img/docker2.png" height="150" style="float: left; margin-right: 5px">

[Docker](https://www.docker.com/){:target="_blank"} est une **technologie de conteneurisation** qui permet de créer des
conteneurs isolés pour exécuter des applications de manière fiable et cohérente sur différents environnements. La
conteneurisation est un principe qui vise à **isoler les processus d'une machine**, chaque applicatif fonctionnant
dans son propre micro-système afin de ne pas dépendre d'autres composants.

Contrairement à la virtualisation, qui émule un ordinateur complet, la conteneurisation ne fait fonctionner que la
partie logicielle nécessaire et peut interagir directement avec le noyau de la machine, ce qui la rend plus légère que
la virtualisation. Cela en fait un choix idéal pour isoler des applications uniques sur un système plus complet.

Docker a été créé en 2013 par Solomon Hykes lors d'un hackathon interne
chez [dotCloud](https://www.docker.com/press-release/dotcloud-inc-now-docker-inc/){:target="_blank"}, une entreprise
de [PaaS](https://azure.microsoft.com/fr-ca/resources/cloud-computing-dictionary/what-is-paas){:target="_blank"}. Hykes
a créé Docker pour résoudre un problème de déploiement de code chez dotCloud, mais la technologie a rapidement attiré
l'attention de la communauté open-source et a depuis connu un succès mondial.

Il est devenu un outil de conteneurisation très populaire dans le monde de l'informatique. Depuis sa création
en 2013, Docker a révolutionné la façon dont les applications sont déployées sur des infrastructures à grande échelle.

Récemment le lancement de [Docker Enterprise 3.1](https://www.docker.com/products/docker-enterprise){:target="_blank"},
a dernière version de leur plateforme de conteneurs d'entreprise a été annoncé. Cette version
est conçue pour faciliter la mise en place d'une infrastructure de conteneurs en entreprise et répondre aux besoins
spécifiques des grandes organisations.

Dans le contexte des entreprises, Docker est largement utilisé pour différentes applications, notamment la
virtualisation de serveurs, la création de plateformes d'applications, et la mise en place de pipelines de livraison
continue. De plus en plus d'entreprises utilisent Docker pour **accélérer la mise en production de leurs applications**
tout en **réduisant les coûts et les risques associés**.

Il est également utilisé dans le domaine de l'
[Internet des objets (IoT)](https://www.ovhcloud.com/fr/learn/what-is-iot/){:target="_blank"}. La conteneurisation
permet de déployer des applications IoT de manière plus efficace et sécurisée en isolant les applications les unes
des autres et en assurant une meilleure gestion des ressources.

Enfin, Docker est de plus en plus utilisé dans le **domaine de l'apprentissage automatique (machine learning)** et de
**l'intelligence artificielle (IA)**. La conteneurisation permet de déployer facilement des modèles d'apprentissage
automatique et de les exécuter sur des infrastructures à grande échelle.

## Mes expériences

J'ai régulièrement eu l'occasion de mettre en avant ma maîtrise de Docker sur 
[les projets clients iTESOFT](../../../mes-réalisations/projets-itesoft).

Un jour, j'ai dû intervenir pour aider un collègue de travail qui était en assistance chez un client pour l'aider à 
déployer sa plateforme de production. Les applications dockerisées ne parvenait pas
à établir une connexion avec la base de données, ce qui compromettait tout le fonctionnement de la plateforme.

Le temps était compté car le client allait avoir besoin de faire fonctionner l'environment avant la fin de la journée.
Il était donc crucial de trouver une solution rapidement. Fort heureusement, grâce à ma maîtrise de
Docker, j'ai rapidement compris que le problème était lié à la configuration du réseau interne des conteneurs.

Je me suis immédiatement plongé dans les fichiers de configuration de Docker Compose, et après une analyse minutieuse,
j'ai identifié une erreur dans les paramètres de réseau attribués aux conteneurs. J'ai rapidement corrigé cette erreur
en ajustant les configurations pour rétablir la communication.

Une fois les modifications apportées, j'ai redéployé les conteneurs concernés. Cette fois-ci, tout a
fonctionné parfaitement. L'application dockerisée a pu se connecter à la base de données sans aucun problème, et 
nous avons pu terminer le déploiement de la plateforme dans les temps.

Cette expérience m'a permis de démontrer ma maîtrise de Docker et ma capacité à résoudre des problèmes complexes liés à
la configuration des conteneurs. Grâce à mes connaissances approfondies et à ma compréhension des mécanismes internes de
Docker, j'ai pu diagnostiquer rapidement le problème et apporter une solution efficace.

Cette intervention m'a également permis de montrer à l'équipe que je pouvais être un atout précieux dans 
la résolution de problèmes techniques liés à Docker.

## Mon niveau d’acquisition de la compétence

En ce qui me concerne, je pense **avoir acquis une forte expertise en Docker** grâce à mon travail chez iTESOFT. Nous 
utilisons Docker pour déployer nos produits chez les clients, ce qui nous permet de les personnaliser rapidement et 
efficacement. J'ai également utilisé Docker dans des projets personnels pour créer des environnements de 
développement cohérents.

## Conseil

Si je devais donner un conseil à quelqu'un qui découvre la conteneurisation avec Docker, je conseillerais de bien
comprendre la différence entre la conteneurisation et la virtualisation. Dans la virtualisation, le système
d'exploitation est totalement indépendant de la machine hôte, tandis qu'avec la conteneurisation, le système
d'exploitation est partagé entre l'hôte et le conteneur.

![vm-vs-containers.png](/portfolio/img/vm-vs-containers.png)

Ensuite, je conseillerais de toujours créer un conteneur pour chaque "service" ou processus de son application. Cela
permet de mieux gérer les dépendances entre les différents services et de les mettre à jour ou de les répliquer plus
facilement.

Pour aller plus loin :

- [Une présentation de Docker par Solomon Hykes](https://www.youtube.com/watch?v=Q5POuMHxW-0){:target="_blank"}
- [La documentation officielle Docker](https://docs.docker.com/){:target="_blank"}

## Projets liés

- [PingScore](../../../mes-réalisations/pingscore)
- [Toolkit Delivery](../../../mes-réalisations/toolkit-delivery)
- [Projets clients iTESOFT](../../../mes-réalisations/projets-itesoft)
