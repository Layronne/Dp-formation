## Back-end
---

# Securite

Les fuites de données les plus importantes sont dues à des API défaillantes, vulnérables ou piratées, car celles-ci peuvent révéler au grand public des données financières et personnelles sensibles. Cependant, toutes les données ne se valent pas et ne nécessitent pas le même niveau de protection. Il est donc d’ordre public que notre stratégie de sécurisation des API doit dépendre du type de données transférées.
Afin de protéger au mieux nos APIs, nous avons besoin d’un environnement fiable qui applique des politiques d’authentification et d’autorisation.
Nous utiliserons donc plusieur méthodes:


* Utilisation des tokens : nous attribuons des jetons utilisateur afin d'accéder au services, sans ce jeton l’utilisateur n’a pas accès. Ce jeton a un temps d’expiration.


* Utilisation du chiffrement et signatures : nous allons chiffrer nos données à l'aide d’un protocole. Seuls les utilisateurs autorisés peuvent déchiffrer et modifier lesdites données.


* Un typage très strict des donnés : se typage strict nous permettra de ne jamais avoir de mauvaise surprise lorsqu’on attend une certaine donnee.
Lorsqu'un utilisateur veut accéder à un système, celui-ci doit dans un premier temps effectuer une procédure d’identification et d'authentification.
L’identification est une phase qui consiste à établir l’identité de l’utilisateur. L’utilisateur utilise un identifiant qui l’identifie et qui lui est attribué individuellement. Cet identifiant est unique.
L’authentification est une phase qui permet à l’utilisateur d’apporter la preuve de son identité. Elle intervient après la phase d’identification. L’utilisateur utilise un authentifiant qui est le password et connue que par lui.
Pour que ce mot de passe ne soit pas découvert ou bien même déduit, nous mettons en place une politique de sécurité pour obliger l’utilisateur à avoir un mot de passe peu facile à trouver.
Une politique de mot de passe consiste en une série de mesures mises en place par une entreprise pour renforcer la sécurité de l’accès aux données et aux outils dont elle dispose, à travers la création et l’utilisation de mots de passe complexes. Elle doit être adaptée en fonction du contexte et des objectifs de sécurité du système d’information de l’organisation.
Bien organiser et cadrer l’authentification des utilisateurs représente un facteur essentiel pour garantir la sécurité des traitements des données personnelles, dans le cadre de l’application des articles 5 et 32 du RGPD, comme le rappelle l’agence nationale de la sécurité des systèmes d’information (ANSSI) dans son guide de recommandations relatives à l’authentification multifacteur et aux mots de passe.
Si l’efficacité d’un mot de passe est souvent réduite à sa « force », une politique efficace en la matière doit définir une série d’éléments indispensables, tels que :
* La longueur des mots de passe,
* La complexité des mots de passe,
* Le délai d’expiration des mots de passe,
* Les mécanismes de contrôle de leur robustesse et la limitation d’essais d’authentification,
* La méthode de conservation des mots de passe et la gestion de l’historique des événements liés à l’authentification,
* La règle pour retrouver ses accès en cas de perte ou de vol de mot de passe,
* L’utilisation d’un coffre-fort de mots de passe.

# API

Conception 

La conception de l'API c'est fait en plusieurs etapes. Tout d'abord nous avons choisis de faire toute notre conception en UML qui est le langage de conception le plus utilise. Cepandant d'autre alternative existe comme le C4 Model ou bien le DoDAF. Grace a ceux langage nous avons voulu conceptualise la meilleurs API possible et pour ce faire nous avons choisis 3 type diagramme a realiser :
    - le Diagramme d'utilisation
    - le Diagramme de classe
    - le diagramme de sequence
Cest trois digrammes couvre l'ensemble de nos besoin lors de la conception de l'API, neanmoins il existe un grand nombre de diagramme realisable mais ceux-ci etaient beaucoups moins pertinant pour notre projet.  


# Base de donnee

La sécurisation de la base de données est un des éléments les plus essentiels de notre stratégie de sécurité, c’est elle qui contient l’ensemble des données sensibles que nous ne voulons pas divulguer. Notre stratégie se basera donc en 4 grand point :
* Contrôles d'administration et d'accès au réseau : Le nombre d'utilisateurs ayant accès à la base de données doit être limité au minimum pratique. Leurs droits doivent être limités au strict minimum nécessaire leur permettant d'effectuer leur mission. De même, l'accès au réseau doit être limité au niveau minimum d'autorisations nécessaires.


* Sécurité des comptes/des appareils des utilisateurs finaux : Nous devons toujours savoir qui accède à la base de données, et quand et comment les données sont utilisées. Les solutions de surveillance des données peuvent nous avertir si certaines activités sur les données sont inhabituelles ou semblent risquées. Tous les appareils utilisateur qui se connectent au réseau hébergeant la base de données doivent être sécurisés physiquement (c'est-à-dire être détenus uniquement par l'utilisateur autorisé) et pouvoir être soumis à des contrôles de sécurité à tout moment.


* Chiffrement : TOUTES les données, y compris les données de la base de données et les données d'identification, doivent être protégées par un chiffrement optimal, qu'elles soient au repos ou en transit. Nous gererons toutes les clés de chiffrement avec les meilleures pratiques possibles (HASHAGE, SALAGE).


* Sécurité des sauvegardes : Toutes les sauvegardes, copies ou images de la base de données doivent être soumises aux mêmes contrôles de sécurité (ou à des contrôles équivalents en termes de rigueur) que la base de données elle-même.
Même avec les plus grande précautions possible la plus grande menace reste l’erreur Humaine, Les accidents, les mots de passe faibles, le partage de mots de passe et d'autres comportements imprudents ou résultant d'une mauvaise information continuent d'être la cause de près de la moitié de toutes les violations de données déclarées.