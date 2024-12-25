# Django Quiz Application

Une application web de quiz interactive construite avec Django.

## Fonctionnalités

- Quiz interactif avec questions à choix multiples
- Système de score
- Interface administrateur pour gérer les questions
- Authentification des utilisateurs
- Suivi des résultats

## Installation

1. Clonez le dépôt :
```bash
git clonehttps://github.com/mzerroug/Python_Quiz.git
cd Python_Quiz
```

2. Créez un environnement virtuel :
```bash
python -m venv venv
```

3. Activez l'environnement virtuel :
- Windows :
```bash
venv\Scripts\activate
```
- macOS/Linux :
```bash
source venv/bin/activate
```

4. Installez les dépendances :
```bash
pip install -r requirements.txt
```

5. Effectuez les migrations :
```bash
python manage.py makemigrations
python manage.py migrate
```

6. Créez un superutilisateur :
```bash
python manage.py createsuperuser
```

## Utilisation

1. Lancez le serveur :
```bash
python manage.py runserver
```

2. Accédez à l'application :
- Application : http://127.0.0.1:8000/
- Administration : http://127.0.0.1:8000/admin

## Administration

Pour ajouter ou modifier des questions :
1. Connectez-vous à l'interface d'administration
2. Naviguez vers la section Questions
3. Utilisez le formulaire pour ajouter/modifier les questions et réponses

## Structure du Projet

```
quiz_project/
├── quiz/                   # Application principale
│   ├── migrations/        # Migrations de base de données
│   ├── templates/        # Templates HTML
│   ├── static/          # Fichiers statiques
│   ├── admin.py        # Configuration admin
│   ├── models.py       # Modèles de données
│   ├── views.py        # Vues
│   └── urls.py         # URLs de l'application
├── static/              # Fichiers statiques globaux
├── templates/           # Templates globaux
└── manage.py           # Script de gestion Django
```

## Technologies Utilisées
- Django
- Python
- HTML/CSS
- Bootstrap
- JavaScript
- SQLite

