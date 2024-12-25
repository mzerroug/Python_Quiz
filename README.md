
**1. Cloner le projet:** 
  git clone https://github.com/mzerroug/Python_Quiz.git
  cd Python_Quiz
**2. Créer un environnement virtuel :**
  python -m venv venv
**3.Activer l'environnement virtuel :**
 - Sur Windows :
    bashCopyvenv\Scripts\activate
 - Sur macOS/Linux :
    bashCopysource venv/bin/activate
  **4. Installer les dépendances :**
   pip install -r requirements.txt
   **Si le fichier requirements.txt n'existe pas, installez les dépendances principales :**
    bashCopypip install django pillow
**5.Effectuer les migrations de la base de données :**
    bashCopypython manage.py makemigrations
    python manage.py migrate
**6.Créer un superutilisateur (admin) :**
    bashCopypython manage.py createsuperuser
**Suivez les instructions pour créer le compte administrateur.**
**7. Charger les questions initiales (si vous avez un fichier de données) :**
    bashCopypython manage.py loaddata questions.json

**8. Collecter les fichiers statiques :**
    bashCopypython manage.py collectstatic

**9. Lancer le serveur de développement :**
    bashCopypython manage.py runserver
**10. Accéder à l'application :**
  Application : http://127.0.0.1:8000/    
