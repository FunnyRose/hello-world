# hello-world

Comment initialiser un dépôt git local qui contient au moins un commit ?

En premier on doit créer un fichier README :
A partir de la command line il faut faire : 
  mkdir ~Hello-World => dans notre répertoire utilisateur local
  cd ~Hello-World => Pour rentrer dans ce répertoire
  git init : installer les fichiers Git dans /Users/you/Hello-World/.git/

Ensuite créer un fichier :
  touch README.md
  
Ensuite créer un commit :
  git add README.md => l'ajoute sur la liste des fichiers à committer
  git commit -m 'Wild Code School' => créer un commit avec le message suivant "Wild Code School"

Pousser le commit :
  git remote add origin : https://github.com/thoughtbot/gitsh (lien vers un dépôt intéressant et utile pour l'utilisation de Git et de la CLI (Command Line Interface)
  git push origin master => envoie le commit vers la branche "master" sur Github


ET VOILA ! Le tour est joué !
