# Des jeux sérieux pour enseigner l'élevage de précision - Panique à la ferme 

Vous connaissez le concept de l’escape game et du serious game ? le logiciel R ? Nous avons fusionné les trois en un pour enseigner l’élevage de précision et R à des étudiants de niveau BTS à Ingénieur/Master 2 au travers de 2 escape game pédagogiques intitulés « R’Scape the office » et « Panique à la ferme ».
Combinant à la fois le côté éducatif d’un Serious Game et ludique de l’Escape Game, deux « Serious Escape Game » (SEG), intitulés « Rscape the Office » et « Panique à la ferme » viennent d’être réalisés.

Financés par l’Institut de Convergence #DigitAg avec l’appui de l’Institut de l’Elevage, INRAE et l’Institut Agro, ils permettent l’acquisition de connaissances et compétences sur l’élevage de précision, le fonctionnement et l’analyse de données issues d’accéléromètre ou d’imagerie 3D, grâce à une interface développée sous le logiciel R.

Il existe 2 jeux : « R’scape the office » et « Panique à la ferme ». Ils sont sous la forme de package R. Ces packages doivent être installer. Lors de leurs installations tous les packages que les jeux nécessitent sont installés automatiquement.

# Installation du jeu Panique à la ferme  

1. Télécharger le package lié à "Panique à la ferme"  ici : https://drive.google.com/drive/folders/1kBa131q2p46rpwxUfGLaYlDyEhgZiFdl?usp=drive_link  
        Enregistrer le fichier .tar dans un répertoire dédié créé pour l'occasion nommé "Jeu sérieux".    
        **Ne pas le décompresser/dézipper**  


2.	Installez R, version 4.3.2 :  https://cran.r-project.org/bin/windows/base/old/4.3.2/  
3.	Installez Rstudio si vous ne l’avez pas : https://posit.co/download/rstudio-desktop/  
 
Pour installer un jeu il suffit de faire tourner un court script qui va installer le package R qui contient le jeu.   

3. Créez un projet R dans le répertoire "jeu sérieux" pour fixer la source du chemin dans le répertoire "jeu sérieux"  
           Dans R studio : File / New project / Existing Directory / Choisir ici le répertoire "jeu sérieux"  
5. Téléchargez le script d’installation "Installation_PANIQUE.Rmd" à disposition dans ce dépot GIT un peu plus haut, dans le répertoire dédié au jeu que vous venez de créer.
6. Ouvrez le script d’installation
7. Suivez les instructions du script d’installation  
   Important lors du lancement du script d’installation, si :  
            •	R souhaite relancer une nouvelle session, cliquez sur « oui » la première fois uniquement  
            •	Si R souhaite installer des packages depuis la « source », cliquez toujours sur « non ».  

   
# Lancement du jeu Panique à la ferme

1. Télécharger le script "lancement_PANIQUE.Rmd" depuis ce dépot GIT vers le répertoire dédié.   
2. Ouvrir le script lancement des jeux et faites tourner toutes les lignes de la cellule correspondant au jeu que vous souhaitez lancer.

# Un problème ? 

Utiliser la fonction pull request (en haut) offerte pas github ou écrivez moi à adrien.lebreton@idele.fr  

