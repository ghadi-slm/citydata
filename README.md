# City Data

**Ouvrez un terminal et clonez le projet :**

git clone https://github.com/ghadi-slm/citydata.git

cd VOTRE-REPO

## Lancer l’application/Démarrer le serveur Django : 

écrire dans le terminal: python manage.py runserver

Accédez à l’application sur http://127.0.0.1:8000/.

## Structure du projet

📂 visualisation/ → Application principale (contient les vues et modèles)

* models.py : Définit la structure de la base de données
* view.py : Gère la logique de l’application et les réponses aux requêtes
* urls.py	: Associe les URLs aux vues correspondantes

📂 visualisation/templates/visualisation/ → Fichiers HTML

📄 requirements.txt → Liste des dépendances

## Travailler avec Git et GitHub

### Ajouter et valider les modifications :

git add .

git commit -m "Description des modifications"

git push origin main 

### Récupérer les mises à jour du projet

git checkout -- db.sqlite3 : remplace la version locale par celle du dernier commit

git pull origin main
=======
# citydata
>>>>>>> origin/main
