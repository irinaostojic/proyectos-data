# ✈️ Proyecto Python/Análisis de Datos: Programa de Lealtad de Aerolínea, por Irina Ostojic
## 👩‍💻 Sobre mí

¡Hola! Soy Irina Ostojic, estudiante del Bootcamp de Data Analytics en Adalab. Esta es mi tercera evaluación del Módulo 3, centrado en el tratamiento de datos a través de Python, usando Pandas, y aplicando visualización y estadística.

Me encanta analizar datos para encontrar patrones, insights y contar historias a partir de ellos. Disfruto depurando datos, creando visualizaciones claras y aplicando pruebas estadísticas para entender mejor los comportamientos de los datos.

📧 Contacto: irinaostojicnieto@gmail.com

# 📁 Descripción y objetivos del proyecto

El proyecto analiza el comportamiento de clientes de un programa de lealtad de una aerolínea, utilizando dos conjuntos de datos:

- Customer Flight Analysis.csv – Información mensual de vuelos reservados, distancias voladas, puntos acumulados y canjeados, y costos asociados a los puntos.
- Customer Loyalty History.csv – Información personal y de perfil de los clientes: país, provincia, ciudad, género, nivel educativo, salario, tipo de tarjeta, valor de vida del cliente, fechas de inscripción y cancelación.

## 🧰 Librerias utilizadas
Las principales librerias que hemos utilizado en el desarrollo del proyecto son:
* `Pandas`: para la manipulación de datos y DataFrames
* `Numpy`: para realizar operaciones numéricas y arrays
* `Sklearn`: para la imputación de nulos con técnicas como Iterative Imputer o KNNImputer
* `Matplotlib`: para la creación de gráficos básicos
* `Seaborn`: para la creación gráficos más estilizados
* `Scipy.stats`: para pruebas de estadística inferencial

# 🎯 Objetivos y estructura del proyecto

El proyecto se ha desarrollado en tres notebooks diferentes, cada uno centrado en una fase del análisis:

1️⃣ Fase 1: Exploración y limpieza (`FASE1_exploracion-limpieza_irina-ostojic.ipynb`)
- Exploración inicial de los datasets: identificación de nulos, valores atípicos y estructura general de los datasets.
- Unión de ambos datasets mediante Loyalty Number.
- Limpieza de datos: manejo de nulos, conversión de tipos y revisión de consistencia de columnas.

2️⃣ Fase 2: Visualización (`FASE2_visualizacion_irina-ostojic.ipynb`)
Las preguntas a las que hemos respondido con gráficos son:
- Distribución de vuelos reservados por mes.
- Relación entre distancia de vuelos y puntos acumulados.
- Distribución de clientes por provincia/estado.
- Comparación de salario promedio por nivel educativo.
- Proporción de clientes según tipo de tarjeta de fidelidad.
- Distribución de clientes según estado civil y género.

3️⃣ Fase 3: Evaluación de diferencias por nivel educativo (`FASE3_diferencias-educacion_irina-ostojic_BONUS.ipynb`)
- Filtrado de columnas relevantes: 'Flights Booked' y 'Education'.
- Análisis descriptivo: media, mediana y desviación estándar por grupo educativo.
- Pruebas de hipótesis: evaluación de diferencias significativas en el número de vuelos reservados entre distintos niveles educativos utilizando diferentes tipos de test (como Mann-Whitney U).

## 🧠 Aprendizajes personales
- La documentación de cada fase con explicaciones claras, me ha permitido reflexionar sobre los resultados y tomar mejores decisiones en base a su análisis.
- He reforzado el uso de Pandas y NumPy para limpieza, transformación y análisis de datos, aprendiendo a manejar nulos y filtrar información de manera eficiente.
- La visualización con Matplotlib y Seaborn me ayudó a adentrarme en la visualización de datos para poder identificar patrones, tendencias y relaciones entre variables.

## 📝 Recomendaciones
Se recomienda revisar cada notebook paso a paso, asegurando comprensión del análisis.