# structure du projet django
pour la créaion de mon projet django je dois créer mon dossier qui va contenir mon projet et l'ouvrir dans mon éditeur 
1) créer un environnement virtuel avec: python -m venv env
2) activer l'environment virtuel: source env/Scripts/activate
3) installer django: python -m pip install django
4) créer le projet django: python -m startproject "nom"
5) créer l'application python: python manage.py startapp "app"
6) lister les applications créer dans le fichier setting dans 'installed_apps' 
7) dans chaque application créer un fichier urls.py qui va contenir les différents liens de chaque application 
8) créer aussi dans chaque app ou il y aura un formulaire un fichier form qui peut nous permettre de créer formulaire non lier ou lier a notre fichier model qui communique avec notre base de donnée
9) ajouter le lien des différentes applications dans l'urlparthern du fichier urls.py
10) ne pas oublier d'ajouter le static url et le staticfiles dirs et dans la database base_dir et templates
11) nous pouvons aussi créer une base de donné et insérer les différentes information de notre base de donnée a 'database' dans notre fichier setting
12) dans notre fichier model nous devons lister les différent champs de notre base de donnée étape a faire avant les migrations
13) pour pouvoir parfaitement connection on fera les migration :python manage.py makemigrations et python manage.py migrate
14) a la base de notre projet nous allons créer un dossier templates qui va contenir les fichier html et le fichier static qui va stoquer les dossier css,js,images,fonts
15) lancer: avec python manage.py runserver
