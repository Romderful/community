---

# FILENAME : please use your OpenClassrooms's name, available in your url.
# Example: https://openclassrooms.com/membres/celinemartinet
# must be the name of your file. If file name is celinemartinet.md, title is celinemartinet.
# lowercase, no blank space, Capital case or special character.
title: alexandre

# First name or full name
name: Alexandre
date: 2020-01-04 17:20

# One line.
# If you need more space, go to the next line and add 4 spaces on the left, as in 'description'.
objective: Apprendre de nouvelles choses :)
short_description: J'aime les nouvelles technologies et je souhaite appronfondir mes connaissances.

# Ne modifiez pas le paramètre 'template', seulement la description
template: students
description:
    Je m'appelle Alexandre, j'ai 27 ans, et je suis cette formation
    pour appronfondir mes connaissances en informatique.

# image must be located in content/images/students
# name should be the same as this file. Eg: celinemartinet.png
image: alexandre.jpg

# Change this to True when you do you pull request.
public: True

# You need to keep the exact same structure for each new project.
projects:
  - title: Présentez-vous !
    description: Une présentation de moi-même et un lien vers mon LinkedIn.
    # Create a new repository for your images. Name it the same as your nickname and profile picture.
    # Image must be here: content/images/students/yourrepo/project1.png
    image: alexandre/projet_1.png
    link: www.linkedin.com/in/alexandre-prieto-pantoja-735404b6
    # 'true' makes it fully available.
    # 'false' will add a black layer on the picture. IT WILL BE PUBLIC!
    finished: true
  - title: Intégrez la communauté !
    description: Modifier un projet Open Source pour comprendre le fonctionnement de Git, de Github et des PR. 
    image: alexandre/projet_2.png
    link: https://github.com/ppalex
    finished: true
  - title: Aidez MacGyver à sortir !
    description: Création d’un jeu développé en Python et utilisant PyGame.
    image: alexandre/projet_3.png
    link: https://www.github.com
    finished: false
---