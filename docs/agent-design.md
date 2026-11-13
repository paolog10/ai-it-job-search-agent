# Diseño del Agente de IA

## 1. Objetivo

El objetivo de este agente es identificar oportunidades laborales del sector IT que coincidan con un perfil profesional determinado, automatizando el proceso de búsqueda, análisis, evaluación y clasificación.

El prototipo fue diseñado y configurado utilizando ChatGPT, mediante instrucciones personalizadas, búsquedas web y tareas programadas.

Su propósito es reducir el trabajo manual de búsqueda laboral y facilitar la identificación de oportunidades relevantes.

## 2. Perfil profesional de referencia

El agente utiliza como referencia un perfil que incluye:

### Formación académica

- Técnico Universitario en Programación.
- Técnico Universitario en Química.
- Diplomatura en Programación Web Full Stack.
- Formación complementaria en Ingeniería de Datos.

### Experiencia profesional

- Desarrollo frontend para plataformas de comercio electrónico utilizando React JS.
- Consumo de APIs REST y mantenimiento de aplicaciones web.
- Trabajo con bases de datos relacionales y SQL Server.
- Desarrollo y optimización de procedimientos SQL.
- Experiencia en entornos de trabajo remotos y equipos de desarrollo.

### Conocimientos técnicos

- React JS y JavaScript.
- HTML y CSS.
- C# y .NET.
- APIs REST.
- SQL Server y PostgreSQL.
- Git y GitHub.
- Postman.
- Power BI.
- Python.

### Formación y proyectos personales

Experiencia práctica y formativa mediante proyectos relacionados con:

- Ingeniería de Datos.
- Procesos ETL/ELT.
- Docker.
- Apache Kafka.
- Apache Airflow.
- Data Warehousing.
- Procesamiento y streaming de datos.

Los proyectos personales de Ingeniería de Datos no se consideran experiencia laboral profesional en esa especialidad.

También se contempla la experiencia previa en entornos industriales, producción, calidad y laboratorio cuando resulte relevante para una oportunidad laboral.

El nivel de inglés se considera básico, con capacidad de lectura y comprensión de documentación técnica.

## 3. Puestos laborales objetivo

La búsqueda se divide en dos categorías principales.

### Ingeniería de Datos y posiciones relacionadas

- Data Engineer Junior.
- Junior Data Engineer.
- ETL Developer.
- ELT Developer.
- Python Developer orientado a datos.
- SQL Developer.
- Data Integration Developer.
- Data Warehouse Developer.
- Posiciones relacionadas con bases de datos y procesamiento de datos.
- Analista SQL o BI cuando exista correspondencia razonable con el perfil.

### Desarrollo de Software

- Software Developer Semi Senior.
- .NET Developer.
- C# Developer.
- Backend Developer.
- Frontend Developer.
- Full Stack Developer.
- Desarrollador de aplicaciones y APIs.

Para desarrollo de software se priorizan posiciones que soliciten aproximadamente entre 3 y 5 años de experiencia profesional, evaluando los requisitos específicos de cada publicación.

## 4. Criterios de búsqueda

Cada oportunidad se analiza considerando:

- Experiencia profesional requerida.
- Conocimientos técnicos solicitados.
- Nivel de seniority.
- Formación académica.
- Ubicación geográfica.
- Modalidad de trabajo: remota, híbrida o presencial.
- Elegibilidad para trabajar desde Argentina.
- Fecha de publicación.
- Vigencia de la oferta.
- Información salarial, cuando está disponible.

Se consideran oportunidades publicadas dentro de los últimos 15 días.

### Criterios geográficos

- San Francisco, Córdoba, y localidades cercanas: se aceptan oportunidades presenciales, híbridas o remotas.
- Otras localidades de Argentina: únicamente posiciones 100 % remotas que permitan trabajar desde cualquier provincia.
- Ofertas internacionales: únicamente cuando permitan contratar personas residentes en Argentina.

No se considera suficiente que una publicación indique simplemente modalidad remota: debe verificarse la elegibilidad geográfica.

## 5. Evaluación de compatibilidad

ChatGPT compara los requisitos de cada oferta laboral con el perfil profesional definido.

Cada oportunidad recibe un porcentaje estimado de compatibilidad entre 0 y 100 %.

El análisis contempla:

- Conocimientos y habilidades coincidentes.
- Experiencia profesional relevante.
- Formación académica.
- Tecnologías y herramientas solicitadas.
- Seniority requerido.
- Modalidad y ubicación.
- Nivel de inglés.
- Requisitos faltantes o no demostrados.
- Posibles áreas de mejora.

Cada evaluación debe incluir una explicación breve de las fortalezas y brechas detectadas.

El porcentaje representa una estimación generada por IA y no una evaluación oficial de selección de personal.

## 6. Detección de publicaciones duplicadas

El agente utiliza el historial de oportunidades notificadas para identificar publicaciones repetidas mediante:

- URL de la publicación.
- Identificador de la oferta.
- Empresa y nombre del puesto.

Las oportunidades ya informadas se excluyen cuando es posible identificarlas de manera confiable.

Si una misma publicación aparece en diferentes portales, se considera una única oportunidad y se prioriza el enlace original.

El historial debe actualizarse después del envío exitoso del reporte para evitar repeticiones en futuras búsquedas.

## 7. Automatización y reportes

La búsqueda está configurada para ejecutarse diariamente a las **05:00**, utilizando la zona horaria `America/Argentina/Cordoba`.

El agente prepara un único correo electrónico diario dirigido a `paologamarra10@gmail.com`.

El reporte incluye dos categorías:

1. Ingeniería de Datos Junior y puestos relacionados.
2. Desarrollo de Software Semi Senior.

Las oportunidades se ordenan según su porcentaje de compatibilidad e incluyen:

- Empresa y puesto.
- Categoría profesional.
- Fecha de publicación.
- Ubicación y modalidad.
- Elegibilidad geográfica.
- Compatibilidad estimada.
- Fortalezas y brechas.
- Salario, si está publicado.
- Enlace directo a la oferta.

Si no se encuentran nuevas oportunidades verificadas que cumplan los criterios, se envía igualmente un correo breve informando que no hubo novedades relevantes.

El objetivo es recibir un único resumen diario, evitando múltiples notificaciones y publicaciones repetidas.

## 8. Limitaciones

- Los resultados dependen de la información públicamente accesible.
- Algunas publicaciones pueden dejar de estar disponibles o modificarse.
- No todas las empresas informan fechas o salarios.
- La elegibilidad geográfica puede no estar claramente especificada.
- Los porcentajes de compatibilidad son estimaciones y requieren revisión humana.
- El control de duplicados depende de la disponibilidad y persistencia del historial.
- El prototipo depende de las funcionalidades de ChatGPT y de los servicios utilizados para la búsqueda y entrega de reportes.
- No es una aplicación independiente ni dispone de un backend propio.

## 9. Enfoque de diseño

El agente fue diseñado a partir de una necesidad real: automatizar y mejorar la búsqueda personal de oportunidades laborales.

Para ello se aplicaron conceptos de:

- Ingeniería de instrucciones (Prompt Engineering).
- Definición de perfiles y criterios de búsqueda.
- Clasificación de información.
- Evaluación de compatibilidad.
- Validación de publicaciones.
- Detección de duplicados.
- Automatización de tareas.
- Organización y entrega de reportes.

**Herramienta principal:** ChatGPT.

**Repositorio:** documentación del diseño, instrucciones y funcionamiento del prototipo de agente de búsqueda laboral IT.
