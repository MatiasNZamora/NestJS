<p align="center">
  <a href="https://nestjs.com/" target="_blank">
    <img src="https://nestjs.com/img/logo-small.svg" width="100" alt="NestJS Logo" />
  </a>
</p>

<h1 align="center">🧩 Repositorio de Proyectos NestJS</h1>

<p align="center">
  Colección de proyectos desarrollados con <strong>NestJS</strong>, enfocados en arquitectura modular, buenas prácticas y escalabilidad.  
  Cada uno de estos proyectos refleja distintas implementaciones backend modernas utilizando TypeScript, Node.js y PostgreSQL/MongoDB.
</p>

---

## 🚀 Sobre este repositorio

Este repositorio agrupa diferentes proyectos backend desarrollados con **NestJS**, mostrando la evolución, estructura y buenas prácticas aplicadas en entornos reales.  
Cada carpeta representa un proyecto independiente con su propio README y documentación.

El objetivo es mantener un entorno organizado y accesible para la revisión de código, el aprendizaje y la colaboración.

---

## 📂 Lista de proyectos

| Proyecto | Descripción | Enlace |
|-----------|--------------|--------|
| 🧾 **Reportes PDFs NestJS** | Servicio backend para generación de reportes en PDF utilizando NestJS, TypeORM y plantillas dinámicas. | [Ver proyecto](https://github.com/MatiasNZamora/Reportes-PDFs-NestJs) |
| 🏞️ **Talampaya Backend** | API backend desarrollada para la gestión de datos turísticos del Parque Nacional Talampaya. | [Ver proyecto](https://github.com/MatiasNZamora/Talampaya-backend) |
| 🛒 **TesloShop Backend** | API completa de e-commerce desarrollada con NestJS, autenticación JWT y PostgreSQL. | [Ver proyecto](https://github.com/MatiasNZamora/tesloshop-backend) |
| ⚡ **NestJS GraphQL API** | API desarrollada con NestJS y GraphQL utilizando Code First, autenticación JWT, relaciones en PostgreSQL, paginaciones, filtros y despliegue con Docker. | [Ver proyecto](https://github.com/MatiasNZamora/Nest-GraphQL) |


---

## 🧱 Tecnologías principales

- **[NestJS](https://nestjs.com/)** – Framework progresivo para Node.js  
- **TypeScript** – Tipado estático y robustez en el desarrollo  
- **TypeORM** – ORM para bases de datos SQL  
- **PostgreSQL / MongoDB** – Bases de datos relacionales y NoSQL  
- **GraphQL** – APIs flexibles y eficientes para el consumo de datos  
- **JWT & Passport** – Autenticación y autorización  
- **Docker** – Contenedorización y despliegue  
- **Testing (Jest)** – Pruebas unitarias y de integración  

---

## 📘 Estructura general de proyectos

Cada proyecto sigue una estructura modular y escalable:

```
src/
 ├── modules/        # Módulos de funcionalidad
 ├── common/         # Reutilizables, DTOs, interceptores, pipes
 ├── config/         # Variables de entorno, conexiones DB
 ├── main.ts         # Punto de entrada principal
 └── app.module.ts   # Módulo raíz
```

---

## 🧠 Buenas prácticas aplicadas

- Arquitectura modular basada en **Domain-Driven Design (DDD)**
- Aplicación del principio **DRY (Don't Repeat Yourself)** para optimizar la reutilización de código
- Uso de **Swagger** y **OpenAPI** para documentación dinámica de endpoints
- Implementación de **Winston** para registro avanzado y manejo de logs
- **Integración con Docker** para facilitar entornos de desarrollo y despliegue reproducibles
- Configuración y uso de bases de datos **PostgreSQL** y **MongoDB** en entornos híbridos
- Manejo centralizado de errores y validaciones
- Control de versiones de base de datos con **TypeORM migrations**
- Testing con **Jest** y **Supertest**
- Integración continua y despliegue en entornos productivos

---

## 📫 Contacto

👤 **Matías N. Zamora**  
💼 Desarrollador Fullstack & Asesor Técnico  
🌐 [Portafolio](https://matiasnzamora.com.ar)  
📧 [matiaszamora@email.com](mailto:devmatiasnzamora@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/matiasnzamora/)  

---

<p align="center">
  <sub>Desarrollado con ❤️ y NestJS • © 2025 Matías N. Zamora</sub>
</p>

