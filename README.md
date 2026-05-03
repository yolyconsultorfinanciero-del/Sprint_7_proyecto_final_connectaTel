# Sprint_7_proyecto_final_connectaTel

## OBJETIVO DEL PROYECTO
El objetivo principal es realizar un Análisis Exploratorio de Datos (EDA) y una segmentación de clientes para una empresa de telecomunicaciones en Bogotá. El proyecto busca limpiar inconsistencias técnicas, identificar patrones de consumo (mensajes, llamadas y duración) y categorizar a los usuarios por edad y nivel de uso para diseñar estrategias comerciales de fidelización más efectivas.

## DATASETS UTILIZADOS
Se trabajó con un conjunto de datos integrado que consolidó la información de 4,000 usuarios:
user_profile: Contiene datos demográficos (como age) y métricas de comportamiento técnico.
Variables clave:
- age: Edad del usuario.
- is_text: Cantidad de mensajes enviados.
- is_call: Cantidad de llamadas realizadas.
- duration: Minutos totales de conversación.
- length: Longitud o métrica adicional de actividad.

## ETAPAS DE ANALISIS REALIZADAS
- Limpieza de Datos: Identificación y tratamiento de valores centinela (como -999), eliminación de símbolos/asteriscos en          nombres y corrección de fechas futuras.
- Análisis Estadístico: Generación de resúmenes (media, mediana, desviaciones) para entender la distribución de la base.
  Detección de Outliers: Uso del método de Rango Intercuartílico (IQR) y diagramas de caja (Boxplots) para identificar usuarios    con consumo extremo.
- Segmentación Lógica:
  - Grupo de Uso: Clasificación en 'Bajo', 'Medio' y 'Alto uso' según llamadas y mensajes.
  - Grupo de Edad: Clasificación en 'Joven', 'Adulto' y 'Adulto Mayor'.
- Visualización: Creación de gráficos de conteo (countplot) y distribución para validar los segmentos creados.

## COMO REPORDUCIR EL PRIYECTO
Existen dos formas principales de ejecutar este análisis:

### Opción 1: Google Colab (Recomendado)
1. Ve a [Google Colab](https://colab.research.google.com/).
2. Selecciona la pestaña **GitHub**.
3. Ingresa tu usuario de GitHub y selecciona el repositorio `Sprint_7_proyecto_final`.
4. Abre el archivo `.ipynb` y ejecuta las celdas.

### Opción 2: Local (Jupyter Notebook)
1. Clona el repositorio:
   ```bash
   git clone [https://github.com/TU_USUARIO/Sprint_7_proyecto_final.git](https://github.com/TU_USUARIO/Sprint_7_proyecto_final.git)
   
