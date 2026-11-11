# SHINE UP S.A.S. - Ingeniería Financiera

## Contenido
- `index.html`: aplicación web y módulos financieros.
- `api/assistant.js`: endpoint opcional para conectar el asistente con OpenAI.
- `vercel.json`: configuración de despliegue.
- `package.json`: configuración del proyecto.

## Publicación en Vercel
1. Sube el contenido de esta carpeta a un repositorio GitHub.
2. En Vercel selecciona Add New > Project e importa el repositorio.
3. Mantén la configuración predeterminada y pulsa Deploy.
4. Para activar el asistente IA, configura `OPENAI_API_KEY` en Project Settings > Environment Variables. Opcionalmente configura `OPENAI_MODEL` con un modelo disponible en tu cuenta de API.
5. Vuelve a desplegar después de guardar las variables.

La aplicación puede funcionar sin configurar la IA; el asistente mostrará respuestas locales básicas.

## Nota
Prototipo inicial. Verifica los resultados y supuestos antes de usarlo en decisiones financieras reales. La TIR por bisección puede no encontrar todas las raíces en flujos no convencionales.
