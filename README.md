# TuPrimeraPagina+Cornacchione

Proyecto desarrollado en Django utilizando patrón MVT

## Funcionalidades
- Herencia de plantillas HTML 
- Modelos: Autor, Categoria, Post
- Formularios para cargar datos en cada modelo
- Formulario de búsqueda en BD

## Cómo ejecutar
Paso 1:
Abrir PowerShell y posicionarse en la carpeta del proyecto:
- cd Desktop\TuPrimeraPagina+Cornacchione
- Ejecutar.

Paso 2:
Activar el entorno virtual: A continuacion en PowerShell pegá lo siguiente
- .\venv\Scripts\activate
- Ejecutar.

Paso 3:
Ejecutar el servidor de Django:
- python manage.py runserver

Paso 4:
Abrir tu navegador favorito y copiar la siguiente dirección:
- http://127.0.0.1:8000/

## Orden recomendado para probar
1) Crear Autor: /autor/nuevo/
2) Crear Categoría: /categoria/nueva/
3) Crear Post: /post/nuevo/
4) Buscar Post: /post/buscar/
