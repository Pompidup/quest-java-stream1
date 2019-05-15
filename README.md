# quest-java-stream1

Challenge
Fichage des héros

Après des années à postuler, tu as enfin été embauché au S.H.I.E.L.D ! Malheureusement, ton premier boulot consiste à aider le président du CE (Comité d'Entreprise) pour des tâches ingrates. Peu importe, c'est pour le bien de la Terre, alors tu t'exécutes !

Le président te fournit une liste de héros, et te donne les tâches suivantes :

    le CE a négocié un avantage avec Tony Stark pour réaliser des cartes seniors : -30% sur des pantoufles en vibranium. Ta première mission consiste à trouver la liste des héros de 60 ans et plus !
    le goûter d'anniversaire de Thor sera organisé la semaine prochaine : afin d'éviter les drames, ta seconde mission est de trouver la liste des héros intolérants au gluten !

Pour démarrer, fais un Fork du dépôt suivant puis clone-le en local.

    Pense bien à faire un Fork, sinon tu ne pourras rien pousser !

    Ouvre les classes Hero et Shield afin d'en étudier leurs contenus respectifs.
    Dans Shield.java, utilise un Stream et la méthode filter pour récupérer dans elders la liste des héros de 60 ans et plus
    Dans Shield.java, utilise un Stream et la méthode filter pour récupérer dans intolerants la liste des héros intolérants au gluten
    Dans les deux cas précédents, utilise un Predicate et des lambdas
    Tu ne dois pas modifier la classe Hero !
    Compile et exécute le code, afin de vérifier que les deux listes s'affichent bien dans le terminal

Résultat attendu lors de l'exécution de Shield :

$ Elders:
$ Captain America
$ Thor

$ Gluten intolerants:
$ Vision
$ Scarlet Witch
$ Hulk

Critères de validation

    Le dépôt GitHub contient bien les fichiers Hero.java et Shield.java. Seul Shield.java doit avoir été modifié.
    La classe Shield contient bien un Stream qui récupère la liste des héros de 60 ans et plus, en utilisant la méthode filter et un Predicate
    La classe Shield contient bien un Stream qui récupère la liste des héros intolérants au gluten, en utilisant la méthode filter et un Predicate
    La classe Shield se compile sans erreur et affiche dans le terminal le même résultat que celui présenté précédemment

