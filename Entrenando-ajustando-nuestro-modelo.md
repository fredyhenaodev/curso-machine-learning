# Training &amp; Loss: Entrenando y ajustando nuestro modelo

En esta clase hablaremos del proceso de entrenamiento y cómo minimizar la pérdida. Queremos que nuestro modelo quede de la mejor forma posible

Nuestro objetivo es minimizar la pérdida.

Para calcular el error usamos una fórmula llamada MSE(Mean Squared Error)

Stochastic Gradient Descent(SGD): Es estocástico porque será aleatorio y tenemos opciones para realizar el gradiente en busca del mínimo. ¿Deberíamos calcular el gradiente de todo el dataset? Puede ser más eficiente elegir ejemplos aleatorios. Un solo ejemplo es muy poco, trabajamos con un batch.

El proceso de aprendizaje requiere iniciar los pesos de los valores para calcular la pérdida que estamos teniendo, con la ecuación vista tendremos una idea de qué tan lejos está nuestra predicción de lo real y así evaluar el desempeño de nuestro modelo. Repetimos utilizando el gradiente como referencia para acércanos al peso donde podemos minimizar la pérdida.

* La fase de entrenamiento es un proceso iterativo
* Al calcular el error(loss), el gradiente nos ayuda a buscar el mínimo
* Es necesario calibrar el valor de learning rate
