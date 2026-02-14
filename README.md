# Análisis mercado automovilístico español

El sector automovilístico español está atravesando un proceso de transformación impulsado por la transición hacia energías alternativas, cambios regulatorios y medioambientales, evolución de la demanda del consumidor, envejecimiento del parque automovilístico, entre otras.

Empresas del sector como fabricantes, compañías de renting, aseguradoras y administraciones públicas necesitan comprender cómo evoluciona el mercado para tomar decisiones estratégicas.

Una empresa del sector movilidad desea responder a las siguientes preguntas estratégicas:

  - ¿Cómo ha evolucionado el volumen de matriculaciones en España en las últimas décadas?
  - ¿Qué tecnologías de combustible están ganando o perdiendo relevancia?
  - ¿Se está renovando el parque automovilístico a un ritmo suficiente?
  - ¿Qué implicaciones tiene esta evolución para el negocio del renting y la movilidad sostenible?

## Proceso de ánalisis de datos

Los datos utilizados provienen del Anuario Estadístico de la Dirección General de Tráfico (DGT), que recoge información histórica sobre matriculaciones de vehículos en España. Se han analizado datos desde 1990 hasta 2024.

### 1. Extracción y transformación de datos

Los datos originales estaban disponibles únicamente en formato PDF, por lo que se desarrolló un script en Python para:

  - Extraer tablas automáticamente del último anuario de la DGT
  - Limpiar inconsistencias estructurales
  - Estandarizar formatos numéricos
  - Consolidar la información en una base de datos analítica
  - Clasificar las matriculaciones por tipo de combustible

### 2. Análisis exploratorio

Se analizaron:

  - Tendencias históricas del mercado
  - Evolución del mix de combustibles
  - Cambios en la distribución por tipo de vehículo
  - Crecimiento de tecnologías electrificadas

Además, se desarrolló una estimación del parque automovilístico basada en matriculaciones acumuladas de los últimos 10 años para aproximar el ratio de renovación del parque.

### 3. Dashboard para la visualización de los datos

Se diseñó un dashboard en Power BI orientado a toma de decisiones, que incluye:

  - Evolución de matriculaciones
  - Cuota de mercado por combustible
  - Crecimiento de vehículos electrificados
  - Distribución por tipo de vehículo
  - Indicadores estratégicos como variación anual y ratio de renovación

## Conclusiones

### Evolución del mercado

El mercado automovilístico español ha mostrado una fuerte volatilidad en las últimas décadas, con:
  
  - Crecimiento sostenido hasta mediados de los 2000
  - Impacto significativo de la crisis financiera
  - Recuperación progresiva posterior
  - Descenso reciente asociado a incertidumbre económica y transición energética

### Transición energética

Se observa un cambio estructural en el mix de combustibles:

  - Reducción progresiva del peso del diésel
  - Estabilización y posterior descenso de la gasolina
  - Crecimiento sostenido de tecnologías electrificadas
  - Esto refleja un cambio en el comportamiento del consumidor y la presión regulatoria hacia movilidad sostenible.

### Renovación del parque automovilístico

El ratio estimado de renovación muestra una desaceleración en los últimos años, lo que sugiere:
  
  - Mayor envejecimiento del parque
  - Potencial aumento en costes de mantenimiento
  - Oportunidades de crecimiento para modelos de renting y suscripción

### Implicaciones estratégicas

Este análisis sugiere que:

  - Existe una clara oportunidad de crecimiento en vehículos electrificados
  - El envejecimiento del parque puede impulsar soluciones de movilidad flexible
  - Las empresas del sector deben adaptarse a un mercado cada vez más orientado a sostenibilidad


