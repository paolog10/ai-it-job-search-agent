# Flujo de Funcionamiento del Agente

## 1. Inicio de la búsqueda

El agente ejecuta una búsqueda programada diariamente mediante las funcionalidades de ChatGPT.

Utiliza un perfil profesional y criterios de búsqueda previamente definidos.

## 2. Identificación de oportunidades

ChatGPT consulta diferentes fuentes de empleo, entre ellas:

- LinkedIn Jobs.
- Indeed.
- Computrabajo.
- Bumeran.
- ZonaJobs.
- Get on Board.
- Sitios oficiales de empresas.

Se priorizan publicaciones recientes y oportunidades que cumplan con las condiciones establecidas.

## 3. Clasificación de ofertas

Las oportunidades identificadas se separan en dos grupos:

- Ingeniería de Datos Junior y puestos relacionados.
- Desarrollo de Software Semi Senior.

## 4. Análisis de compatibilidad

Cada publicación se compara con el perfil profesional de referencia.

Se consideran los conocimientos técnicos, la experiencia, el nivel solicitado, la ubicación y la modalidad de trabajo.

ChatGPT genera una estimación de compatibilidad y señala fortalezas y posibles brechas.

## 5. Control de duplicados

Antes de preparar el reporte, se revisan las oportunidades para evitar informar nuevamente publicaciones que ya fueron comunicadas.

Se consideran identificadores, enlaces y datos de empresa y puesto.

## 6. Generación del reporte

Las oportunidades se ordenan según su compatibilidad y se presentan con la siguiente información:

- Empresa.
- Nombre del puesto.
- Fecha de publicación.
- Modalidad de trabajo.
- Ubicación.
- Compatibilidad estimada.
- Requisitos principales.
- Fortalezas y brechas detectadas.
- Salario, si está publicado.
- Enlace a la publicación original.

## 7. Entrega del resultado

El proceso está configurado para ejecutarse diariamente a las 08:00 (hora de Argentina).

El objetivo es disponer de un resumen organizado de las nuevas oportunidades laborales identificadas.

## 8. Supervisión humana

El agente funciona como asistente de búsqueda y análisis.

La decisión de postularse, evaluar las condiciones laborales y enviar el currículum queda siempre a cargo de la persona.

El agente no realiza postulaciones ni contacta empresas o reclutadores.

---

**Nota:** Este flujo describe la configuración del prototipo implementado con ChatGPT. No representa una arquitectura de software independiente.
