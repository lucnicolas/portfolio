# API

## Contexte

<img src="../../../img/api.png" width="50" height="50" style="float: left; margin-right: 5px">

Les APIs (Application Programming Interface) sont un ensemble de règles, de protocoles et de définitions qui 
**permettent à deux applications de communiquer entre elles**. les APIs sont largement utilisées dans le développement 
de logiciels, en particulier dans les applications web et mobiles, pour permettre à différents systèmes de partager 
des données et des fonctionnalités.

Les API sont généralement conçues pour être consommées par programme par d'autres applications, c'est pourquoi elles
sont appelées interfaces de programmation d'applications.

Voici quelques-uns des nombreux cas d'utilisation des API :

- **Tâches d'automatisation** : Créez un script qui exécute vos tâches manuelles automatiquement et par programmation.
  Exemple : Vous êtes un gestionnaire et le dernier jour de chaque période de paie, vous devez vous connecter
  manuellement au portail et télécharger la feuille de temps de chaque personne qui relève de vous. Ensuite, vous devez
  additionner manuellement le nombre d'heures travaillées par chaque personne afin de voir combien les payer. Si vous
  créez un script automatisé qui appelle l'API du portail pour obtenir les données de chaque feuille de temps et
  calculer le total à partir de ces données, votre script peut imprimer une liste du nombre total d'heures travaillées
  par personne dans un format convivial. Pensez au temps que cela vous ferait gagner !
- **Intégration de données** : Une application peut consommer ou réagir aux données fournies par une autre application.
  Exemple : de nombreux sites Web de commerce électronique utilisent des services de paiement accessibles via une API
  REST. L'interface de paiement permet à un site marchand de transmettre des données de valeur relativement faible,
  telles qu'une description de l'objet acheté et le prix. L'utilisateur s'authentifie alors indépendamment auprès du
  service de paiement pour confirmer le paiement. Cela permet au vendeur de recevoir le paiement sans avoir besoin d'un
  accès direct aux données de carte de crédit du client. Le fournisseur récupère un code de confirmation à utiliser par
  la comptabilité.
- **Fonctionnalité** : Une application peut intégrer la fonctionnalité d'une autre application dans son produit. 
  Exemple :
  de nombreux services en ligne, tels que Yelp et Uber, échangent des données avec Google Maps pour créer et optimiser
  des itinéraires de voyage. Ils intègrent également des fonctionnalités de Google Maps dans leurs propres applications
  et sites Web pour présenter des cartes d'itinéraire en temps réel.

Les APIs sont devenues de plus en plus importantes dans l'actualité récente, car **elles sont devenues une partie
essentielle de la connectivité numérique**. Les grandes entreprises de technologie telles que Google, Facebook et Amazon
sont devenues des leaders dans l'utilisation et le développement d'API, avec des produits tels que Google Maps, Facebook
Login et Amazon Web Services (AWS).

Les API existent depuis des décennies, mais leur exposition et leur consommation ont connu une **croissance 
exponentielle**
au cours des dix dernières années environ. Par le passé, les applications étaient verrouillées et la seule intégration
entre elles se faisait via des partenariats prédéterminés. Avec l'essor de l'industrie du logiciel, la demande
d'intégration a également augmenté. Par conséquent, de plus en plus d'applications ont commencé à exposer des éléments
d'elles-mêmes pour que des applications tierces ou des individus puissent les utiliser.

La plupart des API modernes sont conçues dès le départ pour le produit plutôt que d'être une réflexion après coup. Ces
API sont généralement soigneusement testées, tout comme n'importe quel autre composant du produit. Ces API sont fiables
et sont parfois même utilisées par le produit lui-même. Par exemple, l'interface utilisateur d'une application est
de temps en temps construite sur les mêmes API qui sont fournies aux tiers.

La popularité de langages de codage plus simples tels que Python a permis à plus de personnes de construire des
applications et de consommer ces API. Ils obtiennent les résultats souhaités sans avoir à engager des ingénieurs de
développement coûteux.

## Mes expériences

1. Pour le projet interne iTESOFT [Toolkit-Delivery](../../../mes-réalisations/toolkit-delivery), j'ai dû développer une
   API pour connecter l'application à différents services comme l'API Azure et l'API vSphère pour permettre
   d'automatiser l'ensemble de la chaîne de déploiement. Cela a permis de rendre le déploiement de nouvelles plateformes
   plus rapide et plus efficace. Aujourd'hui, cet outil permet de monter une solution complète standard en une
   demi-journée contre deux jours auparavant.
2. Durant ma formation à INTECH, j'ai travaillé sur un 
[projet de développement d'application pour le laboratoire Pythocontrol](../../../mes-réalisations/essentiel).
   Dans le cadre de ce projet, j'ai été chargé de développer une API REST pour permettre à l'application de communiquer
    avec le SI du laboratoire. J'ai également dû développer une API pour permettre à l'application de
    communiquer avec le serveur de base de données pour y stocker les formations créent par les formateurs, 
   enregistrer les progressions des utilisateurs sur leurs formations, etc. Ma bonne maîtrise des APIs m'a permis de
    développer ces APIs rapidement et efficacement.

## Mon niveau d’acquisition de la compétence

J'ai acquis **une solide expérience dans la création et la gestion d'API**, ayant travaillé sur plusieurs projets 
qui ont nécessité l'utilisation d'API. J'ai une connaissance approfondie des différents types d'API, tels que les 
**APIs REST**, les **APIs SOAP** ou encore les **APIs GraphQL**, et des outils et des technologies couramment utilisés 
dans le développement d'API, tels que Postman, Swagger et OpenAPI.

## Conseil

Mon conseil pour les professionnels qui cherchent à maîtriser les APIs est de commencer par comprendre les concepts clés
tels que les méthodes HTTP, les formats de données tels que JSON et XML, les authentifications et les autorisations. Il
est également important de comprendre les bonnes pratiques en matière de sécurité des APIs, telles que l'utilisation de
tokens d'authentification et la limitation des appels d'API par seconde. Enfin, je recommande de s'exercer en créant des
APIs simples pour des projets personnels et de progressivement augmenter la complexité des APIs pour acquérir une
expérience pratique solide.

Pour aller plus loin :

- ["RESTful API Design - Tips and Tricks"](https://betterprogramming.pub/restful-api-design-tips-and-tricks-31a0f71e6d8f){:target="_blank"} de BetterProgramming : Cet article propose des conseils pour la conception d'API RESTful efficaces.
  Il aborde notamment les bonnes pratiques de conception et de documentation, ainsi que les stratégies pour gérer les
  erreurs et les versions de l'API.

## Projets liés

- [Toolkit Delivery](../../../mes-réalisations/toolkit-delivery)
- [WorkBoard](../../../mes-réalisations/workboard)
