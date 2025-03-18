# 📌 Prueba Técnica - Fullstack

Este es un proyecto Fullstack desarrollado con **Nest.js (Backend)** y **React con Material UI (Frontend)**.

## 🚀 Descripción

La aplicación permite gestionar estudiantes y cursos, incluyendo:
- Registro de estudiantes.
- Creación de cursos.
- Inscripción de estudiantes en cursos.
- Visualización de los cursos en los que está inscrito un estudiante.
- Modificación del límite de estudiantes en un curso.

---

## 📂 Estructura del Proyecto

```
📁 main/
 ├── 📁 frontend/   # Aplicación frontend con React
 ├── 📁 backend/    # API desarrollada en Nest.js
```

---

## ⚙️ Instalación y Ejecución

### 🔹 Requisitos Previos
- Node.js y npm instalados
- Docker instalado (opcional para PostgreSQL)

### 🔹 Clonar el repositorio
```bash
 git clone https://github.com/JJoseCT/PruebaT.git
 cd PruebaT
```

### 🔹 Backend (Nest.js + PostgreSQL + Prisma)
```bash
cd backend
npm install
```

#### Configurar la base de datos
Si usas Docker, ejecuta:
```bash
docker-compose up -d
```
Si usas una base de datos local, configura el archivo `.env` con tu conexión PostgreSQL.

#### Migrar la base de datos con Prisma
```bash
npx prisma migrate dev
```

#### Ejecutar el backend
```bash
npm run start
```
Acceder a la API en: `http://localhost:3001`

### 🔹 Frontend (React + Material UI)
```bash
cd ../frontend
npm install
npm start
```
Acceder a la app en: `http://localhost:3000`

---

## 🌐 URLs de Servicios Desplegados

- **Frontend:** [URL del frontend](#)
- **Backend:** [URL del backend](#)
- **Documentación API (Swagger):** [URL de Swagger](#)

*(Reemplaza `#` con los enlaces reales si los tienes desplegados.)*

---

## 📖 Documentación Relevante

- [NestJS - Documentación](https://docs.nestjs.com/)
- [React - Documentación](https://react.dev/)
- [Prisma - Documentación](https://www.prisma.io/docs/)
- [Docker - Documentación](https://docs.docker.com/)

---

## 📌 Notas Finales
Si tienes dudas o sugerencias, abre un issue en el repositorio. 😊

