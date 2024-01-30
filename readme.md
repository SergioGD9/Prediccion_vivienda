# Predicción de precios de propiedades 


Este proyecto utiliza un modelo de Bosque Aleatorio para predecir los precios de las propiedades basándose en varias características de la propiedad.

### Características


Las características utilizadas para la predicción son:

+ Número de baños (Bathrooms)
+ Número de dormitorios (Bedrooms)
+ Área de la vivienda (Living Area)
+ Tipo de vivienda (Home Type)
+ Ciudad (City)

### Proceso


1. Preparación de los datos: Las características y las etiquetas se extraen del conjunto de datos. Las características numéricas se escalan y las características categóricas se codifican en caliente.

2. División de los datos: Los datos se dividen en un conjunto de entrenamiento y un conjunto de prueba.

3. Ajuste de hiperparámetros: Se realiza una búsqueda en cuadrícula para encontrar la mejor combinación de hiperparámetros para el modelo de Bosque Aleatorio.

4. Evaluación del modelo: El modelo se evalúa utilizando el error cuadrático medio (MSE) en el conjunto de prueba.

5. Predicción de precios para nuevas propiedades: El modelo se utiliza para predecir el precio de una nueva propiedad basándose en sus características.



### Resultados


Los resultados de la predicción se imprimen en la consola. Para una nueva propiedad con 2 baños, 3 dormitorios, un área de vivienda de 1500 pies cuadrados, de tipo 'Casa' y ubicada en 'San Francisco', el modelo predice un precio de aproximadamente $621,252.61.