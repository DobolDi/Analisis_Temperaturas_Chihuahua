# Analisis_Temperaturas_Chihuahua
Análisis de temperaturas interiores de una tienda.

Querido Python, he intentado desarrollar un programa para leer varios archivos .csv con datos de una tienda en Chihuahua y realizar un análisis de datos rápido y eficiente, el cual funciona pero no es elegante. El objetivo es presentar las temperaturas máximas y mínimas diarias por zona en el horario de 9am a 8pm, obtener el valor promedio máximo semanal y poder determinar en qué intervalo de tiempo ocurren así como calcular el tiempo total semanal en que las zonas permaneces fuera del rango de confort de 21°C a 24°C. En las gráficas busco presentar de manera visual la relación entre la temperatura exterior medida y las interiores, la similitud entre los datos de temperatura exterior medidos y los reportados por el Sistema Meteorológico Nacional (SMN) if else si la diferencia entre estos se debe ganancas por irradincia solar del sensor en tienda.

En Chihuahua1.csv y Chihuahua2.csv encontrarás datos cada 5 min de distintos parámetros medidas correspondientes un intervalo de tiempo de una semana (del 1 de marzo al 7 de marzo de 2021 y del 21 de febrero al 27 de febrero de 2021 respectivamente). En Chihuahua.csv encontrarás solo la columna de temperatura ambiente de utilidad y en Estacion_Chihuahua.csv datos del sistema meteorológico nacional (del que solo nos interes temperatrua ambiente e irradiancia) que vienen con un encoding raro que no permite que se lean en mi notebook a menos que se los cambie. 

Quisiera eficientar la limpieza de los nombres de las variables, la reducción de los DataFrames a solo las variables que me interesan (temperaturas), y pimpear gráficas que contienen datos de varios archivos .csv. Me he portado muy bien este año aunque apenas empieza, así que espero me regales trucos, definiciones o hasta un código limpio y ordenadito y no un pedazo de carbón. Sí así lo decides podrás mostrar cómo se hacen funciones como to_datetime, groupby, t.stack, dt.time, drop y muchas más.

Gracias

PD. Si me traes todo lo que pedí prometo titularme y conseguir trabajo... un momento
