# PCA: Implementación desde cero

- En este proyecto se implementa desde cero el algoritmo PCA para reducción de dimensionalidad de datos y se comparan los resultados con la implementación de Scikit Learn.  
- Como datos a estudiar se usa la base de datos Iris (plantas del genero *Iris*) para determinar las componentes principales.   
- Se usan estos datos ya que la proyección a dos componentes principales logra separar las 3 distintas clases, lo que ayuda a la visualización.

- El projecto esta compuesto por dos *jupyter notebooks*:
  - **Algoritmo PCA.ipynb**: Donde se crea clase con implementación manual de PCA.
  - **Implementacion Iris Dataset.ipynb**: Se implementa el algoritmo manual sobre los datos de plantas *Iris* y se comparan resultados con la implementación de Scikit Learn.  

# Algoritmo PCA

- El algoritmo K-Means es un algoritmo no supervisado de reducción de dimensionalidad.
- Esta técnica encuentra las direcciones donde los datos tienen mayor varianza, denominadas direcciones principales.
- Al tomar los componentes de los datos proyectados en las direcciones con mayor variabilidad, se logra mantener gran cantidad de la información que diferencia los datos y a la vez reducir el número de componentes por datos (reducción de dimensionalidad).
- Debido a que se enfoca en mantener los datos diferenciados, permite mantener la estructura global de los datos al reducir el número de dimensiones.
- Al usar PCA se tiene la libertad de elegir cuantas direcciones principales utilizar, entre más direcciones se captura más información de los datos, pero a la vez aumenta el número de dimensiones.
- Se puede utilizar para visualización de datos, reduciendo las dimensiones a 2 o 3 para poder graficar los datos.
