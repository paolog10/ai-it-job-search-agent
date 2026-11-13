# Flujo de Funcionamiento del Agente

## 1. Inicio de la búsqueda

El agente ejecuta una búsqueda programada diariamente mediante las funcionalidades de ChatGPT.

La automatización está configurada para ejecutarse a las **05:00 (hora de Argentina)**, utilizando la zona horaria `America/Argentina/Cordoba`.

Utiliza un perfil profesional y criterios de búsqueda previamente definidos.

## 2. Identificación de oportunidades

ChatGPT consulta diferentes fuentes de empleo, entre ellas:

- LinkedIn Jobs.
- Indeed.
- Computrabajo.
- Bumeran.
- ZonaJobs.
- Get on Board.
- Wellfound.
- Sitios oficiales de empresas.
- Otros portales laborales relevantes.

Se priorizan publicaciones realizadas dentro de los últimos 15 días, verificando que las oportunidades continúen activas.

Siempre que sea posible, se consulta la publicación original para verificar sus requisitos, fecha y condiciones.

## 3. Clasificación de ofertas

Las oportunidades identificadas se separan en dos grupos:

- **Ingeniería de Datos Junior y puestos relacionados:** Data Engineer Junior, ETL/ELT, Python, SQL, integración y procesamiento de datos, entre otros.
- **Desarrollo de Software Semi Senior:** .NET, C#, React, Backend, Frontend, Full Stack y desarrollo de APIs.

Cada oportunidad se clasifica según su correspondencia con el perfil profesional.

## 4. Análisis de compatibilidad

Cada publicación se compara con el perfil profesional de referencia.

Se consideran:

- Conocimientos técnicos y herramientas solicitadas.
- Experiencia profesional requerida.
- Formación académica.
- Seniority.
- Ubicación y modalidad de trabajo.
- Elegibilidad geográfica.
- Nivel de inglés requerido.

ChatGPT genera una estimación de compatibilidad entre 0 y 100 %, señalando las fortalezas y posibles brechas.

Los proyectos personales y la formación en Ingeniería de Datos se consideran experiencia práctica y formativa, sin atribuirles carácter de experiencia laboral profesional.

## 5. Control de duplicados y vigencia

Antes de preparar el reporte, se revisan las oportunidades para evitar informar nuevamente publicaciones que ya fueron comunicadas.

Se utilizan identificadores, enlaces y datos de empresa y puesto para detectar duplicados.

Cuando una misma oferta aparece en diferentes portales, se considera una única oportunidad y se prioriza el enlace original.

También se verifica que las publicaciones estén activas y que su antigüedad cumpla con el límite de 15 días.

El historial de oportunidades notificadas se utiliza para evitar repeticiones en futuras ejecuciones.

## 6. Generación del reporte

Las oportunidades se ordenan de mayor a menor compatibilidad y se presentan en dos secciones:

- Ingeniería de Datos Junior y puestos relacionados.
- Desarrollo de Software Semi Senior.

Para cada oportunidad se incluye:

- Empresa.
- Nombre del puesto.
- Categoría profesional.
- Fecha de publicación.
- Modalidad de trabajo.
- Ubicación y elegibilidad geográfica.
- Compatibilidad estimada.
- Requisitos principales.
- Fortalezas y brechas detectadas.
- Salario, si está publicado.
- Enlace directo a la publicación.

Cuando no se informa el salario, se indica: "Salario no informado".

Los datos que no pudieron verificarse se identifican expresamente.

## 7. Entrega del resultado

El proceso está configurado para ejecutarse diariamente a las **05:00 (hora de Argentina)**.

El agente prepara y envía un único correo electrónico diario a `paologamarra10@gmail.com`.

El asunto del correo sigue el formato:

`Oportunidades laborales IT – [fecha local]`

El reporte reúne las oportunidades nuevas identificadas durante la búsqueda, organizadas por categoría y compatibilidad.

Si no se encuentran ofertas nuevas verificadas que cumplan los criterios, también se envía un correo breve informando que no hubo novedades relevantes.

El historial de oportunidades notificadas debe actualizarse después del envío exitoso para evitar repeticiones.

## 8. Supervisión humana

El agente funciona como asistente de búsqueda y análisis.

La decisión de postularse, evaluar las condiciones laborales y enviar el currículum queda siempre a cargo de la persona.

El agente no realiza postulaciones ni contacta empresas o reclutadores, tampoco modifica perfiles profesionales.

---

**Nota:** Este flujo describe el diseño y la configuración del prototipo implementado mediante ChatGPT y sus funcionalidades de automatización. No representa una arquitectura de software independiente ni una integración desarrollada mediante una API propia.
