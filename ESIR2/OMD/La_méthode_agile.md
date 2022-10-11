# La méthode agile
CM OMD 11/10/2022 

## Résumé du cours précédent

### I. Premières SDLC 
Les premières SDLC visent à découper un projet en étapes successives, ce qui permet d'échelonner l'avancement. 

Mais elles ne prennent pas en compte les changements qui peuvent survenir au cours du développement du projet.

### II. SDLC itérative

Pour les SDLC itératives (modèle Spiral, modèle prototypage), on démarre avec une première esquisse du projet complet, puis on l'améliore au fur et à mesure des versions.

On y utilise un principe clé : "la rétroaction", c'est apprendre en développant : apprendre en utilisant le produit de l'utilisation précédente. Il a été vu, qu'il n'est pas possible de spécifier un bon produit. N'étant pas possible de tout prévoir, il faut donc s'adapter au fur et à mesure.

C'est une amélioration des pratiques, mais pas encore jusqu'au niveau agile.

# Méthode Agile

| Principe du management         | Caractéristiques                                          |
| :----------------------------- | :-------------------------------------------------------- |
| Amélioration continue          | Le client est au cœur du processus                        |
| Respect des personnes          | Le produit est construit en dialogue avec le client       |
| Remettre en cause chaque chose | Plus de pouvoir est donné à l'équipe de développement     |
| Adopter le changement          | Le client est impliqué dans le processus de développement |

## Construire un produit de façon agile

| Pas agile                                             | Agile                                                                           |
| :---------------------------------------------------- | :------------------------------------------------------------------------------ |
| une chaine de hiérarchie classique                    | retour de la part des développeurs                                              |
| Pas d'interaction entre le client et les développeurs | De la liberté de développement pour les développeurs (choix des technos etc...) |

# SCRUM

## Définition

- Processus de la méthode agile où l'on fabrique le meilleur produit en temps réduit : de 2 à 4 semaines
- Création d'un produit à chaque période appelé sprint""
- Le client donne ses priorités et l'équipe s'organise pour réaliser les plus prioritaires
- À la fin de chaque sprint, le produit est livré au client et tout le monde peut voir ce qui a été fait

<p align=center>
    <img src="https://i.imgur.com/8MpaN52.jpg" alt="SCRUM diagram" width="400"/>
</p>


SCRUM permet d'organiser le développement, mais ne spécifie pas comment le faire, les méthodes d'ingénierie restent libre.

## Termes

**"BACKLOG"** : Ensemble des **user stories** à réaliser

**"USER STORY"** : Description d'une fonctionnalité avec son contexte et du sens. Rédigée sous forme de série de phrases rédigées dans un langage simple et compréhensible par tous. Elles ne contiennent pas de détails techniques et permettent une meilleure compréhension du besoin par les développeurs.

## Fixer le cadre des développements

### I. Sprint 0
Le Sprint 0 est le premier sprint du projet, où l'on :
- Définit les bases du produit, mode de travail, objectifs, attentes, etc...
- On fixe le cadre du projet, ses contraintes, priorités, etc...
- Clarifie les communications : 
  - Le modèle d'analyse
  - Le dictionnaire commun
  - Les notions communes
  - Le modèle du problème
  - Les utilisateurs
  - Les actions 
  - etc...
- Valide les points techniques difficiles
- Montre une première version du produit qui démontre que le projet est réalisable
- Faire une mini estimation du backlog du produit

### II. Les autres sprints
Les autres sprints sont des sprints de développement, où l'on :
- Fabrique un produit plus complet que le précédent
- On fabrique toujours un produit utilisable par le client
- On implémente toujours des fonctionnalités issues de user stories

On fabrique pour cela une revue de planification du sprint, où en fonction du backlog et de la capacité de l'équipe à produire durant le sprint, on va :
- Définir les user stories à réaliser
- Définir les tâches à réaliser pour chaque user story

### III. Réunion quotidienne

Dans les réunions quotidiennes, on regarde grâce à des outils de suivi des taches l'avancement du projet et l'on rerépartit les tâches à faire entre les acteurs du projet. Suite à chaque réunion, on remet à niveau le backlog.

### IV. Analyses de fin de sprint

Après chaque sprint, on fait 2 analyses : 
- Une Revue de sprint sur l'avancement du projet
- Une "Sprint rétrospective" sur le déroulement du projet
  
| Revue de sprint       | Sprint review / Sprint rétrospective            |
| :-------------------- | :---------------------------------------------- |
| Valider l'avancement  | Identifier les bonnes pratiques                 |
| Analyser le résultat  | Identifier les points à améliorer / abandonner  |
| Définir les priorités | Choisir 1/2 résolutions pour le prochain sprint |

### V. Définir et estimer une tache
Un des grands point de la méthode agile est la définition et l'estimation de taches, pour chacune d'entre elles, on doit :
- Chercher un ordre de grandeur de la tache
- Définir un critère de fin

# Jeu des lancés de balles
En fin de CM, nous avons fait un jeu/exercice démontrant l'efficacité de la méthode agile.
| Règles                                            | Matériel                 |
| :------------------------------------------------ | :----------------------- |
| Découpage en 3 équipes                            | $+\infty$ Balles simples |
| 1 équipe en mode classique                        | 4 Balles à 2 points      |
| 2 équipes en mode agile                           | 1 Avion à 10 points      |
| Agile: 5 itérations avec 30s de rétrospective     |                          |
| Classique: Gros temps de réflexion et 1 tentative |                          |
## Résultats

| Catégorie  | Agile Au départ | Agile Au final    | Classique                |
| :--------- | :-------------- | :---------------- | :----------------------- |
| Estimation | Trop faible     | La Meilleure      | Loin de la réalité       |
| Erreurs    | Beaucoup        | Le Meilleur ratio | De débutant              |
| technique  | Basique         | La Meilleure      | Évoluée, mais pas adaptée|

## Conclusion

L'équipe classique qui a pris le temps de réfléchir à fait beaucoup mieux que la première itération agile. Mais, l'équipe classique n'a pas su prévoir les réalités du terrain. Ainsi l'équipe agile a fait beaucoup mieux que l'équipe classique sur le même temps, en ayant su adapter sa technique et en corrigeant à chaque fois les erreurs humaines. 
