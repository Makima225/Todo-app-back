# Backend de l'application TodoList
cette partie génere les Api de notre application avec rest framework

# Inscription/Connexion de l'utilisateur
Les utilisateurs s'inscrivent ou se connectent à l'aide des tokens avec simple jwt tokens

# Creation de l'utilisateur
la creation de l'utilisateur se fait de maniere simple avec (le nom et prenom , username , password )

# les Taches
toutes les taches sont liés à un utilisateurs 

# Prerequis
- Python 3.8+
- pip
- environnement virtuel (virtualenv) : recommandé

# Installation
1. Cloner le repo :
2. Créer et activer l'environnement virtuel :
  Sur Linux :

  python3 -m venv venv
  source venv/bin/activate

  Sur Windows :
  py -m venv venv
  venv\Scripts\activate

3. Installer les dépendances : 

  pip install -r requirements.txt

4. Configurer la base de données :

    python manage.py migrate
## Lancement du Serveur

python manage.py runserver


L'API sera disponible à `http://localhost:8000/api/v1`.  

## les Différents endpoints

### Au niveau utilisateur

1. connexion avec token:
   http://localhost:8000/api/v1/token/
2. creer un utilisateur:
  http://localhost:8000/api/v1/users/create/

3. Déconnexion:
   http://localhost:8000/api/v1/token/logout/


