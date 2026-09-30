# Política de Privacidad — Levit (beta)

**Última actualización:** 30 de septiembre de 2026

Resumen: **Levit no recopila datos personales ni envía telemetría.**

## 1. Qué procesa el Software

- **Servidor local:** escucha únicamente en `127.0.0.1` (tu propia máquina).
  No abre puertos hacia la red local ni a internet.
- **Datos almacenados localmente** en
  `~/Library/Application Support/Levit/`:
  - `config.json` — preferencias (puerto, API keys generadas por ti).
  - `usage.json` — contadores locales de uso (solicitudes y tokens).
  - `serve.log` — registro técnico del backend.
- **Nada de esto sale de tu Mac** salvo la petición de inferencia que tú mismo
  envías con tus apps.

## 2. Servicios de terceros

Cuando usas el Software, el texto de tus conversaciones se envía al proveedor
de los modelos de IA que estés utilizando (a través de la CLI/servicios de
opencode) para que generen la respuesta. Ese envío ocurre **porque tú lo
solicitaste desde tu app**; está sujeto a los términos y políticas de ese
proveedor. Levit no añade ningún destino adicional.

## 3. Qué NO hacemos

- No recopilamos nombre, correo, IP ni ningún otro dato personal.
- No hay analytics, telemetría, cookies ni píxeles de seguimiento.
- No vendemos ni compartimos datos (no tenemos datos que compartir).
- No accedemos al contenido de tus conversaciones desde ningún servidor
  propio: no existe servidor propio.

## 4. Seguridad

- El servidor solo acepta conexiones de `127.0.0.1`.
- Puedes exigir API key en cada petición (por defecto, en modo local se admite
  sin clave para comodidad; puedes desactivarlo en el menú).
- Las API keys se guardan en texto plano **solo en tu Mac**; protege tu cuenta
  de usuario (cifrado FileVault, contraseña).

## 5. Tus derechos

Al no existir recolección de datos, no hay base de datos personal que
solicitar. Si tienes preguntas, abre una issue en el repositorio de descargas.

## 6. Cambios

Cualquier cambio futuro de esta política se publicará en este archivo con fecha
actualizada, y se anunciará en el repositorio de descargas.
