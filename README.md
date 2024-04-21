# Blog Project

### Description
Ce projet est un blog dynamique développé en utilisant le framework Django. Le backend est entièrement géré par Django, offrant une plateforme robuste et flexible pour la création et la gestion des articles de blog.

### Installation et Configuration
#### Prérequis
- Python 3.x
- Django 2.x ou supérieur

#### Installation
1. Clonez le dépôt : 
```
git clone https://github.com/debad1/blog_project.git
```
2. Accédez au dossier du projet : 
```
cd blog_project
```
3. Créer un environnemnt installer les dépendances : 

```
pip install -r requirements.txt
```

#### Activer l'environnement virtuel
```
source bin/activate
```
- Effectuez les migrations : 
```
python manage.py migrate
```

### Utilisation
Pour lancer le serveur de développement :
```
python manage.py runserver
```
Accédez à 
```
http://localhost:8000
```
 dans votre navigateur pour voir le blog en action.

### Fonctionnalités
- Création, édition, et suppression d'articles de blog
- Interface d'administration Django pour la gestion des articles

