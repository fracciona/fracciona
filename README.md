FRACCIONA - Proyecto Esqueleto

Instrucciones rápidas:

1. Levantar local con Docker:
   docker-compose up --build

2. Inicializar prisma y seed:
   cd backend
   npm ci
   npx prisma generate
   npm run prisma:seed

3. Frontend:
   cd frontend
   npm ci
   npm run dev

Default admin:
  email: admin@fracciona.local
  password: Admin!12345

Cambia contraseñas y JWT_SECRET antes de producción.
