# Rattrapage-M1-MIAGE-Technologs
Session Rattrapage M1 MIAGE - Technologs - SUJET C


Consignes générales :
• La durée du partiel est de 2 heures.
• Le rendu doit se faire sur un repository Github, avec l’envoi d’un email avec le lien au
adresse suivantes : didier.courtaud@univ-evry.fr et laurent.breda@univ-evry.fr
• Il y a plusieurs sujets
Ce qui est attendu
• Dépôt du code sur GitHub
• Une organisation de votre travail avec la création d’un board et d’issue (liés au
commits)
• Un readme clair et précis sur les démarches d’installation, et d’utilisation de votre
application
• Un fichier postman avec des jeux de valeurs pour tester votre application
• Du code fonctionnel tournant avec un docker-compose up
Barèmes
• Utilisation de GIT : 5 points
• Rendu Front : 3 points
• Code fonctionnel, commenté et testable : 7points
• Utilisation de dockers : 5 points
M1 MIAGE - 2019
Session rattrapage TechnoLogs
2
DESCRIPTION DU CONTEXTE
Introduction
Bonjour,
Afin de valider votre période d’essai au sein de la web agency Secu@Donf, votre directeur
technique vous demande de réaliser un POC sur les technologies du moment et de démontrer
votre savoir dans l’organisation de votre travail.
Le thème choisi pour ce POC est l’authentification :)
Contexte
Modèle de données :
• Utilisateur = nom / login / mot de passe
• Log de connexion = une date / utilisateur / échec ou non (exemple mauvais mot de
passe)
Architecture souhaitée :
• Un front sur le port 80 permettant l’authentification puis la présentation de tous les
logs de connexion de l’utilisateur en cours
• Un back avec une API Rest exposé sur le port 3000
• Une base de données mongo
Livrables :
• Un répertoire github bien expliqué, avec des commits réguliers
• Un readme d’explication pour le lancement de l’application
• Un docker compose pour lancer le tout
