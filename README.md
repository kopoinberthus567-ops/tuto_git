# Documentation du tuto github

## Initialiser un depot

'''bash
git init
git remote add origin SSH_REPO
'''

## Rediger un commit

'''
Titre du commit

Description de notre commit avec des information sur l'évolution du projet
''' 

## Envoyer un commit sur le dépot distant

'''bash
git add .
git commit -m "Un commentaire"
git push origin master
'''

## Création d'une branche

'''bash
git checkout -b Nom_de_Branche 
'''

Pour les bonnes pratiques, on va intégrer la notion de revue de code.
