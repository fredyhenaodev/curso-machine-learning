# Terminología y regresión lineal

La regresión lineal nos va a dar justo lo que queremos como resolución de un problema de ML. Partimos de una ecuación, la Y será nuestro label o variable que estamos prediciendo, la X que será nuestra variable de entrada y le llamaremos feature.

* **Modelo:** Una vez construyamos nuestro modelo con los datos históricos, vamos a predecir el futuro y que la máquina pueda tomar esas decisiones con lo ya aprendido.
* **Training:** Para lograr predecir el futuro, tendremos una etapa de entrenamiento. En esta etapa aprenderá cómo se relacionan las variables
* **Inference:** Usamos nuestro modelo para realizar predicciones.

Para construir un modelo usamos las variables de entrada siendo necesario normalizar una para tener una representación numérica y construimos una ecuación.

La diferencia que puede haber entre el resultado y el valor real debemos tratar de que no exista para que la predicción sea lo más cercana posible al valor real, no será al 100%, pero la diferencia o pérdida debe ser baja. Para llegar a eso debemos escoger el peso correcto.
