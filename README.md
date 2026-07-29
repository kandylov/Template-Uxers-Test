# Template-Uxers-Test

Genera fichas de testeo editables (secciones de preguntas + encuesta de satisfacción tipo CSAT) y las exporta a PDF, una por cada entrevistado.

## Cómo se usa

1. En la primera hoja se arma la **plantilla**: título, secciones de preguntas y encuesta de satisfacción.
2. Con **"+ Nuevo entrevistado"** se clona esa estructura en blanco para cada persona testeada.
3. Cada quien completa nombre, perfil, observaciones y selecciona las caritas de la encuesta.
4. **"Exportar a PDF"** abre el diálogo de impresión del navegador (Ctrl/Cmd + P → Guardar como PDF).
5. Importante: activar la opción **"Gráficos de fondo"** para que se respeten los colores.

## Notas técnicas
- Es un único archivo HTML/CSS/JS, sin backend ni dependencias externas (salvo las tipografías de Google Fonts).
- No guarda datos entre sesiones: hay que exportar a PDF antes de cerrar o recargar la página.
