# FRUTIMIA 🍓

Tienda web adaptable para FRUTIMIA. Catálogo sin precios públicos, pedidos para recoger, cuentas de clientes, puntos, recompensas, opiniones, chat y panel de administración.

## Backend
Esta versión utiliza **Supabase** (Auth + PostgreSQL + Row Level Security). Ya no requiere Firebase.

## Configuración
1. Sigue `LEEME_SUPABASE.txt`.
2. Pega Project URL, anon/public key y correo administrador en `js/supabase-config.js`.
3. Ejecuta `supabase/schema.sql` completo en el SQL Editor de tu proyecto Supabase.
4. Abre `index.html` con Live Server.

**Nunca pongas la clave `service_role` en el navegador.**
