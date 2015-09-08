# Git-Github
##Principales commandes de Git-Githup
###$ git init
Initialise un nouveau dépôt Git. Jusqu’à ce que vous exécutiez cette commande dans un dépôt ou répertoire, c’est simplement un répertoire normal. Seulement après avoir entré cette commande, il accepte les commandes Git qui suivent.

###$ git config
ceci est tout particulièrement utile quand on paramètre Git pour la première fois.
  
###$ git status
Vérifie le statut du repository. Voir quels fichiers sont à l’intérieur, quels sont les changements ayant besoin d’être gardés en mémoire, et sur quelle branche du repository vous êtes en train de travailler.

###$ git add
Ceci n’ajoute pas de nouveaux fichiers dans votre dépôt. Au lieu de cela, cela porte de nouveaux fichiers à l’attention de Git. Après que vous ayez ajouté des fichiers, ils sont inclus dans les “instantanés” du dépôt Git.

###$ git commit
la commande la plus importante de Git. Après avoir fait toute sorte de modification, vous saisissez ça afin de prendre un “instantané” du dépôt. Généralement cela s’écrit sous la forme git commit -m “Message ici“. Le -m indique que la section suivante de la commande devrait être lue comme un message.

###$ git branch
Cette commande nous permet de construire une nouvelle branche, ou une timeline de commits, de modifications et d’ajouts de fichiers qui sont complètement les nôtres. Notre titre va après la commande.

###$ git checkout
Permet littéralement de rapatrier un dépôt dans lequel vous n’êtes pas.

###$ git merge
Quand nous avons terminé de travailler sur une branche, nous pouvons fusionner nos modifications vers la branche master, qui est visible pour tous les collaborateurs.

###$ git push
Si vous travaillez sur votre ordinateur local, et voulez que vos commits soient visibles aussi sur Github, vous “push”ez les modifications vers Github avec cette commande.

###$ git pull
Si vous travaillez sur votre ordinateur local, et que vous voulez la version la plus à jour de votre repository pour travailler dessus, vous “pull”ez (tirez) les modifications provenant de Github avec cette commande.