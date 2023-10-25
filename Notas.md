-------------------------------------------------------------------
                GITHUB
------------------------------------------------------------------- 
# Conocer el correo de GitHub logueado
git config --get user.email

# Establecer el correo de GitHub
git config --global user.email jmaymerich17@gmail.com

# Conocer el nombre de GitHub logueado
git config --get user.name

# Establecer el correo de GitHub logueado
git config --global user.name ChemaAymerich

# Convertir el directorio en un proyecto git
git init

git commit -m "Proyecto vacío"


-------------------------------------------------------------------
                INSTALACIÓN
------------------------------------------------------------------- 
# Teniendo pip instalado

pip install django djangorestframework

-------------------------------------------------------------------
                EJECUCIÓN DEL PROYECTO
------------------------------------------------------------------- 
# Migraciones -> Si devuelve No changes detected
python .\manage.py makemigrations

# Migración
python .\manage.py migrate

# Ejecución
python .\manage.py runserver




-------------------------------------------------------------------
                CREACIÓN DEL PROYECTO DJANGO
------------------------------------------------------------------- 
# Teniendo pip instalado
django-admin startproject IdentidadDigital

 cd .\IdentidadDigital\

 django-admin startapp API

# [Identidad Digital] Añadir en settings.py la aplicaicón API y el rest_framework

# [API] views editar

# [API] crear archivo urls.py -> se encarga de alamacenar

# [Identidad Digital] Incluir en urls.py la ruta de urls de API

# [API] modificar urls.py -> para que coja el fichero views.py


