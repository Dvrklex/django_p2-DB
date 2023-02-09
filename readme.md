# Django Practice Parte 2 
Utilizando SQLite3

# Comandos 
## Crear el projecto
python manage.py startproject <nombre del projecto>

## Crear aplicación 
python manage.py startapp <nombre de la aplicación>

## Agregar aplicación a setting.py y checkear si se agrego correctamente
python manage.py check <nombre de la aplicación>

## Crear Base de Datos
python manage.py makemigrations

## Crear código SQL para crear las tablas
python manage.py sqlmigrate <nombre de la aplicacion> <codigo de migracion>

- El codigo de migración se crea con el comando makemigrations

## Agregar las tablas a la Base de Datos
python manage.py migrate


# Ejecutar Django 
python manage.py runserver