## Analyse des besoins
---
# Besoin fonctionnel


 Keystoms est une plateforme de e-commerce, le site devra offrir au client la possibilite d'acheter des pieces detache de clavier d'ordinateur de tout type (case, PCB, plate, switch, keycaps, accessoire en tout genre). Cepandant ce n'est pas tout, celui-ci devra aussi proposer un systeme de "configurator", le client pourra selectionner les differents type de pieces d'un clavier afin d'en "construire" virtuellement un. Une fois celui-ci construit il pourra se le commander et il recevra le meme en "plug and play", c'est a dire qu'il sera pret a l'emploi. En plus de ces deux fonctionnalite le client aurra acces a une panel de possibilite, comme acceder a different guide ou bien pouvoir me contacter afin de resoudre des probleme de service apres-vente etc...





# Preconnisation technique

Apres avoir annalyse les besoins du client, je preconise donc d'utiliser du JavaScript, celui-ci nous permettra de traiter du front, de faire une API.
Pour creer cette API nous allons utiliser NestJS qui est un environnement de travaille securise, ainsi que pug pour travailler en templating a travers nestJS, nous aurrions pu travailler avec un framework front-end tel que ReactJs ou VueJS mais ayant besoin de referencement pour rester competitif envers la concurrence nous nous sommes decide de ne pas utiliser ces framework.
Pour travailler au mieux en equipe nous utiliserons le systeme de versionning git et son workflow Gitflow en travaillant en systeme de feature.
Cepandant nous avons fait un grand nombre de commit sans jamais respecter de template d'appelation, a l'avenir je souhaite utiliser un template angular pour organiser au mieux mes differents commits