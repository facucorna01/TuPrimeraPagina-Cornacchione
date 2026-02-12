# TuPrimeraPagina+Cornacchione

Proyecto Web en Django (patrón MVT) tipo blog.

## Funcionalidades (requisitos)
- Herencia de plantillas HTML (base.html + templates que extienden)
- Modelos (3 clases): Autor, Categoria, Post
- Formularios para cargar datos en cada modelo
- Formulario de búsqueda en BD (Post por título)

## Cómo ejecutar
1) Crear entorno e instalar dependencias:
- python -m venv venv
- activar venv
- pip install -r requirements.txt

2) Migraciones:
- python manage.py makemigrations
- python manage.py migrate

3) Correr servidor:
- python manage.py runserver

## Orden recomendado para probar
1) Crear Autor: /autor/nuevo/
2) Crear Categoría: /categoria/nueva/
3) Crear Post: /post/nuevo/
4) Buscar Post: /post/buscar/
