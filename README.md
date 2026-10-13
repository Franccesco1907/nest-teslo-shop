# Teslo API

API NestJS/PostgreSQL de productos, autenticaci�n y WebSockets. Usa las versiones Node/npm de `package.json`.
1. Ejecuta `npm ci`, copia `.env.template` a `.env` y ajusta las variables (incluido `JWT_SECRET`).
2. Inicia PostgreSQL con `docker compose up -d` y la API con `npm run start:dev`.
3. Swagger: http://localhost:3000/api. Solo para datos de desarrollo, solicita `GET /api/seed` **despu�s de arrancar la API**: borra los productos y usuarios existentes.
Compilaci�n: `npm run build`; arranque compilado: `npm start`. `npm run test:e2e` requiere la base de datos; no hay archivos de pruebas unitarias en `src/`.
Cliente WebSocket: [ws-client](https://github.com/Franccesco1907/ws-client).
