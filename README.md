# Redes-Neuronales-25.63
## Clase 3-3-26
### Temas Importantes de la Materia:
- Criterios de Ajustes de Parámetros
- Modelos de Redes Neuronales <br>
    - MLP, Backprop, Adam, RMSProp. <br>
    - Probabilísticos, Optimizables, Paralelizables, Etc.
- Metodología de Entrenamiento y Evaluación de Modelos
- Técnicas de Regularización <br>
    - Formas de asegurarse de que los modelos funcionen con datos reales.
- Datos vs Parámetros 
- Modelos 2 <br>
    - Imágenes (CNN, 2D, ViT, etc.) <br>
    - NLP

Un gran problema no es encontrar o tener un buen modelo sino tener una buena base de datos útil y competitiva.

### Repaso
Requirements: Pandas, Numpy, Matplotlib, SKLearn, Konda, PyEmp, Typing, DocString, Clases, Metodos, Dunders


## Clase 4-1-26

**Regresión Logística**: Si los datos son linealmente separables es super útil como función de activación

Hay un término que es la entropía de los datos, que es una medida de la incertidumbre de una variable aleatoria.

Si los datos de los que se parten son no deterministicos, entonces la entropía máxima a la que tenderá el modelo es la entropía de dichos datos de entrada.

Overfitting, hace que un modelo funcione excelente con los datos de entrenamiento pero a la que le agregue datos le pifia a todo.

Funcion de costo.

Gradient Descent: Una forma de reducir la función de binary cross entropy a su punto mínimo a través del gradiente.

#### Redes Neuronales

Bottom Up vs Top Down:

    - A partir de datos sin conocimiento en la materia se encuentrar patrones vs a partir de mi conocimiento en el tema lo vuelco en un modelo.

    - Ninguno de los dos enfoques son puros.
