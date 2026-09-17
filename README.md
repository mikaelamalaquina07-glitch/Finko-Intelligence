# Finko-Intelligence
Sistema inteligente para analizar el rendimiento de propiedades publicadas en Instagram

## Variables de entorno

Copia `.env.example` como `.env` y completa la clave publishable de Supabase. En Vercel configura estas mismas variables en el proyecto:

- `SUPABASE_URL`
- `SUPABASE_PUBLISHABLE_KEY`

La aplicación consulta Supabase desde `/api/propiedades`, por lo que las credenciales no quedan expuestas en el HTML.
