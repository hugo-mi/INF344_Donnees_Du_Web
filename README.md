# INF344_Donnees_Du_Web : Projet Mul

## Projet : Tous les chemins mènent à la philosophie

Développement d'une application Web pour jouer à un jeu simple : en partant d'un article Wikipédia, atteindre l'article \Philosophie" en suivant les liens d'un article à l'autre, 
et en aussi peu d'étapes que possible.
L'application du TP permet de jouer à ce jeu en récupérant les pages de Wikipédia et en proposant les liens à l'utilisateur.
Le projet utilise le langage de programmation **Python** et le framework **Web Flask**.

L'application Web affichera à l'utilisateur, lorsqu'il arrive sur un article de Wikipédia, la liste des 10 premiers liens de la page où il est arrivé. 
Cette information sera obtenue en interrogeant l'API de Wikipdia. Spécifiquement, nous allons éditer le fichier getpage.py et y programmer deux fonctions :

• Une fonction ``getRawPage()`` qui prend en argument un titre de page page, et renvoie un couple formé de deux
  éléments : le nom de la page page aprés résolution des redirections, et le contenu HTML de la page. (La "réesolution des redirections", signifie que le titre de la page "Philosophique" doit être "Philosophie" et non
  "Philosophique", parce qu'elle redirige vers "Philosophie".)
  
• Une fonction ``getPage()`` qui prend en argument un titre de page page, et renvoie un couple formé de deux éléments : le nom de la page page aprés résolution des redirections comme ci-dessus, et la liste des titres de page des 10
premiers liens de page (sans résolution des redirections pour ces titres).
