# Missions

Au cours de ma formation j'ai été amenée à travailler sur des petites tâches ponctuelles, principalement le développement d'application Android. Ces applications avaient pour but de montrer différents usages de la technologie NFC.
En deuxième année mes tâches ont progressivement évolué vers le projet européen MOOCTab qui occupe maintenant la plus grande partie de mon temps.

## MOOCTab

MOOCTab est un projet européen qui réunit la Turquie et la France. Le but de ce projet est de proposer une solution permettant de consulter des MOOCs en ligne de manière sécurisée sur des tablettes. En outre la solution doit permettre de pouvoir passer des examens. Pour se faire l'ensemble de la tablette doit être sécurisé, de plus l'identité de l'étudiant doit pouvoir être vérifiée.

La solution comprend une MOOCBox qui permet aux utilisateurs de s'authentifier avec leurs badges et d'avoir accès au contenu qu'elle diffuse dans la salle de cours.
La MOOCBox est composée de deux éléments distincts, un serveur local à la salle de cours et un module NFC permettant la partie authentification.

Le module NFC de la box possède un élément sécurisé, cet élément sécurisé permettra de stocker les données d'identification des étudiants. Ce module pourra lire les badges, les écrire et partager des informations avec l'autre partie de la box. C'est cette partie-là que NXP a la responsabilité de réaliser.

Notre partie de la box est composée d'une petite carte tournant sous Android à laquelle nous avons rattaché une puce NFC avec une antenne. Mon rôle a été de réaliser la liaison entre la carte et la puce NFC, autant au niveau matériel que logiciel.

Dans un premier temps il m'a été demandé de réaliser plusieurs démonstrations sous Android.
La première permettait d'accéder à un bracelet connecté qui agissait comme une carte étudiant. Il fallait pouvoir lire et écrire des informations dessus. Cette démonstration a été présentée à l'occasion d'un salon auquel NXP participait. Afin de réaliser cette démonstration il m'a fallu apprendre comment fonctionnait une carte d'identification et comment elle était créée. Il a aussi fallu que j'apprenne à accéder au contenu du braclet pour le lire et le modifier. J'ai ainsi découvert les avantages et les limitations du système.
La seconde venait compléter cette démonstration, il fallait pouvoir démontrer qu'il était possible d'acccéder à l'élément sécurisé du lecteur (l'appareil Android) afin de traiter les informations qu'envoyait la carte (le braclet). Afin que cette démonstration puisse voir le jour nous avions à dispositions des smartphones de référence qui servent de testeurs. Ayant un accès complet à ces smartphones avec les clés permettant d'accéder à l'élément sécurisé nous avons pu y installer une petite application nommée loopback. Cette petit application permettait entre autre de renvoyer, sous forme inversée, les données que nous lui envoyons. Par exemple nous aabbcc était envoyé et en retour ccbbaa était retourné.

Ces deux démonstrations ont été l'occasion pour moi d'apprendre à utiliser différentes manières pour manipuler la NFC sous Android.

C'est pour moi une expérience inédite n'ayant jamais réalisé ce genre de tâches auparavant.

## NFC Playbook

Il arrive que l'entreprise ait des besoins ponctuelles de produire des démonstrations ou des modèles pour promouvoir l'utilisation de la NFC et notamment dans les applications mobiles.
Récemment un collègue d'un autre service est venu solliciter mes compétences en la matière afin de développer un petit squelette de code pouvant être réutilisé.

Le but était de produire une petite application Android permettant d'héberger des mini-applications qui utiliseraient la NFC. Il fallait avoir la possibilité de lancer les mini-applications, soit en cliquant dessus, soit en utilisant un tag NFC.

Cette application sera utilisée lors d'un évènement du Dôme qui aura lieu les 16 et 17 Février 2018. C'est un atelier qui se fera sur une journée et sera centré sur le thème du livre et des intéractions numériques. Les développeurs et artistes de chaque équipe devront fabriquer des prototypes de livres améliorés grâce à l'outil numérique.

Cette mission m'a permis de faire une coupure par rapport au MOOCTab, tout en aidant un collègue. De plus ma contribution a permis d'éviter le recours à un prestataire et a donc induit des économies non négligeables.
