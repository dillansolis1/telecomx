# telecomx
# Análisis de la Evasión de Clientes en Telecom X

## Descripción

Este proyecto tiene como objetivo analizar los datos de los clientes de Telecom X para entender las razones detrás de la evasión de clientes. Utilizando datos ficticios de clientes, se realizó un análisis de varios factores que podrían influir en la decisión de los clientes de abandonar la compañía. Los resultados ayudarán a la empresa a mejorar su servicio y reducir la tasa de evasión.

## Objetivo del Análisis

El análisis busca responder a las siguientes preguntas clave:
- ¿Existen patrones en los datos de uso de los clientes que podrían estar relacionados con la evasión?
- ¿Cómo impacta la satisfacción del cliente en la decisión de abandonar el servicio?
- ¿Cuál es la relación entre la frecuencia de interacciones con el servicio al cliente y la evasión?
- ¿Existen diferencias significativas en la evasión según el género, la duración del contrato y el historial de pagos?

## Metodología

1. **Carga y limpieza de los datos**: Se utilizaron datos ficticios generados aleatoriamente para simular características clave de los clientes, como género, uso de datos, historial de pagos, interacciones con servicio al cliente, y más.
   
2. **Análisis Exploratorio de Datos (EDA)**:
   - Análisis de la distribución de los datos demográficos.
   - Análisis de la relación entre el uso de datos y la evasión de clientes.
   - Análisis de la satisfacción y su relación con la evasión.
   - Análisis de las interacciones con el servicio al cliente y su posible impacto en la evasión.

3. **Visualización de Datos**: Se utilizaron gráficos de barras, diagramas de caja y mapas de calor para representar la distribución y la relación entre diferentes variables.

4. **Correlación**: Se calculó la matriz de correlación entre las variables numéricas para identificar posibles relaciones entre ellas.

## Resultados Clave

- **Evasión de Clientes**: La tasa de evasión (clientes que abandonaron) es de un porcentaje significativo, lo que indica que se deben tomar medidas para reducir esta tasa.
- **Factores Relacionados con la Evasión**: Se identificaron patrones en el uso de datos, la satisfacción del cliente y las interacciones con el servicio al cliente como factores clave que podrían influir en la decisión de los clientes de abandonar el servicio.

## Recomendaciones

Basado en los hallazgos del análisis, se sugieren las siguientes recomendaciones para reducir la evasión de clientes:

- Mejorar la calidad del servicio al cliente para reducir las interacciones negativas.
- Ofrecer promociones y servicios personalizados para clientes con bajo uso de datos.
- Implementar encuestas de satisfacción periódicas para detectar insatisfacción antes de que los clientes decidan irse.

## Instrucciones para Ejecutar el Código

Para ejecutar el análisis, sigue estos pasos:

1. **Instalar las librerías necesarias**:
   
   Ejecuta el siguiente código para instalar las librerías necesarias:

   ```bash
   pip install pandas matplotlib seaborn
