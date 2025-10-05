# 🎼 Pentagrama: E-commerce de Instrumentos Musicales

**Pentagrama** es una aplicación web de comercio electrónico desarrollada en **Python** con el *framework* **Flask**. Su objetivo es simular una tienda en línea moderna para la venta y exhibición de instrumentos musicales.

El proyecto está diseñado para ser modular y escalable, utilizando entornos virtuales para la gestión limpia de dependencias.

## ✨ Características Principales

  * **Catálogo de Productos:** Sección dedicada a mostrar productos destacados (Saxofones, Baterías, Guitarras, etc.).
  * **Navegación Limpia:** Rutas definidas para `Inicio`, `Servicios`, `Contacto`, y `Sesión` (Login).
  * **Estructura Base:** Uso de plantillas **Jinja2** con un diseño base (`base.html`) para herencia y uniformidad visual.
  * **Archivos Estáticos:** Gestión de recursos CSS, imágenes y videos (MP4) en la carpeta `static`.

-----

## 🛠️ Tecnologías Utilizadas

| Componente | Tecnología | Propósito |
| :--- | :--- | :--- |
| **Lenguaje** | Python 3.x | Backend y lógica de la aplicación. |
| **Web Framework** | Flask | Manejo de rutas, vistas y peticiones HTTP. |
| **Plantillas** | Jinja2 | Renderizado de HTML dinámico. |
| **Estilos** | Flask-Bootstrap | Integración de Bootstrap para estilos y *responsive design*. |
| **Seguridad** | `app.config['SECRET_KEY']` | Clave secreta necesaria para la seguridad de sesiones de Flask. |

-----

## 🚀 Puesta en Marcha (Instalación y Ejecución)

Sigue estos pasos para configurar y ejecutar el proyecto en tu máquina local:

### 1\. Clonar el Repositorio

```bash
git clone [URL_DE_TU_REPOSITORIO]
cd pentagrama
```

### 2\. Crear y Activar el Entorno Virtual

Es crucial aislar las dependencias del proyecto.

```bash
# Crear el entorno
python -m venv venv

# Activar el entorno (Usando la estructura tipo Linux 'bin' que usa este proyecto)
# Para PowerShell:
.\venv\bin\activate

# Para Git Bash / Linux:
# source venv/bin/activate
```

### 3\. Instalar Dependencias

Asegúrate de tener un archivo `requirements.txt` o instala las librerías necesarias:

```bash
# Si tienes requirements.txt (Recomendado)
pip install -r requirements.txt

# Si no tienes requirements.txt, instala manualmente:
# pip install Flask Flask-Bootstrap
```

### 4\. Ejecutar la Aplicación

Con el entorno `(venv)` activo, inicia el servidor de desarrollo:

```bash
python app.py
```

