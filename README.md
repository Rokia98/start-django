# start-django
d'abord on crée notre environnement virtuel " python -m venv myenv" 
activer son environnement en/Scrips/activate
on installe django "pip install django"
creer un project djangob " django-admin startproject 'le nom du projet' "
naviguer dans le repertoire du projet principale "cd le nom du dossier"
renommer le nom de notre project django src
creer des applications  django " python manage.py startapp 'nom de l'application' "
configurer ton project django, on rentre dansS' le fichier settings.py du projet principale et on ajoute le nom de notre application dans INSTALLED_APP
 configurer la base de donnée dans le settings.py on modifier la configuration de la BD sous la section 'DATABASES'
 creer des modeles  dans le fichier models.py de ton application apres avoir creer
 creer des templates (html,  xml) et scripts(css, js images) pour le Frontend 
 configurer les URLS 'ajouter un url pour acceder ala vue dans urls.py de ton application
 tester son site "python manage.pyrunserver
 pour creer les formulaires on installe django crispy et  'pip install crispy-boostrap4' et    
