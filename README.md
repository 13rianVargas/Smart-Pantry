# Smart Pantry & Waste Tracker 🍎🥦

[![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)](https://www.docker.com/)
[![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)](https://spring.io/projects/spring-boot)
[![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)](https://angular.io/)
[![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)](https://www.mongodb.com/)

**Smart Pantry & Waste Tracker** es una aplicación fullstack diseñada para gestionar los productos de tu cocina con un enfoque en la **sostenibilidad y el ahorro**. No es solo un inventario; es una herramienta inteligente que te ayuda a priorizar qué cocinar hoy basándose en fechas de vencimiento y el costo de tus productos.

---

## 🚀 Funcionalidades Clave

- **Gestión de Stock:** CRUD de productos con categorías, fechas de vencimiento y unidades.
- **Semáforo de Prioridad:** Visualización intuitiva de productos que vencen en menos de 48 horas.
- **Calculadora de "Valor en Riesgo":** Conoce cuánto dinero podrías perder si tus productos se vencen.
- **Lista de Compras Inteligente:** Generación de listas basada en un stock mínimo definido.
- **Dockerizado:** Entorno listo para producción con contenedores para Frontend, Backend y Base de Datos.

## 🛠️ Stack Tecnológico

- **Frontend:** Angular 15+, Angular Material.
- **Backend:** Spring Boot 3.x (Java), Spring Data MongoDB.
- **Base de Datos:** MongoDB (NoSQL).
- **DevOps:** Docker & Docker Compose.

## 📦 Estructura del Proyecto

```text
.
├── backend/        # API REST con Spring Boot
├── frontend/       # Aplicación Web con Angular
├── docker/         # Configuraciones de contenedores
├── docker-compose.yml
└── README.md
```

## ⚙️ Requisitos Previos

- [Java 17+](https://www.oracle.com/java/technologies/downloads/)
- [Node.js 18+](https://nodejs.org/)
- [Docker & Docker Compose](https://www.docker.com/products/docker-desktop/)
- [Angular CLI](https://angular.io/cli)

## 🏁 Instalación Fast Track (Docker)

1. Clona el repositorio:
   ```bash
   git clone https://github.com/13rianVargas/Smart-Pantry.git
   cd Smart-Pantry
   ```

2. Ejecuta con Docker:
   ```bash
   docker-compose up -d
   ```

3. Accede a la aplicación:
   - Frontend: `http://localhost:80`
   - API Docs (Swagger): `http://localhost:8080/swagger-ui.html`

---

## 👨‍💻 Autor
**Brian Vargas** - [GitHub](https://github.com/13rianVargas)

---
*Este proyecto fue desarrollado con un propósito educativo para demostrar habilidades Fullstack y DevOps.*
