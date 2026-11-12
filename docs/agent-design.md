# Diseño del Agente de IA

## 1. Objetivo

El objetivo de este agente es identificar oportunidades laborales del sector IT que coincidan con un perfil profesional determinado, automatizando el proceso de búsqueda, análisis y clasificación.

El prototipo fue diseñado y configurado utilizando ChatGPT, mediante instrucciones personalizadas y tareas programadas.

## 2. Perfil profesional de referencia

El agente utiliza como referencia un perfil que incluye:

- Técnico en Programación.
- Técnico Químico.
- Experiencia profesional en desarrollo de software.
- Conocimientos y experiencia en bases de datos, SQL, APIs, .NET, C# y tecnologías frontend.
- Formación en Ingeniería de Datos.
- Proyectos personales con Python, PostgreSQL, Docker, Kafka, Airflow y procesos ETL.

## 3. Puestos laborales objetivo

La búsqueda se divide en dos categorías principales.

**Ingeniería de Datos**
- Data Engineer Junior.
- Junior Data Engineer.
- Desarrollador ETL Junior.
- Posiciones relacionadas con datos de nivel inicial.

**Desarrollo de Software**
- Software Developer Semi Senior.
- Backend Developer.
- Full Stack Developer.
- Otros puestos relacionados con desarrollo de software.

## 4. Criterios de búsqueda

Cada oportunidad se analiza considerando:

- Experiencia profesional requerida.
- Conocimientos técnicos solicitados.
- Nivel de seniority.
- Ubicación geográfica.
- Modalidad de trabajo: remota, híbrida o presencial.
- Fecha de publicación.
- Información salarial, cuando está disponible.

## 5. Evaluación de compatibilidad

ChatGPT compara los requisitos de cada oferta laboral con el perfil profesional definido.

Cada oportunidad recibe un porcentaje estimado de compatibilidad entre 0 y 100%.

El análisis contempla:

- Conocimientos y habilidades coincidentes.
- Experiencia profesional relevante.
- Requisitos faltantes o no demostrados.
- Posibles áreas de mejora.

El porcentaje representa una estimación generada por IA y no una evaluación oficial de selección de personal.

## 6. Detección de publicaciones duplicadas

El agente utiliza el historial de búsquedas para identificar oportunidades repetidas mediante:

- URL de la publicación.
- Identificador de la oferta.
- Empresa y nombre del puesto.

Las oportunidades ya informadas se excluyen cuando es posible identificarlas de manera confiable.

## 7. Automatización y reportes

La búsqueda está configurada para ejecutarse diariamente mediante una automatización programada de ChatGPT.

El reporte organiza las oportunidades nuevas según su categoría y porcentaje de compatibilidad, incluyendo enlaces directos y datos relevantes.

## 8. Limitaciones

- Los resultados dependen de la información públicamente accesible.
- Algunas publicaciones pueden dejar de estar disponibles o modificarse.
- Los porcentajes de compatibilidad son estimaciones y requieren revisión humana.
- El prototipo depende de las funcionalidades de ChatGPT.
- No es una aplicación independiente ni dispone de un backend propio.

## 9. Enfoque de diseño

El agente fue diseñado a partir de una necesidad real, aplicando ingeniería de instrucciones (Prompt Engineering), criterios estructurados de búsqueda, análisis de información y automatización de tareas.

**Herramienta principal:** ChatGPT.
