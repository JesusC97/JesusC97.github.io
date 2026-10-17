# Test de oposiciones

Aplicación web para practicar preguntas tipo test desde el móvil. Funciona en el navegador y se puede añadir a la pantalla de inicio del iPhone o Android. No necesita servidor ni cuenta: todo se guarda en el propio dispositivo.

**Versión:** actualizada el 17/10/2026 a las 21:20 (hora de España). Esa fecha y hora aparecen en la pantalla de inicio de la app, así puedes comprobar qué versión estás usando.

## Qué permite

- **Importar un examen con dos PDF:** el de preguntas y el de plantilla de respuestas. La app une ambos por número de pregunta y muestra una pantalla de revisión antes de guardar.
- **Importar o exportar un JSON** con preguntas, para reutilizar copias o cargar baterías preparadas en el ordenador.
- **Sesiones de práctica:** cada sesión tiene su propio nombre, filtro (convocatoria, tema, solo preguntas revisadas) y estadísticas. Puedes practicar en orden o mezclado, y repasar solo las falladas.
- **Edición en cualquier momento:** enunciado, opciones, respuesta correcta y creación de preguntas nuevas.
- **Preguntas anuladas:** se guardan, pero no aparecen en la práctica. Se marcan en la revisión o en el editor.
- **Pantalla de resultados** con porcentaje, desglose por tema y repaso de falladas.

## Cómo usarla

1. Abre la dirección de la app en Safari (iPhone) o Chrome (Android).
2. Ve a **Datos** e importa el examen (dos PDF) o un JSON de preguntas. Solo hace falta una vez por dispositivo.
3. Revisa la pantalla de confirmación: número de preguntas, respuestas sin marcar y avisos. Marca las anuladas si las hay.
4. Pulsa **Añadir** o **Reemplazar** para guardar.
5. Ve a **Comenzar**, crea una sesión y empieza a practicar.
6. Para añadir la app a la pantalla de inicio, pulsa compartir y elige **Añadir a pantalla de inicio**.

## Antes de subir el repositorio

- **No subas PDF ni JSON de exámenes** si el repositorio es público. El repositorio solo debe contener la aplicación (`index.html`) y este README.
- Los datos se guardan en el dispositivo, así que si cambias de móvil o de navegador tendrás que volver a importar. Usa **Datos → Exportar copia** para hacer copias de seguridad.

## Limitaciones conocidas

- La lectura de PDF depende de su formato. Funciona con el formato de estos exámenes (preguntas numeradas, opciones a), b), c), d) y plantilla en tabla), pero otros formatos pueden necesitar revisión manual o un JSON.
- Si un PDF es una imagen escaneada, no se puede leer directamente.
- Los avisos de la pantalla de revisión indican qué números revisar. Las preguntas sin respuesta se pueden corregir en el editor.

## Estructura del repositorio

```
index.html   ← la aplicación
README.md    ← este archivo
```

