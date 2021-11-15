# MLTutorial- Taller 3 corte- DAVID STIVEN SALAMANCA SANCHEZ
1.Del script de forest fires:
# ¿Se desea resolver el problema utilizando aprendizaje supervisado o no supervisado? 
-Se desea resolver un problema utilizando aprendizaje no supervisado ya que no se nota evidencia alguna de supervicion solo estan las graficas y resultados naturales del archivo csv.
# ¿Es un problema de clasificación o de regresión?
-Es un problema de clasificación.
# ¿Qué interpretación le puede dar a los resultados obtenidos?
-Se calcula la cantidad de incendios forestales que pueden llegar a producirse en los siguientes años.
# 2.Del script de recursos humanos (rrhh):
# ¿Cuál es la clase para la que el modelo más se equivoca? ¿Por qué?
-Evaluating the model es el modeloerroneo ya que ni funciona.
![image](https://user-images.githubusercontent.com/42383263/141829439-5f83fc8d-d79c-4385-839b-289c9482dd52.png)
# ¿Cuál cree que es el propósito del parámetro max_depth usado al momento de instanciar el modelo de árbol de decisión?
Para este caso particular, ¿por qué cree que es difícil obtener un buen clasificador?
-max_depth esta hecho para encontrar el valor óptimo formax_depth es una forma de ajustar su modelo. El siguiente código muestra la precisión de los árboles de decisión con diferentes valores para max_depth.
# ¿Para este caso particular, ¿por qué cree que es difícil obtener un buen clasificador?
-Por que por la magnitud de datos no se puede tomar con detalle cada uno de los datos en Script

# 3. Identificación de géneros musicales: Tenga en cuenta que hay dos scripts: music.ipynb y music-multiclass.ipynb. En el primero se intenta crear un modelo clasificador solo para dos clases (caso binario) y en el segundo se entrena uno para todas las clases (géneros musicales) del dataset.
Para el caso binario (jazz and blues vs. soul and reggae) ¿Es posible obtener mejores métricas entrenando un modelo basado en Random Forest?
-Si es posible el modelo lo acepta sin ningun provblema
Escoja otro par de géneros, entrene un conjunto de modelos y documente los resultados del mejor que se haya obtenido.
-El genero mejor obtenido es pop y rock.
![image](https://user-images.githubusercontent.com/42383263/141832532-2c655ad9-f235-4397-ae35-70a8413271ed.png)

Para el caso multi-clase, ¿cuál es la clase para la que el modelo más se equivoca? ¿Por qué?
-Seesquivoca mas en el modelo Splitting train and test datasets no toma en su totalidad los datos
![image](https://user-images.githubusercontent.com/42383263/141832654-750be23b-8431-4bed-8a1c-d177faaca65e.png)

Para el caso multi-clase, el modelo basado en red neuronal parece estar mayoritariamente sesgado hacia un género particular. ¿Cuál género cree que es?
- si esta mas enfocado en el genero de metal.

4 # Segmentación de cajas de compensación familiar (subsidio):
¿Qué cajas de compensación parecen ser mayoritariamente diferentes a las demás?
No ninguno
¿A partir de qué características utilizadas para el entrenamiento del modelo se podría explicar la razón por la que las cajas anteriores fueron agrupadas en clusters tan pequeños?
Apartir de Cluster explanations
¿Se pueden obtener resultados más homogéneos utilizando cantidades diferentes de clusters para el entrenamiento? Entienda homogeneidad como clusters con cantidades similares de instancias de datos.
Si si se puede evidenciar en el modelo
![image](https://user-images.githubusercontent.com/42383263/141834746-86460501-6a5c-4833-bbf5-5f5c76416165.png)



