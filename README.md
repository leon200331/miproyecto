# Tienda en Línea

Este proyecto es una **Tienda en Línea** desarrollada con Django (o el framework que uses), diseñada para gestionar productos, clientes, carrito de compras y pedidos, facilitando la venta de artículos de forma digital.

---

## Descripción

La aplicación permite a los usuarios navegar por un catálogo de productos, agregar productos al carrito, modificar cantidades, y realizar pedidos. Los administradores pueden gestionar productos, clientes y pedidos mediante un panel administrativo.

---

## Características principales

- Registro y autenticación de usuarios.
- Catálogo de productos con descripción, precio y stock.
- Carrito de compras con opción para agregar, modificar o eliminar productos.
- Creación y gestión de pedidos con estado.
- Panel administrativo para gestión de productos, clientes y pedidos.
- Manejo de sesiones para mantener el carrito activo.
- (Agregar aquí otras características que tenga tu proyecto)

---

## Tecnologías usadas

- Python 3.x
- Django x.x.x (u otro framework que uses)
- HTML5, CSS3, JavaScript
- Base de datos: SQLite/MySQL/PostgreSQL (según tu configuración)
- Otros: Bootstrap, jQuery, etc.

---

## Instalación y ejecución

1. Clonar el repositorio

```bash
git clone https://github.com/tu_usuario/tu_repositorio.git
cd tu_repositorio
Crear y activar entorno virtual (opcional pero recomendado)

bash
Copiar
python -m venv venv
.\venv\Scripts\activate.ps1   # Windows
Instalar dependencias

bash
Copiar
pip install -r requirements.txt
Migrar base de datos

bash
Copiar
python manage.py migrate
Ejecutar servidor de desarrollo

bash
Copiar
python manage.py runserver
