# Tarea5

## OBJETIVOS

General
 
Aplicar alguno de los métodos aprendidos para determinar la cantidad que tiene los elementos del circuito 

Específicos:

-Emplear de manera correcta los 3 métodos para resolver ecuaciones


-Utilizar el método del corriente en ramas y el análisis de nodos para calcular algunos elementos


-Entender los principios del magnetismo y electromagnetismo


## MARCO TEÓRICO (RESUMEN)

**CAPITULO 9**

![](https://github.com/bavargas5/Tarea5/blob/main/IMGBV/1.png)

**CAPITULO 10**


## EXPLICACIÓN Y RESOLUCIÓN DE EJERCICIOS O PROBLEMAS

**CAPITULO 9**
**1. Con el método de sustitución, resuelva el siguiente conjunto de ecuaciones para IR1 e IR2.**

                                          100I1 + 50I2 = 30 (1)

                                          75I1 + 90I2 = 15 (2)

Solución

Despejamos una variable de la ec (1)

![](https://github.com/bavargas5/Tarea5/blob/main/IMGBN/1.PNG)

Reemplazamos en la ec (2)

![](https://github.com/bavargas5/Tarea5/blob/main/IMGBN/1.1.PNG)

Con el valor obtenido podemos reemplazar en la ec (1) y obtener el valor de la I1

![](https://github.com/bavargas5/Tarea5/blob/main/IMGBN/1.2.PNG)


**3. Utilizando determinantes, resuelva el siguiente conjunto de ecuaciones para ambas corrientes:**

                                       -I1 + 2I2 = 4

                                       7I1 + 3I2 = 6
                                       
Solución 
Evalúe el determinante característico como sigue:

![](https://github.com/bavargas5/Tarea5/blob/main/IMGBN/2.PNG)

Al resolver para I1 se obtiene

![](https://github.com/bavargas5/Tarea5/blob/main/IMGBN/2.1.PNG)

Al resolver para I2 se obtiene

![](https://github.com/bavargas5/Tarea5/blob/main/IMGBN/2.2.PNG)

**5. Evalúe cada uno de los determinantes:**

![](https://github.com/bavargas5/Tarea5/blob/main/IMGBN/3.PNG)



**7. Resuelva para I1, I2, I3 en el siguiente conjunto de ecuaciones con determinantes:**

                                     2I1 - 6I2 + 10I3 = 9
                                     
                                     3I1 + 7I2 - 8I3 = 3
                                     
                                     10I1 + 5I2 - 12I3 = 0
                                     
Este determinante de tercer grado se evalúa aplicando el método del triángulo como sigue:

![](https://github.com/bavargas5/Tarea5/blob/main/IMGBN/4.PNG)


![](https://github.com/bavargas5/Tarea5/blob/main/IMGBN/4.1.PNG)

A continuación, se forma otro determinante sustituyendo los coeficientes de I1 por las constantes
del lado derecho de las ecuaciones en el determinante característico.

![](https://github.com/bavargas5/Tarea5/blob/main/IMGBN/4.2.PNG)


Se resuelve para I1 dividiendo este determinante entre el determinante característico. El resultado
negativo indica que la corriente real circula en dirección opuesta a la suposición original.

![](https://github.com/bavargas5/Tarea5/blob/main/IMGBN/4.3.PNG)


Para I2

![](https://github.com/bavargas5/Tarea5/blob/main/IMGBN/4.4.PNG)


Para I3

![](https://github.com/bavargas5/Tarea5/blob/main/IMGBN/4.5.PNG)


![](https://github.com/bavargas5/Tarea5/blob/main/IMGBN/4.6.PNG)



**9. Resuelva las dos ecuaciones simultáneas del problema 1 con su calculadora.**


![](https://github.com/bavargas5/Tarea5/blob/main/IMGBN/5.PNG)


![](https://github.com/bavargas5/Tarea5/blob/main/IMGBN/5.1.PNG)


Entonces las intensidades calculadas son

![](https://github.com/bavargas5/Tarea5/blob/main/IMGBN/5.2.PNG)


Comparando con los otros calculos kas respuestas coinciden


**11. Escriba la ecuación de la corriente de Kirchhoff para la asignación de corriente mostrada en el nodo A en la figura 9-26.**

![](https://github.com/bavargas5/Tarea5/blob/main/IMGBN/6.PNG)


La ley de la corriente de Kirchhoff dice que la suma de todas las corrientes que fluyen hacia un nodo es igual a la suma de las corrientes que salen del nodo.

En este caso I1 es la corriente que entra en el punto A por lo cual nos quedaría:


![](https://github.com/bavargas5/Tarea5/blob/main/IMGBN/6.1.PNG)



**13. Determine la caída de voltaje entre los extremos de cada resistor mostrado en la figura 9-26 e indique **la polaridad real.**


![](https://github.com/bavargas5/Tarea5/blob/main/IMGBN/7.PNG)


Como lo vimos en el anterior caso, usaremos la ley de la corriente de Kirchhoff

![](https://github.com/bavargas5/Tarea5/blob/main/IMGBN/7.1.PNG)



En el nodo A, la ecuación de corriente es

![](https://github.com/bavargas5/Tarea5/blob/main/IMGBN/7.2.PNG)


Las ecuaciones se resuelven por sustitución como sigue. En primer lugar, encuentre I1 en función de I2 e I3.

![](https://github.com/bavargas5/Tarea5/blob/main/IMGBN/7.3.PNG)




Al sustituir esta expresión para I2


![](https://github.com/bavargas5/Tarea5/blob/main/IMGBN/7.4.PNG)


Ahora, sustituya el valor de I3 en amperes en la ecuación para el lazo derecho.

![](https://github.com/bavargas5/Tarea5/blob/main/IMGBN/7.5.PNG)


Con estos datos ya podemos sacar el voltaje

Usando la ley de ohm

![](https://github.com/bavargas5/Tarea5/blob/main/IMGBN/7.6.PNG)


![](https://github.com/bavargas5/Tarea5/blob/main/IMGBN/7.7.PNG)


**17. Con el método de la corriente en lazos, determine las corrientes en los lazos que aparecen en la figura 9-28.**


![](https://github.com/bavargas5/Tarea5/blob/main/IMGBN/9.PNG)


Dibujando la trayectoria de la corriente


![](https://github.com/bavargas5/Tarea5/blob/main/IMGBN/9.1.PNG)



Vamos a realizar un análisis por mallas por lo cual

Para la I1

![](https://github.com/bavargas5/Tarea5/blob/main/IMGBN/9.2.PNG)


Para I2

![](https://github.com/bavargas5/Tarea5/blob/main/IMGBN/9.3.PNG)


![](https://github.com/bavargas5/Tarea5/blob/main/IMGBN/9.4.PNG)


Resolveremos las ecuaciones por medio de una calculadora


![](https://github.com/bavargas5/Tarea5/blob/main/IMGBN/9.5.PNG)


Entonces ya obteniendo los valores, estos datos son las intensidades de las 2 mallas


![](https://github.com/bavargas5/Tarea5/blob/main/IMGBN/9.6.PNG)

**19. Determine los voltajes y sus polaridades apropiadas en cada uno de los resistores mostrados en la figura 9-28.**


![](https://github.com/bavargas5/Tarea5/blob/main/IMGBN/10.PNG)



En este caso hemos analizado las polaridades eficientemente ya que obtuvimos la corriente de ambas mallas positivas

En este caso solo buscaríamos los voltajes 



![](https://github.com/bavargas5/Tarea5/blob/main/IMGBN/10.1.PNG)









**21. Resuelva para las corrientes de lazo en la figura con su calculadora.**


![](https://github.com/bavargas5/Tarea5/blob/main/IMGBV/2.png)

![](https://github.com/bavargas5/Tarea5/blob/main/IMGBV/3.png)

**25. Escriba las ecuaciones de lazo en la forma estándar para el circuito puente T mostrado en la figura.**

![](https://github.com/bavargas5/Tarea5/blob/main/IMGBV/4.png)

![](https://github.com/bavargas5/Tarea5/blob/main/IMGBV/5.png)

**27. ¿Cuáles son los valores de corriente de rama en la figura? En cada rama, muestre la dirección real de la corriente.**

![](https://github.com/bavargas5/Tarea5/blob/main/IMGBV/6.png)

![](https://github.com/bavargas5/Tarea5/blob/main/IMGBV/7.png)

**29. Use el análisis de nodos para determinar el voltaje en los puntos A y B con respecto a tierra en la figura.**

![](https://github.com/bavargas5/Tarea5/blob/main/IMGBV/8.png)

![](https://github.com/bavargas5/Tarea5/blob/main/IMGBV/9.png)

![](https://github.com/bavargas5/Tarea5/blob/main/IMGBV/10.png)

**CAPITULO 10**

**1. El área de sección transversal de un campo magnético se incrementa, pero el flujo no cambia. ¿La densidad de flujo aumenta o disminuye?**

Disminuye, debido a que el área es inversamente proporcional a la densidad del flujo.

**3. ¿Cuál es el flujo en un material magnético cuando la densidad de flujo es de 2500x10^-3 y el área de sección transversal mide 150 cm^2?**

![](https://github.com/bavargas5/Tarea5/blob/main/IMGBV/11.png)

**5. Un imán permanente muy fuerte tiene un campo magnético de 100,000 uT. Exprese esta densidad de flujo en gauss.**

![](https://github.com/bavargas5/Tarea5/blob/main/IMGBV/12.png)

**7. ¿Cuál es la permeabilidad relativa de un material ferromagnético cuya permeabilidad absoluta es de 750x10^-6 Wb/At*m?**

![](https://github.com/bavargas5/Tarea5/blob/main/IMGBV/13.png)

## VIDEO



## CONCLUSIONES


-Estos métodos los de sustituciones algebraicas y método del determinante nos facilitan y acortan el proceso de resolver ecuaciones en algunos casos complejas y de varias variables por lo cual su uso es indispensable para resolver circuitos 


-Al utilizar el método de corriente en ramas determinamos los valores de las componentes desconocidas al igual que el análisis de nodos 


-Si tenemos polos magnéticos iguales estos se repelen y si son diferentes se atraen, podemos usar la regla de la mano derecha para indicar la dirección de las fuerzas electromagnéticas que están en un conductor  


## BIBLIOGRAFÍA


-Floyd, T. L. (2021). Principios De Circuitos Electricos C/Cd Rom (8.a ed.). PRENTICE HALL/PEARSON.


-Khan Academy. (s. f.). La terminología de los circuitos (artículo). https://es.khanacademy.org/science/electrical-engineering/ee-circuit-analysis-topic/circuit-elements/a/ee-circuit-terminology





