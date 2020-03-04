# IA_datos
Este es un proyecto de la materia de inteligencia artificial para la prediccion mediante el aprendizaje supervisado 
utilizando el algoritmo random forest dentro de la herramienta BigMl, ademas, los datos fueron obtenidos de la 
base de datos abiertos que se encuentran en el INEC.

BASES DE DATOS ORIGINALES

Dentro de la caerpeta BASES_original se encuentran los datos descargados directamente de los datos abierto del INEC
de los cuales se obtuvo todas las variables para contestar nuestra pregunta de investigacion y solucionar nuestro 
problema planteado y finalmente armar nuestro nuevo data set que sera utilizado en el aprendizaje automatico.

DATA SET A UTILIZAR

Se lo encuentra con el nombre de data_final_pobreza son las variables que necesitamos para determinar nuestra 
pregunta, se lo obtuvo de realizar la limpieza de los data set originales y simplificar variables no necesarias
entonces poseemos un todal de 9 caracteristicas que son (Hogar propio, calle, zona, tipo vivienda, 
tiene discapacidad, tiene celular, recibe BDH tiene negocio, area)y 14,199 datos.

DICCIONARIO DE DATOS

Se encuentra con el nombre de diccionario_de_datos, donde estan el nombre de las variables con su respectiva 
descripcion que estan en cada una de las caracteristicas para el entendimiento del data sed a utilizar.

DATOS DE ENTRENAMIENTO Y TEST

Se encuentran con el nombre de entrenamiento_80% y test_20% respectivamente, para el entrenamiento del modelo 
se utilizo el 80% del data set total y el 20% para comprobar la prediccion del modelo, en este caso la division 
se la realizo en la herramienta BigMl, y esto fue de forma randomica ya que es una de las facilidades de la misma.

MATRIZ DE CONFUSION

se presenta con el nombre de matriz_de confusion, es una de las facilidades de evaluar el modelo de entrenamiento 
con el test nos emite una matriz con los valor que se han predecido y el porcentaje de la prediccion entre otros 
valores y graficas.

PRUEBAS DE CARACTERISTICAS

Esta con el nombre de PRUEBA, es un documento que nos facilita la herramienta BigMl en el cual podemos 
intercambiar los valores de las caracteristicas para ir determinando si es pobre o no, ademas del porcentaje de 
confiabilidad de que la prediccion es precisa, y entre otros valores.

PREDICCION

Esta con el nombre de segunda_prediccion, luego de hacer la primera prediccion con la columna existente se procedio
a relizar una segunda columna de prediccion en el data set de test, para combrobar que el modelo funciona y podremos
observar las coincidencias y los errores.
