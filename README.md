This project is now mine !
# TP2 : Github Action
## Question 2.1
Les Testcontainers sont une librairies java qui permettent de lancer des contenaeurs Docker éphémères lors des tests d'intégration. Les testcontainers fournissent des images afin de simuler des bases de doonées, navigateurs, etc. , pour simuler un environnement de test réaliste.
## Question 2.2
L'utilisation de variables sécurisées sur Github à pour but de cacher la visibilité d'informations compromettantes/sensibles, comme les clefs API et autre token, afin d'éviter que tout le monde puisse les voir. 
## Question 2.3
Le mot clef `needs` permet de lier et de définir une dépendance entre deux tâches. Dans notre cas, on indique ici que la tâche `build-and-push-docker-image`ne doit s'éxécuter que si les tests du backent réussissent avant. En effet, sans `needs`, l'image Docker pourrait être construite même en cas d'échec des tests.
## Question 2.4
Pousser les images sur Docker Hub permet de les partager et de les déployer plus facilement. Cela permet ainsi à des environnements différents de récupéper facilement la même version de l'application pour garantir sa reprocductibilité.
# TP3 : Ansible
