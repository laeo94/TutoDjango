#TutoDjango par la création d'une simple application de sondage

Framework web (outils,lib..) permettant la facilité et simplicité de la création d'application web.
Django ici est le framework web de Python le plus populaire utilisant design pattern MVC (Model View Controler)

#Quelque commande utiles

Création d'un projet : django-admin startproject nom-du-projet

Fichiers
    manage.py : utilitaire en ligne de commande (équivalent django-admin) 
    __init__.py : vide indiquant à Python que répertoire = paquet
    settings.py : réglages et config du projet
    urls.py : déclarations des URL (tables des matières du site)
    wsgi.py : entrée pour les serveurs Web afin de déployer le projet

Démarrer serveur Django : py manage.py runserver

Créer application : py manage.py startapp polls

Changement modèles : py manage.py makemigrations polls

Schéma de la BDD :py manage.py sqlmigrate polls 0001

Exécution des migrations pas encore appliquées dans la BDD (synchronisation) : py manage.py migrate

Shell Python : py manage.py shell

Création utilisateur admin: createsuperuser

