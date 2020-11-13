# Regresión logística y descenso del gradiente en Python
## Beatriz Cárdaba Rico
### 12/11/2020
__Objetivo__: Programar el descenso del gradiente en Python en base al archivo de datos facilitado en clase. Explicar el notebook con el máximo grado de detalle para trabajar en el entendimiento del algoritmo.

En el presente notebook se implementarán diferentes algoritmos que nos permitirán el cálculo y la visualización del descenso del gradiente, en este caso se está realizado con el data set "4_1_data" aunque será sencillo realizar los cambios para calcular el descenso del gradiente de cualquier otro data set. También, los algoritmos están preparados para cambiar fácilmente la tasa de aprendizaje y el número máximo de iteraciones que queremos establecer.

Índice:
 - Importar librerías y datos.
	- Importar librerías
	- Importar data set
 - EDA
	- Descripción de datos
	- Tranformaciones y organización de datos
	- Visualización de datos.
 - Descenso del Gradiente
	- Normalización de las variables predictivas.
	- Creación de coeficientes iniciales aleatorios.
	- Establecemos la función sigmoide para 𝑦̂ .
	- Función de Costes.
	- Redefinimos los Betas.
	- Código DESCENSO GRADIENTE
	- Visualización gáfica
 - Referencia
