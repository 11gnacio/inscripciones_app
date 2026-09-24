# Inscripciones App (Relación N:N)

Aplicación web desarrollada con **Flask**, **MySQL** y el patrón de diseño **MVC** (Modelo-Vista-Controlador). Demuestra el manejo de relaciones Muchos a Muchos (N:N) en bases de datos relacionales mediante una tabla intermedia y claves primarias compuestas.

---

## 🛠️ Tecnologías Utilizadas

* **Python 3**
* **Flask** (Framework web)
* **PyMySQL** (Conector MySQL)
* **Bootstrap 5** (Estilos UI)
* **MySQL** (Motor de base de datos)
* **Pipenv** (Gestión de entornos virtuales)

---

## 📁 Estructura del Proyecto

```text
inscripciones_app/
│
├── flask_app/
│   ├── bd/
│   │   └── esquema_educacion.sql
│   │
│   ├── config/
│   │   ├── __init__.py
│   │   └── mysqlconnection.py
│   │
│   ├── controllers/
│   │   ├── __init__.py
│   │   └── inscripciones.py
│   │
│   ├── models/
│   │   ├── __init__.py
│   │   ├── estudiante.py
│   │   ├── curso.py
│   │   └── inscripcion.py
│   │
│   ├── static/
│   │   └── css/
│   │       └── style.css
│   │
│   ├── templates/
│   │   └── index.html
│   │
│   └── __init__.py
│
├── resources/
│   ├── esquema_educacion_erd.mwb
│   └── esquema_educacion_erd.png
│
├── .env
├── .gitignore
├── Pipfile
├── Pipfile.lock
└── server.py