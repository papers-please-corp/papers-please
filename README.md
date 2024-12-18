# Papers - Please

## Proyecto Fullstack: React, Node.js, Express y SQLite

Este proyecto es una aplicación fullstack que utiliza **React** para el frontend, **Node.js** con **Express** para el backend, **SQLite** como base de datos y **OpenAi API** para el chatbot.

## Requisitos

- **Node.js** (https://nodejs.org)
- **npm** o **yarn** para gestionar paquetes.

## Instalación

1. Clona el repositorio e instala dependencias:

    - Backend:
      ```bash
      cd server
      npm install
      ```

    - Frontend:
      ```bash
      cd ../client
      npm install
      ```

## Cómo levantar el proyecto

1. **Servidor (Backend)**:
    - Abre una terminal y ejecuta:
      ```bash
      cd server
      node server.js
      ```
    - El backend estará en `http://localhost:5000`.

2. **Cliente (Frontend)**:
    - En otra terminal, ejecuta:
      ```bash
      cd client
      npm start
      ```
    - El frontend estará en `http://localhost:3000`.

## Base de Datos

La base de datos SQLite está en `server/database.db`.

Si te paras en server podes ejecutar *sqlite3 database.db* y te deja hacer querys


# OpenAI API
Para poder correr el codigo se necesita una key de la API de OpenAI colocada en el .env de la carpeta server.

---

¡Listo! Con estos pasos puedes levantar el frontend y backend por separado.
