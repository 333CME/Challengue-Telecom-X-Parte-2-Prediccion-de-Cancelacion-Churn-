# CHALLENGUE TELECOM X PARTE 2 MODELO DE PREDICCIÓN DE CANCELACIÓN MACHINE LEARNING
## 1.- **MISIÓN**  
Desarrollar modelos predictivos capaces de prever qué clientes tienen mayor probabilidad de cancelar sus servicios.
La empresa quiere anticiparse al problema de la cancelación, y se debe construir un pipeline robusto para esta etapa
inicial de modelado:  
## 2.- ** OBJETIVOS DEL DESAFÍO  
  - Preparar los datos para el modelado (tratamiento, codificación, normalización).  
  - Realizar análisis de correlación y selección de variables.  
  - Entrenar dos o más modelos de clasificación.  
  - Evaluar el rendimiento de los modelos con métricas.  
  - Interpretar los resultados, incluyendo la importancia de las variables.  
  - Crear una conclusión estratégica señalando los principales factores que influyen en la cancelación.  

## 3.- **ESTRUCTURA INICIAL DEL PROYECTO:**  
  - Archivo Readme md para introduccipon del proyecto 
  - Archivo con los Datos tratados: datos_tratados.csv  
  - Notebook Google Colab principal para realizar los análisis (telecom_x_parte_2.ipynb):  
      - Revisión preliminar de los datos tratados.
      - Gráficos exploratorios de datos
      - Análisis de correlación
      - Selección de variables
      - Elegir y entrenar 2 modelos de clasificación
      - Evaluar el rendimiento de los módelos basado en métricas 
  - Informe final
      - Paso paso del análisis preliminar de los datos
      - Gráficos
      - Tablas con la información del data frame
      - Correlación
      - Variables seleccionadas
      - Separación de datos en: entrenamiento(train), prueba(test) y validación(val)
      - Modelos utlizados
      - Métricas obtenidas
      - Ajustes a las métricas
      - Interpretación de los resultados
      - Pesentación de los resultados  
## 4.- **SELECCIÓN DE LA VARIABLE PRINCIPAL**  
  - Distribución de Churn:¿Qué es Churn?  
Churn (o tasa de abandono) es un término clave en el análisis de negocios, y se refiere a la pérdida de clientes  
que dejan de usar los productos o servicios de una empresa. En el contexto de Telecom X, el churn representa a  
los clientes que cancelan sus suscripciones o contratos.  
Ta = Churn Rate = ((N° de clientes perdidos en un período) / (Total de clientes al inicio del período)) × 100  

