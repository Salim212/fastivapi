! VOUS DEVEZ CREER UN FICHIER .env EN Y INSERANT UN MAIL ET UN MOT DE PASSE PAR UNE ADRESSE MAIL VALIDE !

Commandes à réaliser pour le bon fonctionnement de l'API :


Lancement de l'environnement :

python3 -m venv venv
source venv/bin/activate


Installations requises :

pip install fastapi
pip install uvicorn
pip install tortoise-orm
pip install fastapi-mail
pip install python-dotenv
pip install pyjwt
pip install python-multipart
python3 -m pip install --upgrade Pillow
pip install aiofiles


Commande pour lancer et relancer l'API :

uvicorn main:app --reload

Commande permettant de noter les exigences dans un fichier texte :

pip freeze > requirements.txt
