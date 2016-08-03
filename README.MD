# Mémoire de stage de fin d'études

__Edit : ~~Important : toujours nettoyer les répertoires avant de commiter et de pousser les sources.~~ se fait automatiquement avec les nouveaux scripts sur Windaube, vous pouvez vous boire une bière avec le temps de gagné.__

Ce document est mon mémoire de stage de fin d'études. Les informations suivantes permettent d'installer le compilateur LaTeX sous Linux/UNIX et compiler les sources du document.

## Installation du compilateur

Sous Linux/Unix, lancer la commande (un mise à jour des dépôts n'est pas de trop avant cette action) :

`root@computer:# apt-get install texlive texlive-lang-french`

Sous Windows, télécharger MikTeX sur le site officie (pour être sûr d'avoir la dernière version, et pas une version avec backdoor intégrée...) : [MiKTeX - Download page](http://miktex.org/download).
Puis double-cliquer sur l'installeur téléchargé, et suivre les instructions, dans le doute, toujours dire oui (pas comme avec votre femme/mari, bande de lapins).

## Compilation ces sources

__Note : bien sûr il faut être dans le répertoire où se situent les sources, c'est pas de la magie !__

Sous Linux/UNIX :

__Près-requis :__ vérifier et le cas échéant, donner les droits d'exécution à l'utilisateur sur les fichiers clean.sh et make.sh (`root@computer:# chmod a+x *.sh`).

`user@computer:$ ./make.sh`

Sous Windows :

`C:\Mon_chemin_windowbe> make.bat`

## Nettoyage des fichiers de compilation

Sous Linux/UNIX :

`user@computer:$ ./clean.sh`

Sous Windowbe :

`C:\Mon_chemin_windowbe> clean.bat`

_Note de l'auteur : c'est cadeau, profitez-en ! Merci au [BlogHiko](http://blog.hikoweb.net/index.php?post/2011/11/06/Exemple-de-rapport-en-LaTeX) pour les sources originales pour Linux._