# Proyecto: Automatización del Análisis de Tendencias de Videos en YouTube

## Descripción del Proyecto

Este proyecto tiene como objetivo automatizar el proceso de análisis de tendencias de videos en YouTube para la agencia de publicidad Sterling & Draper. El análisis se enfoca en identificar las categorías de videos que estuvieron en tendencia en diferentes regiones, con un énfasis especial en los Estados Unidos.

## Proceso de Trabajo

### Parte 1: Reunir Requisitos Técnicos

- **Objetivo de Negocio**: Analizar el historial de tendencias de videos en YouTube para mejorar la planificación de videos publicitarios.
- **Frecuencia de Uso**: Al menos una vez al día.
- **Usuario Objetivo**: Gerentes de planificación de videos publicitarios.
- **Datos Utilizados**: Datos históricos de tendencias de videos, clasificados por día, categoría y región.
- **Fuentes de Datos**: 
  - La tabla `trending_by_time` de la base de datos `youtube`, actualizada cada 24 horas.
  - Estructura de la tabla:
    - `record_id`: Clave primaria.
    - `region`: País/región geográfica.
    - `trending_date`: Fecha y hora.
    - `category_title`: Categoría del video.
    - `videos_count`: Número de videos en la sección de tendencias.

### Parte 2: Creación del Dashboard

1. **Diseño del Dashboard**:
   - Utilicé `Tableau Public` para crear un dashboard interactivo basado en la tabla `trending_by_time.csv`.
   - El dashboard permite filtrar por fecha/hora y región, afectando todos los gráficos.
   - Incluí gráficos que muestran:
     - El historial de tendencias en números absolutos.
     - El historial de tendencias en porcentajes.
     - Una tabla de correspondencia entre categorías y países.

2. **Publicación del Dashboard**:
   - El dashboard fue publicado en Tableau Public y verificado en varios navegadores para asegurar su accesibilidad.

3. **Análisis de Preguntas Clave**:
   - **Preguntas Respondidas**:
     - ¿Qué categorías de videos estuvieron en tendencia más frecuentemente?
     - ¿Cómo se distribuyeron en las regiones?
     - ¿Qué categorías fueron particularmente populares en los Estados Unidos? ¿Hubo diferencias entre las categorías populares en Estados Unidos y en otras regiones?
   - **Métodos**:
     - Utilicé el dashboard para extraer las respuestas y visualizarlas gráficamente.

## Entregables

- **Datos**: Archivo `trending_by_time.csv` con los datos cargados en el dashboard.
- **Dashboard**: Enlace al dashboard en Tableau Public.
- **Presentación**: PDF con un informe breve que incluye respuestas a las preguntas clave y gráficos del análisis.

---

Este proyecto automatiza el análisis de tendencias, permitiendo a los gerentes de planificación tomar decisiones basadas en datos actualizados y bien organizados.
