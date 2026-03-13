# Sports Reservation System

Sistema web para la gestión de reservas de canchas deportivas.

Permite reservar turnos online, visualizar disponibilidad en un calendario y administrar reservas desde un panel con estadísticas.

Este proyecto fue desarrollado como parte de mi portfolio para demostrar habilidades en desarrollo backend con Python y Django, integrando una API REST con un frontend en React.

---

# Demo del sistema

El sistema permite:

• Reservar turnos de cancha  
• Visualizar horarios disponibles  
• Administrar reservas desde un calendario  
• Analizar estadísticas de uso en un dashboard  

---

# Tecnologías utilizadas

## Backend

- Python
- Django
- Django REST Framework

## Frontend

- React
- Axios
- FullCalendar
- Recharts

## Base de datos

- SQLite (entorno de desarrollo)

---

# Funcionalidades principales

- Creación de reservas de turnos
- Visualización de reservas en calendario
- Panel administrativo
- Dashboard con estadísticas
- API REST para gestión de reservas
- Interfaz responsive

---

# Arquitectura del proyecto
sports-reservation-system
│
├── backend
│ ├── config
│ ├── reservations
│ ├── fields
│ ├── users
│ ├── manage.py
│ └── requirements.txt
│
├── frontend
│ ├── public
│ ├── src
│ ├── package.json
│
└── README.md


El backend expone una API REST desarrollada con Django REST Framework que es consumida por el frontend construido en React.

---

# API Endpoints

## Reservas

GET /reservations/  
Obtiene todas las reservas registradas

POST /reservations/  
Crea una nueva reserva

---

# Instalación del proyecto

## 1 Clonar el repositorio
git clone https://github.com/Gonza9999/sistema-de-reservas-cancha.git


---

## 2 Backend
cd backend

pip install -r requirements.txt

python manage.py migrate

python manage.py runserver


---

## 3 Frontend

Abrir otra terminal:


cd frontend

npm install

npm start



---

# Screenshots

## Página de reservas

![Reservas](docs/reservas.png)

## Calendario administrativo

![Calendario](docs/calendario.png)

## Dashboard

![Dashboard](docs/dashboard.png)

# Mi rol en el proyecto

Este proyecto fue desarrollado principalmente para demostrar habilidades en desarrollo backend utilizando Python y Django.

Me encargué de:

- Diseño de modelos de datos
- Desarrollo de la API REST
- Implementación de lógica de reservas
- Integración entre backend y frontend
- Construcción de dashboard de estadísticas

El frontend fue implementado en React para consumir la API y mostrar la interfaz de reservas, calendario y estadísticas.

---

# Posibles mejoras futuras

- Sistema de autenticación de usuarios
- Notificaciones de reservas
- Implementación de pagos online
- Despliegue en la nube
- Gestión de múltiples canchas
- Panel de reservas para admin y nuevas estadisticas como ganancias diarias, semanales y mensuales

---


