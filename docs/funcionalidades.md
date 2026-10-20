# Funcionalidades de Mi Experiencia ACV

> Derivadas de la visión de producto y de los casos de uso CU-01 a CU-10. Organizadas en tres áreas:
>
> - **Input:** lo que la persona aporta, configura o comparte.
> - **Output:** lo que el sistema le entrega para entender, decidir y acompañar.
> - **Estado:** lo que el sistema conserva y devuelve como contexto: etapa, progreso, permisos, historial y pendientes.

---

## 1. Input

### Contexto y búsqueda

- **El usuario puede** declarar su vínculo con la persona afectada y el momento del proceso en que se encuentra (sospecha, diagnóstico reciente, hospitalización, vuelta a casa, rehabilitación, largo plazo).
- **El usuario puede** indicar su país y ciudad para recibir teléfonos, centros y trámites locales.
- **El usuario puede** buscar con lenguaje cotidiano ("no puede hablar", "se le durmió la cara") además de términos médicos.
- **El usuario puede** registrar la hora de inicio de los síntomas y los datos básicos para una emergencia.
- **El usuario puede** guardar preguntas para el equipo médico y anotar las respuestas.

### Historia y memoria

- **El usuario puede** crear un espacio privado para la persona y su familia.
- **El usuario puede** escribir momentos, capítulos e hitos con fecha, categoría y estado de ánimo.
- **El usuario puede** adjuntar fotos, audios, videos y documentos, o grabar un audio en lugar de escribir.
- **El usuario puede** guardar borradores y editarlos cuando tenga tiempo.

### Círculo y privacidad

- **El usuario puede** invitar a familiares y amistades con distintos roles y permisos.
- **El usuario puede** decidir la visibilidad de cada contenido y crear enlaces temporales.
- **El usuario puede** otorgar o revocar el consentimiento de la persona protagonista y elegir un alias.
- **El usuario puede** pedir ayuda concreta, comentar y reaccionar dentro de su círculo.

### Comunidad y preferencias

- **El usuario puede** publicar su historia en la comunidad, guardar recursos y reportar contenido.
- **El usuario puede** configurar notificaciones, accesibilidad e idioma, y solicitar la eliminación o exportación de sus datos.

---

## 2. Output

### Urgencia y comprensión

- **El sistema permite** ver señales de alarma y qué hacer en los primeros minutos, con un botón para llamar a emergencias.
- **El sistema permite** entender qué es un ACV, sus tipos y los términos médicos en lenguaje claro, con audio y letra grande.
- **El sistema permite** obtener preguntas sugeridas para hacerle al equipo médico.
- **El sistema permite** ver la fuente, el autor clínico y la fecha de revisión de cada contenido.

### Cuidado y acompañamiento

- **El sistema permite** seguir checklists de hospitalización y de vuelta a casa.
- **El sistema permite** reconocer señales de alarma y saber cuándo consultar.
- **El sistema permite** acceder a guías de rehabilitación por etapa y entender el rol de la familia.
- **El sistema permite** acceder a recursos de cuidado emocional, señales de agotamiento y líneas de crisis.
- **El sistema permite** encontrar recursos locales: teléfonos, centros, trámites y derechos.
- **El sistema permite** recibir un resumen semanal y notificaciones de lo que pasa en el espacio.

### Comunidad y memoria

- **El sistema permite** explorar historias públicas por etapa, vínculo y tema, con avisos de contenido sensible.
- **El sistema permite** ver la línea de tiempo, los hitos y la historia completa en capítulos.
- **El sistema permite** exportar un PDF tipo libro y descargar todos los datos y medios.
- **El sistema permite** usar plantillas para escribir una actualización breve a la familia.

---

## 3. Estado

### Estado del proceso

- **El sistema permite** consultar en qué etapa del proceso está la familia y qué viene después.
- **El sistema permite** ver el progreso de las checklists y las preguntas que quedan pendientes.
- **El sistema permite** ver los hitos y avances registrados en la línea de tiempo.
- **El sistema permite** ver la evolución del estado de ánimo registrado, siempre en privado.

### Estado del contenido

- **El sistema permite** ver si un contenido es borrador, publicado o archivado, y consultar su historial de versiones.
- **El sistema permite** saber si un contenido clínico o legal está desactualizado por su fecha de revisión.
- **El sistema permite** ver los recursos guardados y los que quedaron pendientes.

### Estado del acceso

- **El sistema permite** ver el estado de las invitaciones (pendiente, aceptada, vencida) y quién tiene acceso.
- **El sistema permite** ver el estado del consentimiento (otorgado, pendiente, revocado).
- **El sistema permite** ver el estado de los enlaces compartidos (activo, vencido, revocado).
- **El sistema permite** ver las sesiones activas y el estado de privacidad de la cuenta.

### Estado de la actividad

- **El sistema permite** ver el estado de una exportación (en proceso, lista, vencida).
- **El sistema permite** ver el estado de un reporte o de una historia enviada a la comunidad (en revisión, publicada, oculta).
- **El sistema permite** ver las notificaciones no leídas y el historial de actividad.
- **El sistema permite** ver un resumen del espacio: últimos momentos, próximos pasos y necesidades abiertas.

---

## Criterio de diseño

Cada funcionalidad debe **reducir una pregunta de angustia**, no agregar una tarea. Si una función no ayuda a entender, actuar, cuidar, compartir o recordar, queda fuera de este alcance.

**Fuera de alcance:** diagnóstico, prescripción, interpretación de exámenes e historia clínica.
