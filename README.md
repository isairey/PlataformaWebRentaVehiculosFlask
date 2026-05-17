<div align="center">

<img width="220" src="https://cdn-icons-png.flaticon.com/512/2554/2554936.png" />

# 🚗 Car Rental DMS

### Plataforma web de gestión y renta de vehículos con Flask 🚀

<p align="center">
  <b>Car Rental DMS</b> es un sistema de administración de renta de automóviles desarrollado con Flask y MySQL, diseñado para gestionar reservas, selección de vehículos y control de ubicaciones de entrega y devolución mediante una plataforma moderna y dinámica.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/CarRental-WebPlatform-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Flask-PythonFramework-000000?style=for-the-badge&logo=flask&logoColor=white">
  <img src="https://img.shields.io/badge/MySQL-Database-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
  <img src="https://img.shields.io/badge/OpenSource-DatabaseSystem-success?style=for-the-badge">
</p>

<p align="center">
  <a href="#-acerca-del-proyecto">Acerca</a> •
  <a href="#-módulos-del-sistema">Módulos</a> •
  <a href="#-características">Características</a> •
  <a href="#-tecnologías-utilizadas">Tecnologías</a> •
  <a href="#-vista-previa">Vista previa</a>
</p>

</div>

---

# 🌌 Acerca del proyecto

**Car Rental DMS** es una plataforma web enfocada en la administración de reservas y alquiler de vehículos mediante una arquitectura basada en Flask y MySQL.

El sistema permite a los clientes realizar reservas, seleccionar automóviles y administrar ubicaciones de recogida y devolución desde una interfaz intuitiva y centralizada.

El sistema fue diseñado para:

- 🚗 Gestionar vehículos
- 👥 Administrar clientes
- 📅 Gestionar reservas
- 📍 Controlar ubicaciones
- 💳 Gestionar alquileres
- 📊 Visualizar información
- 🔐 Administrar accesos
- 🌐 Centralizar operaciones

---

# ✨ Características

## 🚘 Gestión de vehículos

- 🚗 Registro de automóviles
- 📍 Gestión de disponibilidad
- 💰 Configuración de precios
- 📋 Información detallada
- ⚡ Administración dinámica

---

## 👥 Gestión de usuarios

- 👤 Registro de clientes
- 🔐 Inicio de sesión
- 📄 Gestión de perfiles
- 📊 Historial de reservas
- ⚡ Administración centralizada

---

## 📅 Sistema de reservas

- 📆 Reservas vehiculares
- 🚘 Selección de automóviles
- 📍 Ubicación de entrega y devolución
- ⚡ Confirmaciones rápidas
- 📄 Historial de operaciones

---

## 📊 Panel administrativo

- 📈 Dashboard administrativo
- 🚗 Supervisión vehicular
- 📅 Gestión de reservas
- 👥 Administración de usuarios
- 🔐 Gestión del sistema

---

# 👨‍💼 Módulos del sistema

## 🚗 Vehicle Module

Este módulo administra toda la información de vehículos disponibles.

### Funcionalidades:

- ➕ Registro de automóviles
- 📍 Gestión de disponibilidad
- 💰 Tarifas de alquiler
- 📋 Información técnica
- ⚡ Administración vehicular

---

## 👥 Customer Module

Este módulo es utilizado por clientes del sistema.

### Funcionalidades:

- 🔍 Buscar vehículos
- 📅 Reservar automóviles
- 📍 Seleccionar ubicaciones
- 💳 Gestionar alquileres
- 📄 Consultar historial

---

## 📅 Reservation Module

Este módulo administra las reservas y operaciones de renta.

### Funcionalidades:

- 📆 Gestión de reservas
- 🚗 Asignación vehicular
- 📍 Control de ubicaciones
- 💰 Gestión financiera
- ⚡ Confirmaciones rápidas

---

## 🛠️ Admin Module

Este módulo funciona como administrador principal.

### Funcionalidades:

- 👥 Gestión de usuarios
- 🚗 Supervisión vehicular
- 📊 Dashboard administrativo
- 📅 Gestión de reservas
- 🔐 Administración general

---

# 🛠️ Tecnologías utilizadas

## 🎨 Frontend

<p>
  <img src="https://skillicons.dev/icons?i=html,css,js" />
</p>

- HTML5
- CSS3
- JavaScript
- Templates Flask

---

## ⚙️ Backend

<p>
  <img src="https://skillicons.dev/icons?i=python,flask" />
</p>

- Python
- Flask
- Arquitectura MVC
- Sistema CRUD

---

## 🗄️ Base de datos

<p>
  <img src="https://skillicons.dev/icons?i=mysql" />
</p>

- MySQL
- MySQL Workbench
- Relaciones SQL
- Persistencia de datos

---

## 🧰 Herramientas

<p>
  <img src="https://skillicons.dev/icons?i=git,github,vscode" />
</p>

- Git
- GitHub
- Visual Studio Code
- Python Pip

---

# 📂 Estructura del proyecto

```bash
Car-Rental-DMS/
│
├── main/                     # Aplicación principal Flask
├── static/                   # Recursos frontend
├── templates/                # Plantillas HTML
├── db/                       # Scripts SQL
│   └── schema/
├── models/                   # Modelos de datos
├── routes/                   # Rutas del sistema
├── requirements.txt
├── main.py                   # Punto de entrada
├── README.md
└── LICENSE
```

---

# ⚡ Instalación

## 📋 Requisitos

- Python 3.9+
- Flask
- MySQL Server
- MySQL Workbench
- Pip

---

# 🚀 Configuración del proyecto

## 1️⃣ Clonar repositorio

```bash
git clone https://github.com/isairey/Car-Rental-DMS.git
```

---

## 2️⃣ Instalar dependencias

```bash
pip install -r requirements.txt
```

---

## 3️⃣ Instalar paquetes adicionales

```bash
pip install flask
pip install wheel
```

---

## 4️⃣ Configurar base de datos

Crear base de datos:

```sql
CREATE DATABASE car_db;
```

---

## 5️⃣ Configurar MySQL

| Usuario | Contraseña |
|----------|-------------|
| root     | root        |

---

## 6️⃣ Importar scripts SQL

Importar:

```bash
db/schema/
```

---

## 7️⃣ Ejecutar proyecto

```bash
python main.py
```

---

## 8️⃣ Abrir aplicación

```bash
http://localhost:5000
```

---

# 📊 Funcionalidades principales

## 🚗 Gestión vehicular

- Administración de automóviles
- Gestión de disponibilidad
- Configuración de tarifas
- Información detallada

---

## 👥 Administración de clientes

- Registro y autenticación
- Gestión de perfiles
- Historial de reservas
- Gestión de alquileres

---

## 📅 Gestión de reservas

- Reservas dinámicas
- Ubicaciones de entrega
- Confirmaciones rápidas
- Historial financiero

---

# 📸 Vista previa

## 🖥️ Interfaces del sistema

<div align="center">

### 🏠 Página principal
![Home](/main/static/img/home.JPG?raw=true)

### 🔐 Registro de usuarios
![Signup](/main/static/img/signup.JPG?raw=true)

### 🚘 Selección de vehículos
![Selection](/main/static/img/selection.JPG?raw=true)

### 📅 Página de reservas
![Reservation](/main/static/img/reservation.JPG?raw=true)

</div>

---

# 🧠 Objetivos del proyecto

## 🎯 Aprendizaje y administración

- Desarrollo web con Flask
- Bases de datos relacionales
- Arquitectura MVC
- Gestión vehicular
- Automatización de reservas
- Sistemas administrativos
- Programación backend Python

---

# 🚧 Roadmap

## 🔮 Próximas mejoras

- 📱 Aplicación móvil
- ☁️ Infraestructura cloud
- 💳 Integración de pagos online
- 🤖 Reportes inteligentes
- 🌐 API REST moderna
- 🔔 Notificaciones en tiempo real
- 📍 Geolocalización de sucursales

---

# 🤝 Contribuciones

Las contribuciones son bienvenidas ❤️

## Cómo contribuir

1. Fork del proyecto

```bash
git checkout -b feature/nueva-funcionalidad
```

2. Commit

```bash
git commit -m "✨ Nueva funcionalidad"
```

3. Push

```bash
git push origin feature/nueva-funcionalidad
```

4. Pull Request 🚀

---

# 👨‍💻 Desarrollador

<div align="center">

## Isai Reyes — Python & Flask Developer

Desarrollador apasionado por plataformas vehiculares, sistemas administrativos y aplicaciones backend modernas 🚀

</div>

---

# 🌟 Apoya el proyecto

⭐ Dale una estrella  
🍴 Haz fork  
📢 Comparte el proyecto

---

# 📜 Licencia

Proyecto open source orientado al aprendizaje de Flask, MySQL y sistemas de gestión vehicular.

---

<div align="center">

### 🚗 Car Rental DMS — administración inteligente de vehículos y reservas 🚀

</div>
