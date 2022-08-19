# Methode de travail
Dans un souci de performance et afin de se coller au mieux a la réalité de l’entreprise, nous avons décidé de travailler en méthode AGILE.
En ingénierie logicielle, les pratiques agiles mettent en avant la collaboration entre des équipes auto-organisées et pluridisciplinaires et leurs clients. Elles s'appuient sur l'utilisation d'un cadre méthodologique léger mais suffisant centré sur l'humain et la communication. Elles préconisent une planification adaptative, un développement évolutif, une livraison précoce et une amélioration continue, et elles encouragent des réponses flexibles au changement.
Cette approche a été popularisée à partir de 2001 par le Manifeste pour le développement agile de logiciels Les quatre valeurs et les douze principes adoptés dans ce manifeste sont :
- Les individus et les interactions plus que les processus et les outils

- Des logiciels opérationnels plus qu’une documentation exhaustive

- La collaboration avec les clients plus que la négociation contractuelle

- L’adaptation au changement plus que le suivi d’un plan

Depuis lors, les méthodes ou les approches qui s'inscrivent dans la philosophie de ce manifeste sont appelées « méthodes agiles ».
Les méthodes agiles se veulent plus pragmatiques que les méthodes traditionnelles, impliquent au maximum le demandeur (client) et permettent une grande réactivité à ses demandes. Elles reposent sur un cycle de développement itératif, incrémental et adaptatif.

Ici étant moi-même le client et le concepteur développer nous avons eu une expérience très proche de la réalité
Afin d’être toujours dans la démarche de production nous avons aussi décidé de travailler de manière itérative afin de toujours avoir un produit fonctionnel qui se complexifie et bonifie avec le travail et et le temps

Nous nous somme penche sur la methode SCRUM celle si nous semblais adapte car ayant un temps de developpement plutot cours nous ne pouvions pas nous permettre de developper des features 
inutile ou superflue. Cette methode nous a permis de nous consacrer sur l'essentiel et pouvoirs nous recentrer lors de derrive.
Le SCRUM a pour objectif d'ameliorer la productivite, tout en permettant une optimisation du produit grace a des feddback regulier. Cette methode fonctionne en "Sprint" qui sont des temps 
de developpement qui pour nous dur 1 semaine, au bout d'une semaine on fait le point sur ce qu'on a fait ce qu'on a faire pour la suite ce qui va ce qui va pas pour pouvoir modifier et ameliorer le produit.
je pense que cette methode de travail nous a permit d'avancer bien plus vite que prevue et je la preconiserai meme en travail seul pour eviter "d'avoir la tete dans le guidon" et avoir du recule sur le projet en cours.

# Planification des taches

Dans la creation d'un projet, la planification des taches est l'une des etapes les plus important. Sans une planification exemplaire le projet est voue a partir dans tous les sens et a ne plus respecter les regles de l'agilite.
Celle-ci a pour but de determiner la liste des taches a realiser, a estimer pour chacune d'elle le cout de realisation et les ressource a prevoirs.

- Le decoupage

La toute premiere etape de la planification consiste a effecter un decoupage en phase chronologique. Pour chaque phase, il faut ensuite determiner la liste des tache a accomplire ainsi que les charge a prevoir et les ressources necessaire. Les resultats attendus sont egalement detaille.

- La hierarchisation des taches

Une fois la liste des taches terminee, il faut decider lesquelles seront prioritaire et devront etre realise en premier. il faudra egaleemtn determier les eventuelles interdependances de facon a anticiper les problemes. Si des prerequis sont identifies pour une tache, ils devront etre pris en compte et verront leur niveau de priorite augmenter.

- L'ordonnancement des taches

L'ordonnancement des taches d'un projet consiste a determiner dans quel ordre elles devront etre realisees. Il s'agite egalement a ce stade d'identifier les taches qui devront etre realise sequentiellement et celles qui pourront au contrare etre parallelisees.
Pour cela, il faut se poser les questions suivantes pour chaque tache identifiee :
    - Cette tâche dépend-elle d’une ou plusieurs autres tâches ? Si c’est le cas, ces prérequis peuvent-ils être traités parallèlement ou bien doivent-ils être traités les uns après les autres ?
    - Existe-t-il une marge pour la réalisation de cette tâche ? Un débordement est-il acceptable, et si oui, à combien peut-il se monter sans mettre en danger la suite du projet ?

- Definition de planning

Une fois l'ordonnancement des taches termine, l'ordre dans lequel elles doivent etre realisees en fonction de leur priorite est connu. Le but est maintenant, a partir de la priorite et de la charge estimee des taches, de fixer a chacune des dates de realisation. A la fin de cette etapesle planning du projet permettra de voir les different jalons pour atteindre les objectif et ainsi preparer les Sprint.

Cette planification des taches va nous permettre de degager 4 Epic :

    - Etude préalable : il s’agit de déterminer le périmètre exact du projet (la « gestion du personnel » est une notion très vaste, l’application devra-t-elle comprendre la gestion des        présences, des congés, des absences, de la paie… ?) et de rédiger un cahier des charges.
    - Conception : cette phase correspond à la conception technique de la solution. Des choix qui sont faits à ce stade dépend l’estimation de la durée de réalisation des différentes tâches identifiées.
    - Réalisation : développement de l’application.
    - Tests : tests unitaires, techniques et fonctionnels de l’application.

Ces Epic seront integrer au Jira, chaque Epic se verra attribuer un certain nombre de tickets, tous les tickets doivent etre remplie dans un epic pour pouvoir passer au suivant.

# Choix des technologies

Pour la planification des tache nous somme partie sur Jira qui est le plus complet de tous et qui repondait parfaitement a nos besoin.

pour conceptualiser nous somme partie sur gitmind qui propose des outils adapter a la conception en UML

Dans le but de repondre au mieux au client dans ses choix nous avons du etudier un grand nombre de technologie et faire des choix.
Tout d'abord le site etant une plateforme de e-commerce nous ne pouvions pas delaisser le referencement pour que celui-ci reste competitif contre la concurence, des lors nous avons eliminer React et VueJs car ces framework empeche un bon referencement.
Pour le front nous voulions partir sur NextJS mais au vue du manque de temps nous nous somme avise d'apprendre un nouveau framework. Nous nous somme donc tourne vers la solution du HTML puis pour le back utiliser le templating avec Pug. pour le style nous somme partie sur TailwindCSS qui nous faisait gagner un temps certain grace a l'acces a tailwindUi qui nous propose des blocs de composant de tres bonne qualite comme des boutons, des dropdown menu etc...
pour la partie back nous avons choisis nestJs, qui propose un environnement de travail sains, avec une documentation tres aboutie, et un suivi du framework important ainsi qu'un certain nombre de ressource disponible sur internet qui nous laisse penser que ce framework arrive a maturite contrairement a un framework tel qu'adonnis certe tres performant mais avec tres peu de ressource disponible pour palier a des probleme rencontre.
