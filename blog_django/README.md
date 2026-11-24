# Blog Django - Preentrega 7

Base inicial y estructura técnica para el desarrollo de un blog web utilizando el framework Django.

---

## 🛠️ Requisitos previos

- Python 3.x
- Git

---

## 🚀 Instalación y configuración del entorno

1. **Clonar el repositorio:**
   ```bash
   git clone https://github.com/benjakalnay/Proyecto_blog.git
   cd blog_django
2. **Crear y activar el entorno virtual**

   Crear el entorno virtual:
   ```bash
   python -m venv venv
   ```

   Activarlo en **Windows (PowerShell)**:
   ```powershell
   .\venv\Scripts\Activate.ps1
   ```

   Activarlo en **Linux o macOS**:
   ```bash
   source venv/bin/activate
   ```

3. **Instalación de dependencias**
   ```bash
   pip install -r requirements.txt
   ```

## Ejecución del servidor

```bash
python manage.py runserver
```

Luego abrir el navegador en: http://127.0.0.1:8000/

## Estructura del proyecto

```
blog_django/
├── manage.py
├── requirements.txt
├── .gitignore
├── README.md
├── blog_project/
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   └── wsgi.py
└── posts/
    ├── __init__.py
    ├── admin.py
    ├── apps.py
    ├── models.py
    ├── tests.py 
    └── views.py
```
## Configuraciones realizadas
- Proyecto principal: blog_project
- Aplicación creada: posts (registrada en INSTALLED_APPS)
- Idioma y zona horaria: configurada para español regional en settings.py
