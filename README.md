🏠 Análisis de Rendimiento y Regulaciones de Airbnb: París 🇫🇷
📊 Contexto del Proyecto
Como Analista de Rendimiento en Airbnb, se me ha asignado la tarea de evaluar el mercado de anuncios en París. El crecimiento de la plataforma ha generado nuevas normativas municipales (especialmente en 2015) para limitar el número de propiedades turísticas.

El objetivo central: Entender los factores que afectan a los precios y determinar si las regulaciones de 2015 tuvieron un impacto real en la oferta de anuncios en el mercado parisino.

🎯 Objetivos Principales
Perfil y Control de Calidad: Limpieza profunda de un dataset con más de 24,000 registros.

Preparación de Datos: Segmentación geográfica y transformación temporal para análisis de series de tiempo.

Análisis de Hallazgos: Visualizar la evolución del mercado y la distribución de precios por barrios.

🛠️ Metodología (Paso a Paso)
1. Perfilado de Datos y Limpieza
Gestión de Encodings: Se utilizó ISO-8859-1 para procesar correctamente caracteres especiales del idioma francés.

Tipado de Datos: Conversión de la columna host_since a formato datetime para habilitar el análisis cronológico.

Control de Calidad: Se detectaron y descartaron columnas con 0% de información (como tasas de respuesta del anfitrión en este set).

2. Segmentación del Mercado (París)
Se filtró el dataset global para crear un subconjunto específico de París, reduciendo el ruido y enfocando el análisis en 14,881 listados activos. Se seleccionaron variables críticas: neighbourhood, accommodates, price y host_since.

3. Análisis Estadístico y Hallazgos
Capacidad Media: El alojamiento promedio en París tiene capacidad para ~3 personas, indicando un mercado de apartamentos pequeños/estudios.

Precio Base: Se identificó un precio promedio de 93.64 €, con una alta desviación debido a alojamientos de lujo (outliers de hasta 6,700 €).

Efecto 2015: (Aquí puedes añadir si observaste que la curva de nuevos anfitriones se aplanó después de 2015 debido a las leyes locales).

📈 Resultados Clave
[!TIP] Resumen Ejecutivo:

París es un mercado de alta densidad con alojamientos compactos.

La calidad de los datos para la ciudad de París es del 100% en las variables críticas (0 nulos).

La distribución de precios sugiere una segmentación clara entre el mercado masivo (<100€) y el mercado de lujo.
