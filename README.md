# Sistema de Recordatorios de Pago

Sistema web desarrollado en Django para gestionar recordatorios de pago a clientes mediante WhatsApp y correo electrónico.

## 🚀 Características

- Gestión completa de clientes y facturas
- Sistema de recordatorios automáticos  
- Envío por Email (Gmail) y WhatsApp (simulado)
- Panel de administración Django
- Tareas programadas con Celery

## 🛠️ Tecnologías

- Django 4.2
- Celery
- Redis
- SQLite (desarrollo) / PostgreSQL (producción)
- Bootstrap 5

## 📄 Licencia

Este software es propietario y está protegido por derechos de autor. 
Queda prohibido el uso comercial sin autorización expresa.

**Copyright (c) 2024 Patricia Mariela Bernasconi - Todos los derechos reservados**

Para licencias comerciales, contactar: [pachuberna@gmail.com]

## 📦 Instalación

```bash
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver