# telecomm_tariff_performance_statistical_analysis
Análisis de datos y pruebas de hipótesis estadísticas para evaluar las tarifas de telecomunicaciones para la optimización de del presupuesto de publicidad de la compañía Megaline.  ***Proyecto desarrollado como evaluación final del Sprint de Análisis Estadístico de Datos del Bootcamp de Data Scientist de TripleTen.***

## Contexto del proyecto
Trabajas como analista para el operador de telecomunicaciones Megaline. La empresa ofrece a sus clientes dos tarifas de prepago, Surf y Ultimate. El departamento comercial quiere saber cuál de las tarifas genera más ingresos para poder ajustar el presupuesto de publicidad.

Vas a realizar un análisis preliminar de las tarifas basado en una selección de clientes relativamente pequeña. Tendrás los datos de 500 clientes de Megaline: quiénes son los clientes, de dónde son, qué tarifa usan, así como la cantidad de llamadas que hicieron y los mensajes de texto que enviaron en 2018. Tu trabajo es analizar el comportamiento de los clientes y determinar qué tarifa de prepago genera más ingresos.

## Objetivo del proyecto
Realizar pruebas estadísiticas para evaluar el comportamiento de los clientes en cada tarifa.

## Librerías principales utilizadas
- pandas
- numpy
- matplotlib
- seaborn
- scipy

## Principales métodos y técnicas utilizadas
- Análisis exploratorio inicial
- Análisis de datos ausentes y duplicados
- Análisis de distribución
- Agrupación de datos
- Fusión de dataframes
- Filtrado avanzado de datos
- Creación e interpretación de gráficos avanzados
- Pruebas de hipótesis 
- Prueba de Levene

## Resultados
1. Desde el comienzo se consideraron las políticas de cobro de la compañía, respecto a los minutos, los mensajes o el internet, para agregar columnas que redondearan los valores respectivos.

2. En el análisis de gráficos, se encontraron patrones de comportamiento similares en cuanto al uso de llamadas, mensajes e internet, pero también una diferencia notable en cuanto a la distribución de los ingresos. Casi la totalidad de los usuarios del plan Ultimate pagan solo la cuota de su plan mensual, mientras que los usuarios del plan Surf realizan pagos distintos, en promedio 3 veces más que el costo de su plan mensual. Esto quiere decir que los usuarios subestiman la cantidad de datos, mensajes y llamadas que necesitan, contratando un plan que no satisface esas necesidades y, por lo tanto, haciendo pagos adicionales por cada servicio usado extra a lo contratado.

3. En las pruebas de hipótesis se rechazaron ambas hipótesis nulas, el ingreso promedio de los usuarios de cada plan es diferente y el de los usuarios de la región NY - NJ también lo es, respecto del resto de ciudades.

4. Derivado de las prubas de hipótesis y de la distribución de los ingresos por cada uno de los planes, se puede decir que el plan Surf es más rentable que el plan Ultimate. 
