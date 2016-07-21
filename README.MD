# Mémoire de stage de fin d'études

Ce document est mon mémoire de stage de fin d'études. Les informations suivantes permettent d'installer le compilateur LaTeX sous Linux/UNIX et compiler les sources du document.

## Installation du compilateur

`root@computer:# apt-get install texlive texlive-lang-french`

## Compilation ces sources

*Près-requis :* vérifier et le cas échéant, donner les droits d'exécution à l'utilisateur sur les fichiers clean.sh et make.sh (`root@computer:# chmod a+x *.sh`).

`user@computer:$ ./make.sh`

## Nettoyage des fichiers de compilation

`user@computer:$ ./clean.sh`



