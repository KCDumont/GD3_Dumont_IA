# GD3_Dumont_IA
 Demande du client Romain Domingues

 Contexte
Le joueur incarne Brave Pitre, un jeune humain capturé par des Orcs, qui prévoit d'utiliser ses os pour les transformer en une épice rare et précieuse. Le roi des Orcs a réservé Brave Pitre comme dessert spécial. Cependant, ce dernier ne se laisse pas faire : après s’être échappé de sa cellule, il doit trouver un moyen de fuir le village des Orcs. L’un des principaux obstacles à cette évasion réside dans les mages orcs qui patrouillent et surveillent la prison.
________________________________________
Objectifs pour le développeur :
 Le but est de concevoir une IA pour les patrouilles des Orcs. Voici les éléments fonctionnels à mettre en place :
  1.	Patrouilles avec parcours prédéfinis :
       -	Chaque unité orc doit suivre un itinéraire précis autour de la prison.
       -	Ces parcours doivent être paramétrables, permettant des ajustements ou des variations si nécessaire.
 
  2.	Zone de détection et champ de vision :
       -	Chaque Orc doit disposer d’une zone de détection pour repérer le joueur.
       -	Cette zone doit être directionnelle, simulant un champ de vision réaliste.
       -	Si le joueur entre dans cette zone, cela déclenche une réaction (voir point suivant).
 
  3.	Réaction en cas de détection :
       -	Lorsqu’un Orc repère le joueur :
          -	Il doit attaquer en lançant des projectiles magiques.
          -	Ces projectiles doivent permettre au joueur de les esquiver, ajoutant une couche de défi.
 
  4.	Comportement secondaire conditionnel :
       -	Les Orcs doivent avoir une action secondaire qui s’active sous certaines conditions pour perturber leur routine de patrouille.
       -	Une piste proposée (modifiable si une mécanique plus intéressante est trouvée) :
          -	Lorsqu’un Orc atteint un point de patrouille, il peut utiliser un sort aléatoire parmi les options suivantes :
          -	Invisibilité : L’unité devient temporairement invisible.
          -	Inversion de position : L’Orc échange sa place avec un autre Orc.
          -	Téléportation : L’unité se déplace de façon imprévisible sur la carte.
          -	Ces actions aléatoires doivent progressivement compliquer la tentative d’évasion du joueur.
________________________________________
Remarques importantes
•	Ces mécaniques doivent être pensées pour équilibrer le défi du joueur tout en garantissant que le gameplay reste fluide et cohérent.
•	N’hésitez pas à expérimenter ou ajuster certaines idées pour obtenir un gameplay engageant et dynamique.

