# Rick & Morty Gallery 🛸

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Django](https://img.shields.io/badge/Django-4.2-green?logo=django)
![Bootstrap](https://img.shields.io/badge/Bootstrap-5-purple?logo=bootstrap)

Trabajo práctico final de la materia **Introducción a la Programación**. Aplicación web en Django que consume la [Rick & Morty API](https://rickandmortyapi.com/) para explorar personajes de la serie.

## Funcionalidades

- Galería de personajes con imagen, nombre, estado, ubicación y episodio inicial
- Buscador por nombre
- Login / logout de usuarios
- Favoritos por usuario con opción de eliminar
- Borde de color en cards según estado del personaje (vivo / muerto / desconocido)

## Instalación
```bash
git clone https://github.com/tu-usuario/rick-morty-gallery.git
cd rick-morty-gallery
pip install -r requirements.txt
python manage.py runserver 3000
```

Abrir `http://localhost:3000` — usuario de prueba: `admin / admin`

## Stack

Python · Django 4.2 · SQLite · Bootstrap 5
