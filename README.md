# TAREA 4
## 1.	OBJETIVOS

	1.1	GENERAL: 


	1.2	ESPECÍFICOS:

**a.**	
		
**b.**	

**c.**	

## 2.	MARCO TEÓRICO (RESUMEN)

### CAPÍTULO 7 :

	7–1 Identificación de relaciones en serie-paralelo
	
![1](https://user-images.githubusercontent.com/93396250/146879257-c8911531-5a32-490d-b85f-8ac747a42c2a.jpg)

	
	7–2 Análisis de circuitos resistivos en serie-paralelo 

![2](https://user-images.githubusercontent.com/93396250/146879273-8012cafd-0fe9-483e-9b61-0d7cb9f5723a.jpg)


	7–3 Divisores de voltaje con cargas resistivas 

![3](https://user-images.githubusercontent.com/93396250/146879290-417be375-6821-4dd1-9812-d628f99b6cab.jpg)


	7–4 Efecto de carga de un voltímetro 
	
Cuando la resistencia interna del voltímetro no es suficientemente más grande que la resistencia del circuito entre los extremos del cual está conectado, el efecto de carga hará que el voltaje medido sea menor que su valor real. Siempre se deberá estar consciente de este efecto

EJEMPLO: 

![image](https://user-images.githubusercontent.com/93396250/146879140-8bdca9d2-1f18-4d54-9c28-5d21c2efbb96.png)
![image](https://user-images.githubusercontent.com/93396250/146879160-9f2b67df-23ec-4af3-a26f-9edf47838615.png)

	7–5 Redes en escalera
	
![5](https://user-images.githubusercontent.com/93396250/146881363-e2b6ec5b-1eb6-4779-b9f4-eff5e1701246.jpg)

	
	7–6 El puente Wheatstone 
	
![6](https://user-images.githubusercontent.com/93396250/147421142-d19e4613-2997-4b2c-85a4-bde6984247df.jpg)

	
	7–7 Localización de fallas 

Algunas técnicas de localización de fallas y la aplicación de razonamiento lógico ya se analizaron en relación tanto con circuitos en serie como con circuitos en paralelo. Una premisa básica de la localización de fallas es que se debe saber qué buscar antes de poder localizar con éxito una falla en un circuito.

EJEMPLO: 

![image](https://user-images.githubusercontent.com/93396250/146879851-db98c897-01c0-4811-a9ab-71f2c6fd9eda.png)
![image](https://user-images.githubusercontent.com/93396250/146879868-2cf24a99-813e-4937-bb1a-0b70e424dccf.png)


### CAPÍTULO 8 : 
	
La fuente de voltaje de cd es uno de los principales tipos de fuente de energía la cual proporciona un voltaje constante a una carga, incluso cuando la resistencia de ésta varía. 
		
![8](https://user-images.githubusercontent.com/93834732/146826074-82017959-43f7-447f-90c8-fe11a6aafce2.PNG)

Ninguna fuente de voltaje es ideal; sin embargo, las fuentes de potencia regulada se aproximan a la situación ideal cuando funcionan dentro de la corriente de salida especificada.

Mientras más grande es RL, en comparación con RS, menos cambio ocurre en el voltaje de salida. El voltaje de salida disminuye significativamente conforme la resistencia de la carga se reduce en comparación con la resistencia interna de la fuente.

	8–2 La fuente de corriente
	

La fuente de corriente es otro tipo de fuente de energía que idealmente suministra una corriente constante a una carga, incluso cuando la resistencia de ésta varía. Aunque en la mayor parte del trabajo de análisis se puede utilizar la fuente de corriente ideal, ningún dispositivo real es ideal

![8 1](https://user-images.githubusercontent.com/93834732/146857573-ca2e865e-4284-4bb8-8a38-e17b759e719d.PNG)

Si la resistencia interna de la fuente, RS, es mucho más grande que un resistor de carga, la fuente práctica se aproxima a la fuente ideal.

	8–3 Conversiones de fuente

En ocasiones es útil convertir una fuente de voltaje en una fuente de corriente equivalente, o viceversa.

El voltaje de fuente, VS, dividido entre la resistencia interna de la fuente, RS, da el valor de la corriente de la fuente equivalente.

![8 3](https://user-images.githubusercontent.com/93834732/146857995-08a1c24f-f6d5-48df-800c-6387f69c5fa6.PNG)

La equivalencia terminal  significa que con cualquier resistencia de carga dada que se conecte a las dos fuentes, ambas fuentes producen el mismo voltaje de carga y la misma corriente de carga.

![8 4](https://user-images.githubusercontent.com/93834732/146863689-f7c5cf51-c403-4bf8-8726-db94d60fbb0f.PNG)


La corriente de la fuente, IS, multiplicada por la resistencia interna de la fuente, RS, da el valor del voltaje de la fuente equivalente.

![8 5](https://user-images.githubusercontent.com/93834732/146863781-771f488e-0aea-416c-997f-141e60c49034.PNG)


	8–4 El teorema de superposicion 
	
El método de superposición es una forma de determinar corrientes en un circuito con múltiples fuentes dejando una fuente a la vez y reemplazando las demás fuentes por sus resistencias

El método de superposición es una forma de determinar corrientes en un circuito con múltiples fuentes dejando una fuente a la vez y reemplazando las demás fuentes por sus resistencias internas. Es importante recalcar que una fuente de voltaje ideal tiene una resistencia interna de 0 y una fuente de corriente ideal tiene una resistencia interna infinita.
Los pasos para aplicar el método de superposición son los siguientes:

*Paso 1*

Dejar una fuente de voltaje (o de corriente) a la vez en el circuito y reemplazar cada una de las demás fuentes de voltaje (o de corriente) con su resistencia interna. Para fuentes ideales, un corto representa resistencia interna de cero y una abertura representa resistencia interna infinita. 

*Paso 2*

Determinar la corriente (o el voltaje) particular que se desea justo como si hubiera sólo una fuente en el circuito. 

*Paso 3*

Tomar la siguiente fuente que haya en el circuito y repetir los pasos 1 y 2. Hacer esto con cada una de las fuentes. 

*Paso 4* 

Sumar algebraicamente las corrientes producidas por cada fuente individual para encontrar la corriente real en una rama dada. (Si las corrientes están en la misma dirección, se suman. Si están en direcciones opuestas, se restan y la dirección de la corriente resultante será la misma que la presentada por la cantidad más grande de las
cantidades originales.) Una vez determinada la corriente, ya se puede calcular el voltaje mediante la ley de Ohm.

En el siguiente ejemplo se indica de manera grafica los pasos mencionados previamente.

![8 6](https://user-images.githubusercontent.com/93834732/146864478-6fe5f784-ab70-418a-affd-ecff4dae0c79.PNG)

	8–5 Teorema de Thevenin
	
Este se usa  para simplificar un circuito a una forma equivalente estándar. Se utiliza para hacer más sencillo el análisis de circuitos complejos.

La forma Thevenin equivalente de cualquier circuito resistivo de dos terminales consta de una fuente de voltaje equivalente (VTH) y una resistencia equivalente (RTH) como se indica en el siguiente grafico.

![8 7](https://user-images.githubusercontent.com/93834732/146865219-d78949c4-4665-4cb5-8bee-89fc0beb44b2.PNG)

*"En un circuito eléctrico, el voltaje equivalente de Thevenin (VTH) es el voltaje de circuito abierto (sin carga) presente entre dos terminales de salida."*

La resistencia equivalente de Thevenin (RTH) es la resistencia total que aparece entre dos terminales en un circuito dado que tiene todas las fuentes reemplazadas por sus resistencias internas. 

Para encontrar el equivalente de Thevenin de cualquier circuito, se determina el voltaje equivalente, VTH, y la resistencia equivalente, RTH, vistos desde las terminales de salida.

![8 8](https://user-images.githubusercontent.com/93834732/146865472-c84f5a47-6fef-4301-86ad-5241a28e4fff.PNG)

![8 9](https://user-images.githubusercontent.com/93834732/146865499-4f1a8aba-f31c-48d6-a71c-363d89d1a759.PNG)

El equivalente de Thevenin de cualquier circuito depende de la ubicación de las dos terminales de salida desde donde se “ve” dicho circuito.

En muchos casos, es de cierta ayuda thevenizar sólo una parte de un circuito como se muestra en el siguiente grafico.

![8 10](https://user-images.githubusercontent.com/93834732/146866141-ee1f739d-4157-48c9-9381-95983f8e0054.PNG)

Cabe mencionar que el teorema de Thevenin tambien puede ser usado para resolver circuitos puente como el del siguiente grafico.

![8 11](https://user-images.githubusercontent.com/93834732/146866265-813d0440-6234-42f8-bb44-10d05ec9ca83.PNG)

	8–6 Teorema de Norton
	
![Diagrama en blanco (4)](https://user-images.githubusercontent.com/93834732/146870496-7afaa955-64e4-4070-8863-975d9c4cecf8.png)

En  el siguiente grafico se muestra como aplicar estos pasos.

![8 12](https://user-images.githubusercontent.com/93834732/146870554-8a25ebcc-888e-4f96-b9ea-6f5f20bb4d13.PNG)


	8–7 Teorema de Trasnferencia de Potencia Maxima
	
Este teorema se usa cuando es importante cuando se tiene que conocer el valor de la carga con la cual la fuente suministra la máxima potencia.

Para una fuente de voltaje dada, la potencia máxima se transfiere desde una fuente hasta una carga cuando la resistencia de la carga es igual a la resistencia interna de la fuente.

![8 13](https://user-images.githubusercontent.com/93834732/146870787-71c78831-fc29-43d7-aaef-a5a65f338596.PNG)

Algunas aplicaciones prácticas del teorema de transferencia de potencia máxima incluyen sistemas de audio tales como aparatos estereofónicos, radios, y sistemas de alocución pública, etc. 

	8–8 Conversiones Delta a Y (V A Y) y Y a Delta (Y A V)
	
Las conversiones entre configuraciones de circuito tipo delta y tipo Y son útiles en ciertas aplicaciones especializadas de tres terminales.

![8 14](https://user-images.githubusercontent.com/93834732/146870983-131c3537-e19d-42f6-bed7-f3ca5e287419.PNG)

*Conversión V a Y*

Cada resistor localizado en la Y es igual al producto de los resistores incluidos en dos ramas delta adyacentes, dividido entre la suma de los tres resistores en delta.

![8 15](https://user-images.githubusercontent.com/93834732/146871053-a6277f57-704b-462a-9bbe-e0d6d78cdc6e.PNG)

![8 16](https://user-images.githubusercontent.com/93834732/146871078-0bf5e523-b076-4413-82ec-23d51eaec061.PNG)

![8 17](https://user-images.githubusercontent.com/93834732/146871121-dab0b593-c516-4184-8999-f42f3d655b48.PNG)

*Conversión Y a V*

Cada resistor incluido en la delta es igual a la suma de todos los posibles productos de resistores Y tomados dos a la vez, y divididos entre el resistor Y opuesto

![8 18](https://user-images.githubusercontent.com/93834732/146871279-5354d7a3-8d1d-4238-ad5f-d3b01324b0af.PNG)		

## 3.	EXPLICACIÓN Y RESOLUCIÓN DE EJERCICIOS O PROBLEMAS

#### **CAPÍTULO 7 :**

	7-1 Identificación de relaciones en serie-paralelo
**1.  Visualice y trace las siguientes combinaciones en serie-paralelo:**
  (a) R1 en serie con la combinación en paralelo de R2 y R3
		
![Screenshot 2021-12-20 154406](https://user-images.githubusercontent.com/93826527/146830384-47201cee-f498-4b71-a460-cc283c11b37f.png)		
		
   (b) R1 en paralelo con la combinación en serie de R2 y R3
		   
![Screenshot 2021-12-20 160533](https://user-images.githubusercontent.com/93826527/146832703-3fc91a1e-7906-4894-b6a6-0e5c3823ad83.png)
		   
		   
   (c) R1 en paralelo con una rama que contiene R2 en serie con una combinación en paralelo de otros cuatro resistores
		   
![Screenshot 2021-12-20 160210](https://user-images.githubusercontent.com/93826527/146832327-d4189161-0912-4934-9775-a1989cd59b1c.png)		

**3. En cada circuito de la figura 7-62, identifique las relaciones en serie-paralelo de los resistores vistas desde la fuente.**

![Screenshot 2022-01-03 165628](https://user-images.githubusercontent.com/93826527/147984790-1a4a5896-544c-4753-9c2b-87acbd56e773.png)

(a) Las resistencias R2 y R3 están en paralelo, y las resistencias R1, R23 y R4 están en serie.
(b) Las resistencias R2, R3 y R4 están en paralelo, y, la resistencia R234 está en serie con R1.
(c) Las resistencias R2 y R3 están en paralelo, R4 y R5 también están en paralelo. Las resistencias R23 y R45 están en serie y la R1 está en paralelo con R2345.

**5. Trace el diagrama esquemático de la configuración de la tarjeta de circuito impreso mostrada en la figura 7-64 indicando valores de resistor, e identifique las relaciones en serie-paralelo.**

![Screenshot 2022-01-03 171116](https://user-images.githubusercontent.com/93826527/147985993-49d25149-2357-4caa-ab17-4bf55b4bbb8a.png)

ESQUEMÁTICO REALIZADO EN SIMULADOR MULTISIM

![Untitled Circuit-schematic](https://user-images.githubusercontent.com/93826527/147986955-7477ca80-e8ed-4a67-bfba-04e20377fbf3.png)

**7. Configure una tarjeta de circuito impreso para el circuito de la figura 7-63(c). La batería tiene que conectarse externa a la tarjeta.**

![Screenshot 2022-01-03 173723](https://user-images.githubusercontent.com/93826527/147987909-cbeaa707-5ea3-4279-9297-b0e00bea88bb.png)

	7–2 Análisis de circuitos resistivos en serie-paralelo  
	
**9. Para cada uno de los circuitos mostrados en la figura 7-62, determine la resistencia total presentada a la fuente.**

![Screenshot 2022-01-03 165628](https://user-images.githubusercontent.com/93826527/147984790-1a4a5896-544c-4753-9c2b-87acbd56e773.png)

(a) R23 = 1/(1/R2)+(1/R3) =  50 ohm

R1+R23+R4 = 50 + 56 + 27 = 133 ohm

Rt = 133 ohm

**11. Determine la corriente a través de cada resistor del circuito de la figura 7-62; calcule en seguida cada caída de voltaje.**

Rt = 133 ohm 

It = Vs / Rt = 11.28 mA

La corriente que pasa por la resistencia R1 y R4 es It, ya que la corriente es la misma para resistencias conectadas en serie.

En R2 y R3 existe una división de corriente y como son resistencias de igual valor, tienen la misma corriente.

I(R2) = I(R3) = It * (Rt/Rx) = 15 mA 

**15. Determine el voltaje en cada nodo con respecto a tierra en la figura 7-67.**

![Screenshot 2022-01-03 200841](https://user-images.githubusercontent.com/93826527/147996590-b56b2a62-e541-4f07-b2f7-828e0d6bd3d0.png)

**17. En la figura 7-68, ¿cómo determinaría el voltaje entre los extremos de R2 por medición sin conectar directamente un medidor entre los extremos del resistor?**

![Screenshot 2022-01-03 201219](https://user-images.githubusercontent.com/93826527/147996802-d9109c6e-7e2a-4523-ab44-a0cd29648832.png)

Se toma en cuenta que el voltaje es el mismo en conexiones en paralelo, por loc ual entre R1, R2 y R3 se reparte el mismo voltaje de la fuente, posterior a eso se deberia sacar la resistencia equivalente y sabiendo el Vs, aplicando fórmula de divisor de voltaje se puede encontrar el voltaje en R2, sin usar un equipo de medición.

**19. Determine la resistencia del circuito mostrado en la figura 7-68 como se ve desde la fuente de voltaje.**

![Screenshot 2022-01-03 201219](https://user-images.githubusercontent.com/93826527/147996802-d9109c6e-7e2a-4523-ab44-a0cd29648832.png)

R123 = R1 + R2 + R3 = 716 kΩ

R56 = R5 + R6 = 100 GΩ

Rt = 1/ ((1/R123)+(1/R56)+(1/R4)) = 417.25 kΩ






	7–3 Divisores de voltaje con cargas resistivas 

**25. Un divisor de voltaje está compuesto por dos resistores de 56 kΩ y una fuente de 15 V. Calcule el voltaje de salida sin carga ¿Cuál será el voltaje de salida si se conecta un resistor con carga de 1.0 MΩ a la salida?**

	Vsalida (sin carga) 

   ![image](https://user-images.githubusercontent.com/93396250/147433159-af8fd1ff-1a5c-4e83-85c4-3dc2fedafb04.png)

	
	Para Vsalida con carga se calcula R2 y RL en paralelo, 
	para luego con esa resistencia hacer los cálculos de Vsalida con carga

   ![image](https://user-images.githubusercontent.com/93396250/147433191-5f66b106-d83c-4fbe-b377-bb0402136fe1.png)
	
**27. Cuál de dos cargas, una de 10 kΩ y otra de 47 kΩ, provocará una disminución más pequeña en el voltaje de salida de un divisor de voltaje dado**

	Respuesta: Con la resistencia de 47kΩ
	
	Esto porque mientras más grande es RL en comparación con R2,
	menos se reduce el voltaje de salida con respecto a su valor sin carga.

**29. En la figura 7-74, determine el voltaje de salida con una carga de 33 kΩ conectada entre A y B**

![image](https://user-images.githubusercontent.com/93396250/147421770-b8eff7a4-16fb-4bd2-a1dd-02e793c30032.png)

	Primero se calcula R2+3 || RL y luego se calcula el voltaje de salida con carga
	
![image](https://user-images.githubusercontent.com/93396250/147433572-2b543a2f-f74c-46cc-9337-6a9ac9d8ca07.png)


**31. Determine los valores de resistencia para un divisor de voltaje que debe satisfacer las siguientes especificaciones: la corriente extraída de la fuente sin carga no debe exceder de 5 mA; el voltaje de fuente tiene que ser de 10 V, y las salidas requeridas deben ser de 5 y 2.5 V. Trace el circuito. Determine el efecto en los voltajes de salida si se conecta una carga de 1.0 kΩ a cada toma, una a la vez**

	Asumimos la estructura del divisor de voltaje

![Untitled (5)](https://user-images.githubusercontent.com/93396250/148011482-8ed7e7a0-e8aa-4d36-9bf4-e506c8d26c78.jpg)

	1. La corriente máxima sin carga no debe exceder los 5mA, por lo tanto
	
![image](https://user-images.githubusercontent.com/93396250/148011598-a1d0149a-c0a0-4be1-a48a-d6e18f9686d4.png)


	2. Las salidas requeridas deben ser de 5 y 2.5 V. Debido a esto las resistencias R2 y R3 deben ser iguales ya que tienen el mismo voltaje
	
![image](https://user-images.githubusercontent.com/93396250/148011606-89f4176e-234d-4e9a-b782-0e5c3b349666.png)

	El voltaje que cruza a través de R2 es 5V – 2.5V = 2.5V. 
	Por tanto, R2 y R3 deben ser iguales ya que tienen el mismo voltaje. R_2=R_3     [2]
	Suponiendo una resistencia R1 = 1kΩ entonces tomando en cuenta [1] y [2]

![image](https://user-images.githubusercontent.com/93396250/148011617-3d43f51a-55fc-4bb4-b051-d4d063a1416e.png)


	3. Cuando la carga de RL = 1 kΩ esta con el V1 entonces el circuito queda de la siguiente manera:

![Untitled (6)](https://user-images.githubusercontent.com/93396250/148011646-b7ed40fb-0992-4545-9d96-28071faac7f2.jpg)


	Las Resistencias R3 y RL están en paralelo, por lo tanto, se encuentra la Req ||, para luego calcular el voltaje de salida

![image](https://user-images.githubusercontent.com/93396250/148011668-8373ce26-ef82-4f28-b844-dbd79653d5dc.png)

	4. Cuando la carga de RL = 1 kΩ está conectada a V2 entonces el circuito armado queda de la siguiente manera:

![Untitled (7)](https://user-images.githubusercontent.com/93396250/148011674-cea8e16e-4652-4155-9e39-ad54a83d8cb9.jpg)

	
	Si R2 + R3 y RL están en paralelo y entonces la resistencia equivalente es

![image](https://user-images.githubusercontent.com/93396250/148011692-13f87ab2-239d-4760-ba1d-1d16e34280c4.png)


	Respuesta = Por tanto el voltaje de salida para 2.5 V en V1 y 5v en V2 será de 1.818V y 3.33V respectivamente gracias al efecto de la carga RL
	
	
	
	
	
	
**33. La figura 7-76 muestra un circuito polarizador de cd para un amplificador de transistor de efecto de campo. La polarización es un método común empleado para establecer ciertos niveles de voltaje de cd para la operación apropiada de un amplificador. Aunque no se espera que usted conozca los amplificadores con transistores en este momento, los voltajes y las corrientes de cd presentes en el circuito pueden ser determinados con métodos ya conocidos**

   (a)  Encuentre VG y VS

   (b)  Determine I1, I2, ID, e IS

   (c)  Encuentre VDS y VDG
   
![image](https://user-images.githubusercontent.com/93396250/147421849-2bb05047-46af-4c0a-886d-0d9caa0cc53b.png)


**LOS CIRCUITOS COMPARADORES NO SON TEMA DE ESTE PARCIAL POR LO QUE AUN NO SE VEN EN CLASE, POR ELLO (Y UNA VEZ CONSULTADO CON EL TUTOR) EL EJERICIO NO SE REALIZA**
	
	
	7–4 Efecto de carga de un voltímetro 
	
**35. ¿En cuál de los siguientes intervalos de voltaje presentará un voltímetro la mínima carga que haya en un circuito?**

La respuesta es a) ya que en 1 (V) al ser la cantidad más baja de voltaje en el circuito, es casi seguro que la resistencia interna del voltímetro, será mas grande que la resistencia del circuito y esto nos dará el valor real de carga en el circuito.

**37. El voltímetro descrito en el problema 36 se utiliza para medir voltaje entre los extremos de R4 en la figura 7-62(a).**

**(a) ¿Qué intervalo se deberá utilizar?**

Se debe usar el intervalo de 0.5 (V), ya que su resistencia interna será de 10 (kohm), siendo muy superior a los 27 (ohm) de la R4 a medir.

**(b) ¿En cuánto se reduce el voltaje medido por el medidor con respecto al voltaje real?**

R23 = 50 (ohm)

R123 = 106 (ohm)

V4 = (R4/(R4+R123)) * Vs = 304.5 (mV)

**R4 en paralelo con el voltímetro**

R4RM = (R4RM)/(R4+RM) = 26.93 (ohm)

V4 = (R4RM)/(R123+R4RM) = 202.5 (mV)




	7-5 Redes en escalera
	
	7–6 El puente Wheatstone
	
	7–7 Localización de fallas 



#### **CAPÍTULO 8 :**
	8–3 Conversiones de fuente
	
**1. Una fuente de voltaje tiene los valores VS = 300 V y RS = 50 (ohm). Conviértala en una fuente de corriente equivalente. **

Is = Vs / Rs = 6 (A)

![Screenshot 2022-01-03 205908](https://user-images.githubusercontent.com/93826527/147999684-23b6f10f-45cf-491f-9ead-2d1493e6a9c0.png)

**3. Una batería tipo D nueva tiene entre sus terminales un voltaje de 1.6 V y puede suministrar hasta 8.0 A a un cortocircuito durante muy poco tiempo. ¿Cuál es la resistencia interna de la batería?**	

Rs = Vs / Is = 0.2 (ohm)

**5. Una fuente de corriente tiene una IS de 600 mA y una RS de 1.2 kohm. Conviértala en una fuente de voltaje equivalente. **

Vs = Is * Rs = 720 (V) 

![Screenshot 2022-01-03 211012](https://user-images.githubusercontent.com/93826527/148000374-b23f5f95-d050-4d8d-824e-055c14f53bd4.png)


	
	8–4 El teorema de superposición 
	
**7. Con el método de superposición, encuentre la corriente a través de R5 en la figura 8-69.**

![image](https://user-images.githubusercontent.com/93396250/147422579-5b61b215-1874-4b0d-a742-39090c59e6ad.png)

	Sustituyendo la fuente de voltaje de 3V

![image](https://user-images.githubusercontent.com/93396250/147536475-9cb95235-ccbb-4bad-953c-7ba9eedaddc4.png)


	Primero se halla la corriente obteniendo resistencias equivalentes y por la Ley de Ohm 	
	
![image](https://user-images.githubusercontent.com/93396250/147535446-e5ddb8c1-9b80-4fa2-ab39-41ab06cb6a1a.png)

	Por tanto la corriente que fluye por el circuito es:
	
![image](https://user-images.githubusercontent.com/93396250/147537209-0256f1c8-3753-4636-a518-b00c2670ec67.png)


	La corriente que fluye por R3 sera	
	
![image](https://user-images.githubusercontent.com/93396250/147537234-2f32f815-0fc5-46b7-a499-702e83ae216d.png)


	La corriente que fluye por R5 sera

![image](https://user-images.githubusercontent.com/93396250/147537321-fc27a15a-d510-4cc1-9b23-5006920c0e61.png)



	Sustituyendo la fuente de voltaje de 2V
	
![image](https://user-images.githubusercontent.com/93396250/147536519-934be664-1f4d-4916-bcde-2c0fc88ab109.png)



	Primero se halla la corriente obteniendo resistencias equivalentes y por la Ley de Ohm 

![image](https://user-images.githubusercontent.com/93396250/147535522-9c01a0e2-a243-4865-ab6d-8896c1b85ba5.png)


	Por tanto la corriente que fluye por el circuito es:

![image](https://user-images.githubusercontent.com/93396250/147538577-4fd01bc8-37f8-46af-8e05-ca0f503891fe.png)

	La corriente que fluye por R5 sera

![image](https://user-images.githubusercontent.com/93396250/147537362-63fb2770-37fa-410b-88d0-47e82ea9de01.png)



	Por lo que la corriente total en R5 sera 

![image](https://user-images.githubusercontent.com/93396250/147537377-cb804df0-ec28-4c99-8d1f-4387dc77c291.png)

**9. Con el teorema de superposición, determine la corriente a través de R3 en la figura 8-70.**

![image](https://user-images.githubusercontent.com/93396250/147422581-cf9d9228-4c99-46c2-84be-a70ed444b77e.png)


**11. En la figura 8-72 se muestra un circuito comparador. El voltaje de entrada, VENTRADA, se compara con el voltaje de referencia, VREFERENCIA, y se genera una salida negativa si VREFERENCIA > VENTRADA; de lo contrario es positiva. El comparador no carga a una u otra entrada. Si R2 es de 1.0 kÆ, ¿cuál es el intervalo del voltaje de referencia?**

![image](https://user-images.githubusercontent.com/93396250/147422591-3b66d26c-0e49-46a1-93cd-4cba9336cc89.png)

**LOS CIRCUITOS COMPARADORES NO SON TEMA DE ESTE PARCIAL POR LO QUE AUN NO SE VEN EN CLASE, POR ELLO (Y UNA VEZ CONSULTADO CON EL TUTOR) EL EJERICIO NO SE REALIZA**
	

**13. Determine el voltaje del punto A al punto B en la figura 8-73**

![image](https://user-images.githubusercontent.com/93396250/147542831-d6d13be2-05e1-4a63-9149-254995a28cbd.png)


**15. La figura 8-75 muestra dos redes en escalera. Determine la corriente producida por cada una de las baterías cuando se conectan las terminales A (A a A) y las terminales B (B a B).**


![image](https://user-images.githubusercontent.com/93396250/147542907-f0d6fe1b-3aa5-455b-b4d4-767b2cf621dc.png)



	8–5 Teorema de Thevenin
	
**17. Con el teorema de Thevenin, determine la corriente a través de la carga RL en la figura 8-77.**

![image](https://user-images.githubusercontent.com/93396250/147422645-949c3d0c-b053-42a0-902d-522d23832393.png)

**19. Determine el equivalente de Thevenin para el circuito externo al amplificador de la figura 8-79.** 

![image](https://user-images.githubusercontent.com/93396250/147422659-edd0e11b-81c5-4ac0-8029-9de2523c5e17.png)


**LOS CIRCUITOS CON AMPLIFICADOR NO SON TEMA DE ESTE PARCIAL POR LO QUE AUN NO SE VEN EN CLASE, POR ELLO (Y UNA VEZ CONSULTADO CON EL TUTOR) EL EJERICIO NO SE REALIZA**

**21. Determine la corriente a través del resistor de carga en el circuito puente de la figura 8-81.**

![image](https://user-images.githubusercontent.com/93396250/147422667-53b2c2ce-a93c-4931-b8c6-4770993ba263.png)

	
	
	8–6 Teorema de Norton 
	
	
	8–7 Teorema de transferencia de potencia máxima
	
	
	8–8 Conversiones delta a  Y (Δ a Y) y Y a delta (Y a Δ)


## 4. VIDEO
			
[![Presentación Tarea 1](https://img.youtube.com/vi/2iV6VzArCmY/0.jpg)](https://www.youtube.com/watch?v=2iV6VzArCmY)
	
## 5.	CONCLUSIONES
        

## 6.	BIBLIOGRAFÍA

Floyd, T. L. (2007). PRINCIPIOS DE CIRCUITOS ELÉCTRICOS - Octava edición. México: PEARSON EDUCACIÓN.

