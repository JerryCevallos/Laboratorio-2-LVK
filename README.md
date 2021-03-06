# Laboratorio 2 LVK (Analisis de mallas)
Segunda ley de Kirchhoff donde la suma algebraica de los voltajes es igual a 0

![1 1](https://user-images.githubusercontent.com/75337022/104261539-c3dd2180-5453-11eb-922e-e9520ccbaf47.png)


--Objetivos--

Generales:

	Explicar y demostrar teórica y practicamos la ley de voltajes de Kirchhoff
  
	Realizar el análisis de los diferentes circuitos con el uso de mallas 
  
	Mostrar prácticamente la función del circuito en un simulador e utilizar los instrumentos de medición ya sea para amperaje o voltaje
  
Específicos:

	Construir en el simulador Tinkercad el circuito guiándonos en el diagrama previamente establecido
  
	Demostrar la ley de Kirchhoff donde nos indica que la suma algebraica de los voltajes es igual a 0 
  
	Comprender el uso del multímetro ya sea para medir amperaje o voltaje siendo asi un método de comprobación para los cálculos realizados a mano 
  
  
--Requisitos previos--

	Análisis correcto de circuitos 
  
	Verificación de la teoría para la aplicación en la practica 
  
	Tener un conocimiento previo de la utilización de la instrumentación
  
  
---------------Marco Teorico----------------                                                        

Ley de Voltaje de Kirchhoff
(Método de mallas)

La Ley de voltajes de Kirchhoff es la segunda de sus leyes fundamentales que podemos usar para el análisis de circuitos. La primera es la Ley de corriente de Kirchhoff.

¿Qué es una malla en un circuito?
Una malla consiste en un conjunto de ramas que forman un camino cerrado y que no contienen ninguna otra línea cerrada en su interior.
 
La Ley de voltaje de Kirchhoff establece que la suma algebraica de todos los voltajes alrededor de una malla eléctrica en un circuito es igual a cero. Observe que el término «suma algebraica» significa tener en cuenta las polaridades y signos de las fuentes y caídas de tensión alrededor de la malla. Por lo tanto, al aplicar la Ley de mallas de Kirchhoff a un elemento de circuito específico, es importante que prestemos especial atención a los signos algebraicos, (+ y -) de las caídas de voltaje entre los elementos, de lo contrario nuestros cálculos pueden estar equivocados.
Antes de percibir mejor qué es la ley de voltaje de Kirchhoff (KVL) vamos a entender primero qué es la caída de tensión a través de un solo elemento como una resistencia.

---Caida de tension de una resistencia---

![2](https://user-images.githubusercontent.com/75337022/104261648-ff77eb80-5453-11eb-84af-671804fac1eb.png)
 
En este caso el flujo de corriente circula a través de la resistencia desde el punto A al punto B, es decir, de terminal positivo a terminal negativo. Por lo tanto, como estamos yendo en la misma dirección que la corriente, habrá una caída de potencial a través de la resistencia igual a 
– I * R.
Si el flujo de corriente estuviera en la dirección opuesta del punto B al punto A, entonces habría un aumento en el potencial a través del elemento resistivo a medida que nos movemos de un – potencial a un + potencial, dándonos una caída de voltaje
I * R.
Por lo tanto, para aplicar correctamente el método de mallas a un circuito, primero debemos saber la polaridad, ya que el signo de la caída de voltaje a través del elemento resistivo dependerá de la dirección de la corriente que fluye a través de él. Como regla general, perderá potencial en la misma dirección de la corriente a través de un elemento y ganará potencial al revés.
La dirección de la corriente alrededor de una malla eléctrica puede ser elegida a nuestro antojo en sentido horario o anti horario.
Si la dirección elegida es diferente a la dirección real del flujo de corriente, el resultado seguirá siendo correcto y válido, pero dará lugar a que la respuesta algebraica tenga signo negativo. Para entender esta idea un poco más, veamos un circuito donde aplicar la Ley de voltaje de Kirchhoff en el análisis de mallas.

---Circuito de una malla---

![3](https://user-images.githubusercontent.com/75337022/104261664-07d02680-5454-11eb-97c5-c0b8175d1e05.png)

 
La Ley de tensión de Kirchhoff establece que la suma algebraica de las diferencias de potencial en cualquier malla debe ser igual a cero.
Puesto que las dos resistencias, R1 y R2 están conectadas en serie, ambas son parte de la misma malla eléctrica por lo que la misma corriente debe fluir a través de cada resistencia.

Así, según KVL tenemos que:

![4](https://user-images.githubusercontent.com/75337022/104261676-10286180-5454-11eb-8e3e-8050cdf257ba.png)

Teniendo que la intensidad del circuito será:

![5](https://user-images.githubusercontent.com/75337022/104261688-18809c80-5454-11eb-8ae2-5b5d7ca78df1.png)
	
Como queremos calcular la caída de tensión en cada resistencia aplicamos la Ley de Ohm:

![6](https://user-images.githubusercontent.com/75337022/104261733-33eba780-5454-11eb-87d5-29b4e30bca53.png)
	
	
Podemos apreciar que la caída de tensión en una resistencia de un circuito con una malla será igual al voltaje de entrada por la resistencia en cuestión entre la suma de todas las resistencias.


---Material o Equipo Requerido---

![7](https://user-images.githubusercontent.com/75337022/104261747-3c43e280-5454-11eb-8167-6c7ceabdfaa0.png)


---Diagramas---

![8](https://user-images.githubusercontent.com/75337022/104261769-436af080-5454-11eb-8f1c-14c783ac5e86.png)

Procedimiento 

	Realice el circuito previamente visto en el diagrama a utilizar en este caso el simulador Tinkercad 
	
	Con el multímetro procedemos a medir el voltaje y amperaje según tengamos la necesidad
	
	Con los valores obtenidos vamos a proceder a realizar los cálculos aplicando la teoría de la ley de voltajes de Kirchhoff
	
	Posteriormente tabulamos los datos en tablas donde comprobaremos el error y la variación de las medidas que se realizan en el simulador y las que se realizan a mano en un circuito armado


---Tabulacion de datos----

![9](https://user-images.githubusercontent.com/75337022/104261784-4cf45880-5454-11eb-96de-c99961f53b78.png)


---Calculos---

![10](https://user-images.githubusercontent.com/75337022/104261806-5382d000-5454-11eb-8e26-abc1f28c8293.png)

![11](https://user-images.githubusercontent.com/75337022/104262470-ab6e0680-5455-11eb-8b0f-87d3d5e90bb1.png)

![12](https://user-images.githubusercontent.com/75337022/104266481-b167e580-545d-11eb-8658-5c6c70684fd0.png)



![13](https://user-images.githubusercontent.com/75337022/104262498-bb85e600-5455-11eb-9940-1f5a0807a519.png)


---Conclusiones---

•	Los valores de corriente y voltaje determinados por la ley de Kirchhoff son muy aproximados a los valores experimentales, con un porcentaje de errores del 20%

•	La segunda ley de Kirchhoff también se cumple: en una malla, la suma algebraica de los voltajes es igual a 0, Con los valores hallados gracias a la simulación la suma resulta en un 0 sin necesidad de mucho calculo

•	Esta simulación es importante para la comprensión de temas futuros y el cálculo preciso de los diferentes circuitos que se presenten, podemos tomar como una forma de simplificar problemas con ejercicios extensos envés de reducir a circuitos pequeños y trabajarlos individualmente podemos usar las leyes y resolver los ejercicios en simples pasos llegando a un sistema de ecuaciones  

	
---Recomendaciones---

	Como sabemos Tinkercad tiene muchos valores ideales al momento de realizar la medición debemos procurar utilizar un simulador que nos de valores lo más acercado posible a la realidad para entender mejor la compresión lo cual disminuiría los errores presentados al momento de realizar las mediciones
	
	Realizar ejercicios varios de complejidad media y alta que tena directa relación con la LVK ya que asi mejorara la compresión y podremos ser más agiles al momento de solucionar un circuito con el método de mallas
 
---Bibliografia---

Piensa 3d,2021, Ley de voltaje de Kirchhoff: Método de mallas: 
https://piensa3d.com/ley-voltaje-kirchhoff-metodo-mallas/#:~:text=Una%20malla%20consiste%20en%20un,circuito%20es%20igual%20a%20cero.

Electrónica FP,2017, Método de mallas:
https://www.youtube.com/watch?v=uaG_GPQxKhg


---Anexos---

![14](https://user-images.githubusercontent.com/75337022/104262508-c3de2100-5455-11eb-8e6c-be5ae8cde5c2.png)

1.1 Tomamos los materiales para el circuito

![15](https://user-images.githubusercontent.com/75337022/104262533-cd678900-5455-11eb-8ba5-dfa4acdb1aac.png)


1.2 Armamos y montamos el circuito en el protoboard

![16](https://user-images.githubusercontent.com/75337022/104262580-e3754980-5455-11eb-9393-fdf697b7ab31.png)

 
1.3 Utilizamos los multímetros para obtener los resultados de amperaje y voltaje

![17](https://user-images.githubusercontent.com/75337022/104262596-ea9c5780-5455-11eb-8f17-da47383eaef5.png)

 1.4 Obtenemos los resultados utilizando los amperímetros

