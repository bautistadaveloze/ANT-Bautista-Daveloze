## Dataset elegido
El dataset elegido es **Car Price Assignment Dataset** disponible en Kaggle.

## ¿Qué predeciría?
Si entrenara un modelo con este dataset, intentaría **predecir el precio de un auto (`price`)** a partir de sus características mecánicas y físicas.

## ¿Qué tipo de Machine Learning usaría?
Usaría **Machine Learning supervisado de tipo regresión**, ya que el objetivo es predecir un **valor numérico continuo** (el precio del auto).

## ¿Qué features serían más útiles y por qué?

Algunas de las variables que probablemente serían más útiles son:

- **`enginesize`**: el tamaño del motor suele estar muy relacionado con el precio, ya que motores más grandes suelen pertenecer a autos más potentes y caros.
- **`horsepower`**: indica la potencia del motor, lo cual influye directamente en el valor del vehículo.
- **`curbweight`**: el peso del auto puede indicar el tamaño y la calidad del vehículo, lo que también afecta su precio.
- **`carwidth` y `carlength`**: el tamaño del auto suele estar asociado a categorías más caras.
- **`fueltype`**: el tipo de combustible (por ejemplo gasolina o diésel) puede influir en el costo del vehículo.
- **`drivewheel`**: el tipo de tracción (delantera, trasera o integral) puede afectar el rendimiento y el precio.
- **`CarName`**: la marca o modelo del auto puede ser muy importante, ya que algunas marcas tienen mayor valor en el mercado.

Con estas variables, el modelo podría aprender la relación entre las características del vehículo y su precio para **estimar el valor de un auto a partir de sus especificaciones**.
