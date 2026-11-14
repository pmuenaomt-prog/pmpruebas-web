# Reglas del proyecto — pmpruebas-web (pruebas con Supabase)

Responder siempre en español, en lenguaje simple.

## Qué es
- Página de práctica que muestra la tabla `maquinas` del proyecto Supabase `pmpruebas`.
- Publicada en Vercel (sin build); cada cambio en `main` se publica solo.

## Reglas
- Solo usar la clave PUBLICABLE (`sb_publishable_...`). Nunca poner la clave secreta
  (`sb_secret_...` / service_role) en el código: este repositorio es PÚBLICO.
- Toda tabla nueva en Supabase debe tener RLS activado con sus políticas.
- Después de cambios en la base de datos, revisar los avisos de seguridad de Supabase.
- Es un proyecto de pruebas: no guardar aquí datos reales de OMAMET.
