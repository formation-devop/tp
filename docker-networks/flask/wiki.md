
[VARIABLES D'ENVIRONNEMENT]
- Fichier '.env'

[LANGUAGE]
- Python / Django

[DÉPENDANCES DU PROJET]
- Fichier 'requirements.txt'

[INSTALLATION DES DÉPENDANCES]
- pip install --no-cache-dir -r requirements.txt

[LANCEMENT DE L'APPLICATION]
- gunicorn --workers=4 --bind=0.0.0.0:4300 app:app
