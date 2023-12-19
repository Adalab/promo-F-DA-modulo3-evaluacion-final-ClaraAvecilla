# promo-F-DA-modulo3-evaluacion-final-ClaraAvecilla

# promo-F-DA-modulo3-evaluacion-intermedia-ClaraAvecilla

# Readme

- En este jupiter se muestra una prueba de evaluación del Módulo 3 de Data Analytics de Adalab, en la a partir de los csv “Customer Loyalty History” y “Customer Flight Activity”: que se plantea la resolución de ejercicios en tres fases:

    - Fase 1: Exploración y limpieza de datos

    - Fase 2: Visualización para responder a preguntas relacionadas con los datos

    - Fase 3: Análisis descriptivo y prueba estadística A/B testing.

    **´Nota´**: La Fase 2 se encuenra en jupiter "Visualización"

*Importación de librerías:*
 

- Imputación de Datos Nulos:
    - **SimpleImputer** (de scikit-learn): Para la imputación simple de valores nulos.
    - **IterativeImputer** (de scikit-learn): Para la imputación de valores nulos utilizando métodos iterativos.
    - **KNNImputer** (de scikit-learn): Para la imputación de valores nulos utilizando el algoritmo KNN.


-  Evaluación Estadística
    - **scipy.stats**: Proporciona funciones estadísticas para evaluar relaciones lineales, distribuciones, pruebas de hipótesis, etc.
    - **ttest_ind** (de scipy.stats): Prueba t de Student para la diferencia de medias entre dos muestras independientes.


- Configuración y Gestión de Warnings
    - Configuración de opciones de visualización de pandas y gestión de warnings para mejorar la presentación y suprimir mensajes innecesarios.


**Descripción de los DataFrame**
1- Datos de la actividad de vuelos de los clientes (Customer Loyalty History.csv):

Este DataFrame proporciona información sobre la actividad de vuelos que efectúan los clientes en una aerolínea, con un enfoque en las estadísticas mensuales de vuelo y puntos acumulados.
*Columnas:*
- Loyalty Number: Número de lealtad único asignado a cada cliente.
- Year: Año en el que se registraron los datos.
- Month: Mes correspondiente a los registros.
- Flights Booked: Número de vuelos reservados por el cliente en el mes.
- Flights with Companions: Número de vuelos en los que el cliente viajó con compañeros en el mismo mes.
- Total Flights: Total de vuelos realizados por el cliente en el mes.
- Distance: Distancia total cubierta por los vuelos en kilómetros.
- Points Accumulated: Cantidad de puntos acumulados por el cliente en el programa de lealtad.
- Points Redeemed: Puntos canjeados por el cliente durante el mes.
- Dollar Cost Points Redeemed: Costo en dólares asociado a los puntos canjeados.


2- Datos de Lealtad del Cliente en la Aerolínea(Customer Loyalty History.csv)

Este DataFrame presenta información detallada sobre la lealtad de los clientes en una aerolínea. Cada fila representa datos mensuales para un cliente específico.
*Columnas:*
- Loyalty Number: Número único de lealtad asignado a cada cliente.
- Year: Año en el que se registraron los datos.
- Month: Mes correspondiente a los registros.
- - Flights Booked: Número de vuelos reservados por el cliente durante el mes.
Flights with Companions: Número de vuelos en los que el cliente viajó acompañado por compañeros durante el mes.
- Total Flights: Total de vuelos realizados por el cliente en el mes.
- Distance: Distancia total cubierta por los vuelos del cliente durante el mes (en kilómetros).
- Points Accumulated: Cantidad de puntos acumulados por el cliente en el programa de lealtad.
- Points Redeemed: Puntos canjeados por el cliente durante el mes.
- Dollar Cost Points Redeemed: Costo en dólares asociado a los puntos canjeados por el cliente.
