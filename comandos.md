cd C:\Users\alvar\Documents\GitHub\django_holamundo>

# Como crear entorno python
conda create --name entorno_holadjango_310 python=3.10

# activar entorno python 
conda activate entorno_holadjango_310

# Desactivr el entorno
conda deactivate

# Guardar un texto con todos los paquetes
pip freeze > requirement.txt

# Instalar los paquetes
pip install -r .\requirement.txt

# Crear admin
 django-admin startproject holamundo

 # correr el servidor
 python manage.py runserver

 # Crear usuario
 python manage.py createsuperuser

 # Migrar
 python manage.py migrate