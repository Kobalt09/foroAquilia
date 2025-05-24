# Foro API

API REST para el sistema de foro.

## Requisitos

- Node.js >= 18.0.0
- npm

## Instalación

1. Clonar el repositorio
2. Instalar dependencias:
```bash
npm install
```

## Desarrollo

Para ejecutar el servidor en modo desarrollo:
```bash
npm run dev
```

## Producción

Para ejecutar el servidor en modo producción:
```bash
npm start
```

## Despliegue en Render

1. Crear una cuenta en [Render](https://render.com)
2. Crear un nuevo Web Service
3. Conectar con tu repositorio de GitHub
4. Configurar el servicio:
   - Build Command: `npm install`
   - Start Command: `npm start`
   - Node Version: 18.x o superior

## Endpoints de la API

- GET `/api/status` - Verificar estado del servidor
- GET `/api/users` - Obtener usuarios
- POST `/api/users` - Guardar usuarios
- GET `/api/posts` - Obtener todos los posts
- GET `/api/posts/:id` - Obtener un post específico
- POST `/api/posts` - Crear un nuevo post
- GET `/api/comments/:postId` - Obtener comentarios de un post
- POST `/api/comments` - Crear un nuevo comentario 