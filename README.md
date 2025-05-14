# Fullstack REST API Node.js + TypeScript + React (PERN Stack)

Este proyecto es una aplicación fullstack que utiliza el stack PERN (PostgreSQL, Express, React, Node.js) con TypeScript en el backend y frontend. Permite la administración de productos mediante una API REST y una interfaz web moderna.

## Características

- **Backend**: Node.js, Express, TypeScript, Sequelize, PostgreSQL
- **Frontend**: React, TypeScript, Vite, TailwindCSS, React Router
- **API REST**: CRUD de productos
- **Validaciones**: Middleware y validaciones en el backend
- **Documentación**: Swagger UI para la API
- **Testing**: Jest para pruebas y cobertura
- **Hot Reload**: Vite y nodemon para desarrollo ágil

## Estructura del Proyecto

```
├── client/         # Frontend React + Vite
│   ├── src/
│   │   ├── components/
│   │   ├── layouts/
│   │   ├── services/
│   │   ├── types/
│   │   ├── utils/
│   │   ├── views/
│   │   ├── main.tsx
│   │   ├── router.tsx
│   │   └── ...
│   ├── public/
│   ├── index.html
│   ├── ...
|   ├ README.md
```

## Instalación

### 1. Clona el repositorio

```sh
git clone https://github.com/kevirui/rest_apis_typescript_frontend.git
cd fullstack-rest_api_node_ts
```

### 2. Configura las variables de entorno

- Copia `.env.example` a `.env` en `server/` y configura tus credenciales de PostgreSQL.
- Copia `.env.local.example` a `.env.local` en `client/` si es necesario.

### 3. Instala dependencias

#### Frontend

```sh
cd ../client
npm install
```

## Uso

### Levantar el frontend

```sh
cd client
npm run dev
```

La app estará disponible en `http://localhost:5173` (o el puerto que configures).

## Scripts útiles

### Frontend

- `npm run dev` - Inicia la app en modo desarrollo
- `npm run build` - Compila la app para producción
- `npm run lint` - Linting del código

## Licencia

MIT

---

Desarrollado por Kevin Agustin Ruiz
