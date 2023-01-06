EXERCICE n°3 :   
Vous allez créer un nouveau projet sur votre dépot git.   
Vous allez appeler votre projet “exercice3”.   
Ci-dessous les étapes à effectuer :   
● En local, vous allez créer un projet que vous allez appeler
exercice3.   
● Dans cet exercice, vous aurez besoin d’utiliser :   
○ git branch “nom de la branche” : pour créer une
branche dans votre projet.   
○ git checkout “nom de la branche” pour vous déplacer
vers une branche.   
● Vous allez créer un fichier texte qui va s’appeler
“fichier_branche_master” et qui va contenir le texte, “bonjour,
je suis le fichier de la branche master”.   
● Vous allez ensuite pousser ce fichier sur votre dépôt distant
sur la branche “master”.   
● Vous allez ensuite créer une branche que vous allez appeler
avec “votre prenom” (avec la commande git branch).   
● Vous allez vous positionner sur cette branche (en utilisant la
commande git checkout “nom de votre branche”).   
● Vous allez créer un nouveau fichier qui va s’appeler
“fichier_branche_votre_prenom”et qui va contenir le texte,
“bonjour, je suis le fichier de la branche votre prenom”.   
● Vous allez ensuite pousser ce fichier sur votre dépot distant
mais sur votre nouvelle branche “votre prenom”.   
A la fin, vous aurez, 2 branches, et chacune de ces branches
devraient contenir un seul et unique fichier.   

git init   
git add .   
git commit -m "Commit 1 Exercice3"   
git remote add origin https://github.com/VincentLip/Exercice3.git...   
git branch Vincent   
git log   
git branch   
git checkout Vincent   
git push -u origin Vincent   
