# Informe-tarea-4
***

**OBJETIVOS**

***
**OBJETIVO GENERAL**
***
Comprender los temas sobre circuitos en serie-paralelo, teoremas de circuitos y conversiones, mediante la lectura de los capítulos 7 y 8 del libro "Principios de circuitos eléctricos" de Floyd, para aplicarlos en la práctica y resolución de ejercicios.
***
**OBJETIVOS ESPECIFICOS**
***
- Resumir los temas que se encuentran en el capítulo 7 y 8 del libro "Principios de circuitos eléctricos" de Floyd, mediante el uso de mapas conceptuales.

- Emplear los conocimientos aprendidos con la lectura del capítulo 7 y 8 para la resolución de los ejercicios pares propuestos en el libro "Principios de circuitos eléctricos" de Floyd.

- Explicar mediante un video 4 ejercicios pares del libro "Principios de circuitos eléctricos" de Floyd
***
**MARCO TEÓRICO**
***
CAPITULO 7
***
![circuitos sereie-paralelo](https://user-images.githubusercontent.com/105259459/176674756-28253c34-52d3-4ea7-b5b7-325ded3de6a8.png)

![Circuitos serie parleo 2](https://user-images.githubusercontent.com/105259459/176674832-0e64b645-aba2-4e89-8b22-4b809ed00fea.png)
***
CAPITULO 8 
***
![Teorema de circuitos y converiones 1](https://user-images.githubusercontent.com/105259459/176675051-57da8739-c091-46d4-9ac3-5dbf3e428450.png)

![teorema3](https://user-images.githubusercontent.com/105259459/176694094-e6a1adc3-fe20-430e-b5ad-5b61a6886aea.png)

![Teorema4](https://user-images.githubusercontent.com/105259459/176703135-a50125b1-cf62-4748-8708-c7ee4992385e.png)

![teorema5](https://user-images.githubusercontent.com/105259459/176710501-ba137a6f-f210-424e-87d0-7025d555d69a.png)

![teorema6](https://user-images.githubusercontent.com/105259459/176715076-c96b9456-a543-40bc-b9df-efcd1751d27c.png)

***
**EXPLICACIÓN Y RESOLUCIÓN DE EJERCICIOS O PROBLEMAS**
***
CAPITULO 7
***
**Identificación de relaciones en serie-paralelo**

2. Visualice y trace los siguientes circuitos en serie-paralelo:

 (a) Una combinación en paralelo de tres ramas, cada rama con dos resistores en serie

![image](https://user-images.githubusercontent.com/105259459/176685599-901259ab-de3b-43b7-9814-60df135cd5f2.png)

 (b) Una combinación serie de tres circuitos en paralelo, cada circuito con dos resistores
 
 ![image](https://user-images.githubusercontent.com/105259459/176685675-e7cd31ae-ed83-4526-81c8-d5e4c7f9d0b3.png)

4. En cada uno de los circuitos de la figura 7-63, identifique las relaciones en serie-paralelo de los resistores vistas desde la fuente

![image](https://user-images.githubusercontent.com/105259459/176685871-43ab0897-791a-4097-a6bc-7a7ddcdf2550.png)

a R1+ R2 +R3||R4

b || R1 + R4 ||+ || R3+R2||

C R1 +R2+R3||R4+R8||R5+R6+R7

6. Desarrolle un diagrama esquemático de la tarjeta de circuito impreso de doble cara mostrada en la figura 7-65, y marque los valores de resistor.

![image](https://user-images.githubusercontent.com/105259459/176686102-f1be9818-a3ef-4e4a-88fd-71e3da3f1579.png)

![image](https://user-images.githubusercontent.com/105259459/176686188-8c5712e4-0e97-477b-ac37-6f6370474b2b.png)

**Análisis de circuitos resistivos en serie-paralelo**

8. Un cierto circuito se compone de dos resistores en paralelo. La resistencia total es de 667 ohmios. Uno de los resistores es de 1.0 kohm. ¿Cuál es el otro resistor?
2 RESISTORES

RT  667 ohmios

1RESITOR 1.kohm

667 ohm = 1/((1/1000ohm +1/R2)) 

R2(99.99OHM)=0.1499OHM 

R2= 0.1499/99.99

R2= 1.49 mOHM

10. Repita el problema 9 para cada uno de los circuitos mostrados en la figura 7-63
(Para cada uno de los circuitos mostrados en la figura 7-62, determine la resistencia total presentada a la fuente)

![image](https://user-images.githubusercontent.com/105259459/176686486-385ee399-d953-4e3c-9ed4-9a968345954c.png)

a) R1+ R2 +R3||R4

1k ohm + 1kohm + 1/(1/2.2k ohm + 1/3.3)

R= 3.32 Kohm

b) || R1 + R4 ||+ || R3+R2||

1/(1/1Mohm +1/1 Mohm) + 1/(1/6.2Mohm +1/3.3)

= 2.65 Mohm

c) R1 +R2+R3||R4+R8||R5+R6+R7

1kohm +1komh+ 1/(1/10 komh +1/4.7 komh)+ 1/(1/1.8 komh +1/3.3 komh)+ 6.8 komh +6.8 komh

=19.55 kOHM

12. Determine la corriente a través de cada resistor en cada circuito de la figura 7-63; luego calcule cada caída de voltaje.

![image](https://user-images.githubusercontent.com/105259459/176686818-41e4a0f4-7ce9-4e2a-8842-3efb41c11d1d.png)

a)  1 V   

Rt= 3.32 Kohm

Ix = V/Rx

IR1 =1v/1kohm

IR1= 1 m A

IR2= 1v/1kohm

IR2= 1 m A

IR3= 1V/2.2 kohm 

IR3 = 0.45 m A

IR4= 1V/3.3 kohm 

IR4 = 0.3 m A

IT = 1 m A +1 m A +0.45 m A+0.3 m A

IT = 2.75 A 

1/3.32 =  0.30 m A

CAIDAS DE VOLTAJE

Vx = Ix * Rx 

V1=  0.30 m A *  1kohm = 0.3v 

V2=  0.30 m A *  1kohm = 0.3v 

V3= 0.30 m A *2.2 kohm=0.66v

V4= 0.30 m A *3.3 kohm= 0.99v

b)  2 V 

Rt= 2.65 Mohm

IT= 2/2.65 = 0.75 micro A

Ix = V/Rx

IR1 =2v/1Mohm 

IR1= 2 micro A

IR2= 2v/3.3Mohm

IR2= 6 micro A

IR3= 2V/6.2 Mohm 

IR3 = 0.32 micro A

IR4= 2V/1 Mohm 

IR4 = 2 micro A

IT = 2 micro A +6 micro A +0.32 micro A +2 micro A

IT = 10.32 micro A 

CAIDAS DE VOLTAJE 

Vx = It * Rx 

V1=  0.75 micro A *  1Mohm  = 0.75v 

V2=  0.75 micro A *  3.3Mohm = 0.47v

V3= 0.75 micro A *2.2 Mohm=1.65V

V4= 0.75 micro A *1Mohm = 0.75v

c) 5 V    

Rt= 19.55 kOHM

IT= 5/19.55 = 0.2 m A

Ix = V/Rx

IR1 =5v/1 kohm 

IR1= 5 m A

IR2= 5v/1 kohm

IR2= 5 m A

IR3= 5V/10 kohm

IR3 = 0.5 m A

IR4= 5V/4.7  kohm 

IR4 = 0.1 m A

IR5= 5V/3.3  kohm

IR5 = 1.5 m A

IR6= 5V/6.8  kohm 

IR6 = 0.0735 m A

IR7= 5V/6.8  kohm

IR7 = 0.0735  m A

IR8= 5V/1.8  kohm 

IR8 = 2.7  m A

IT = 2.7  m A+0.0735  m A +0.0735 m A+1.5 m A+0.1 m A +0.5 m A+0.5 m A+5 m A

IT = 9.94 m A  

CAIDAS DE VOLTAJE 

Vx = It * Rx 

V1=  0.2 m A *  1 kohm  = 0.2v 

V2=  0.2 m A *  1 kohm = 0.2v

V3= 0.2 m A *10 kohm =2V

V4= 0.2 m A *4.7  kohm = 0.94v

V5= 0.2 m A *3.3  kohm = 0.66v

V6= 0.2 m A *6.8  kohm = 1.36v

V7= 0.2 m A *6.8  kohm = 1.36v

V8= 0.2 m A *1.8  kohm = 0.36v

14. Determine la resistencia entre A y B en la figura 7-67 sin la fuente

![image](https://user-images.githubusercontent.com/105259459/176687877-646ed6ca-9a50-4333-840e-dcbe8960aded.png)

NODO A 

100v-v1/10 k Ohm +v1/4.7k ohm =0 

4.7(100-v1) +10v1=0

470-4.7v1 +10v1=0

5.3v1=-470

V1=88.67 m V 

Nodo B

V2/5.6 +v2-0.08867  /4.7

4.7v2 + 5.6(V2- 88.67)

11.3V2= 0.4965

V2 =43.64  m V 

RAB = 4.7 + 1/(1/81/10 + 1/5.6) 

RAB= 9.93 k OHM 

16. Determine el voltaje en cada nodo con respecto a tierra en la figura 7-68

![image](https://user-images.githubusercontent.com/105259459/176688127-b6522dce-492c-440c-9081-0aa9eb355f5e.png)

NODO 1 

V1-50/(100+560) + V1/56 =0 

56(V1-50) +660(V1) =0

56V1 -2800 + 660V1=0

716V1=2800

V1= 3.91 m V

NODO 2

50 + V1 /660 +V2/R4=0

50+3.91/660 +V2/R4 =0

V2/1 M Ohm = 0.08168 m V

V2= 81.6 K V 

NODO 3

V1-V2+V3/1 M OHM + V3/100 k Ohm = 0

(3.91 m V +81.6 K V + v3 ) 1 M ohm + v3/100 k Ohm = 0

1(3.91 m V +81.6 K V + v3 )+ 10 v3 =0

11v3 = 81.60000931

V3= 7.41 V

18. Determine la resistencia del circuito mostrado en la figura 7-67 como se ve desde la fuente de voltaje.

![image](https://user-images.githubusercontent.com/105259459/176688502-2bee5e94-de60-4d85-994e-7bc3457ba589.png)

Rt = 4.7 k Ohm + 1/(1/10 +1/5.6) + 1 +1/(1.8+1.0) 

Rt = 9.93 m Ohmios 

20. Determine el voltaje, VAB, en la figura 7-69.

![image](https://user-images.githubusercontent.com/105259459/176688621-d874ba9a-16a3-4e0d-a564-de3cc00dce41.png)

Re (AB)

R4=100 * 560/1340

R4= 41.8v

R8= 100 * 100/1340

R8=7.5 v

R7= 100 * 680/1340

R7=50.7 V

Re (AB)= 41.8v+7.5 v+50.7 V

 Re (AB)=100V
 
22. En la figura 7-71, determine la resistencia entre el nodo A y cada uno de los demás nodos (RAB, RAC, RAD, RAE, RAF, y RAG).

![image](https://user-images.githubusercontent.com/105259459/176688776-e7042bfc-8bac-4c6e-806a-9abfb08a80b7.png)

RA = r1+r8

RA= 1+4.7 = 5.7 k OHM 

RB= 1+2.2

RB= 3.2 k OHM 

RC= 2.2+3.3+1+4.7

RC= 11.2 k OHM

RD=1+2.2

RD= 3.2 k ohm

RE= 2.2 +3.3 

RE= 5.5 K ohm

RF = 4.7+3.3

RF= 8 k ohms

RG = 4.7+3.3

RG= 8 k ohms

RAB= 5.7 k OHM+ 3.2 k OHM= 8.9k ohm

RAC=5.7 k OHM+11.2 k OHM=16.9 k ohm

RAD=5.7 k OHM+3.2 k ohm=8.9 k ohm

RAE=5.7 k OHM+5.5 K ohm=11.2 k ohm

RAF=5.7 k OHM+8 k ohms=13.7 k ohm

RAG=5.7 k OHM+8 k ohms = 13.7 k ohm

24. Determine el valor de cada resistor mostrado en la figura 7-73.

![image](https://user-images.githubusercontent.com/105259459/176689053-d14db106-b15d-4be4-af93-d3e102064e5d.png)

**Divisores de voltaje con cargas resistivas**

26. La salida de una batería de 12 V se divide para obtener dos voltajes de salida. Se utilizan tres resistores de 3.3 kOHM para proporcionar dos tomas. Determine los voltajes de salida. Si se conecta una carga de 10 kOHM a la más alta de las salidas, ¿cuál será su valor con carga?

Voltaje de salida

Vs= 3.3(6.6)/6.6+3.3

Vs= 2.2 m V 

2.2m V X 10 Kohm/6.6+3.3

= 2.22 K V  

28. En la figura 7-74, determine el voltaje de salida sin carga entre las terminales de salida. Con una carga de 100 kOHM conectada de A a B, ¿cuál es el voltaje de salida?

![image](https://user-images.githubusercontent.com/105259459/176689244-cdc8723d-c0ab-4f6a-bd81-937e7e5c2b86.png)

R1= 10K Ohms

R2+R3= 15.12 K OHMS

V= 10K Ohms(15.12 K OHMS) /15.12 K OHMS+10K Ohms

V=6.01 m V 

30. En la figura 7-74, determine la corriente continua extraída de la fuente sin carga entre las terminales de salida. Con una carga de 33 kOHM, ¿cuál es la corriente extraída?

![image](https://user-images.githubusercontent.com/105259459/176689434-d818f569-95e1-4f47-b9dd-fab4c3291723.png)

V = IXR 

I= V/RT      I= 22V/18.3k OHM = 1.20 m A 

I= V/RT      I= 22V/33 k ohm= 0.6 m A La corriente extraída 

32. El divisor de voltaje de la figura 7-75 tiene una carga controlada por interruptor. Determine el voltaje en cada toma (V1, V2 y V3) para cada posición del interruptor

![image](https://user-images.githubusercontent.com/105259459/176675512-22f285a7-7107-4fc0-a4bf-73430441da82.png)

a) 

R=R2+R3+R4=10KΩ+10KΩ+10KΩ=30KΩ

R‖RL=(R*RL)/(R+RL) =(30KΩ*68KΩ)/(30KΩ+68KΩ) =20,82KΩ

V1=[(R‖RL)/ (R1+ R‖RL)] Vs= (20,82KΩ/30.82 KΩ)120V=81,06V

b) 

R=R1+R2=10KΩ+10KΩ=20KΩ

Rs=R3+R4=10KΩ+10KΩ=20KΩ

Rs‖RL=(R*RL)/(R+RL) =(20KΩ*68KΩ)/(20KΩ+68KΩ) =15,45KΩ

V1=[(Rs‖RL)/ (R+ Rs)] Vs= (15,45KΩ /20KΩ+15,45KΩ)120V= 52,30 V

c)

 R=R1+R2+R3=10KΩ+10KΩ+10KΩ=30KΩ
 
R4‖RL=(R4*RL)/(R4+RL) =(10KΩ*68KΩ)/(10KΩ+68KΩ) =8,72 KΩ

V1=[(R4‖RL)/ (R+ R4‖RL)] Vs= (8,72 KΩ /38,72 KΩ)120V=27,02V

*34. Diseñe un divisor de voltaje que produzca una salida de 6 V sin carga y un mínimo de 5.5 V entre los extremos de una carga de 1.0 kΩ. El voltaje de fuente es de 24 V y la corriente extraída sin carga no debe exceder de 100 mA

Vx=(Rx/RT) Vs

RT=(Rx/Vx) Vs=(1kΩ/6V)24V=4kΩ

R1=4kΩ-1kΩ=3kΩ

![image](https://user-images.githubusercontent.com/105259459/176675926-481ca3f5-7ca1-44f3-b7e3-98ecc0a0e9df.png)

**Efecto de carga de un voltímetro**

36. Determine la resistencia interna de un voltímetro de 20,000 Ω/V en cada uno de los siguientes ajustes de intervalo. 

(a) 0.5 V 

 (b) 1 V 
 
(c) 5 V

(d) 50 V

(e) 100 V 

(f) 1000 V

38. Repita el problema 37 si se utiliza el voltímetro para medir voltaje entre los extremos de R4 en el circuito de la figura 7-62(b).

**Redes en escalera**

40. Determine la resistencia total y el voltaje en los nodos A, B y C de la red en escalera mostrada en la figura 7-78

![image](https://user-images.githubusercontent.com/105259459/176676487-af695d84-5f0f-42a9-8524-14a28f0f0423.png)

Rb=R4(R5+R6) /(R4+(R5+R6)) =(2,2kΩ*2KΩ) /4,2kΩ=1.05kΩ

Ra= R2(R3+Rb) /(R2+(R3+Rb)) =(2,2kΩ*2,05kΩ) /4,25kΩ=1.06kΩ

RT=R1+Ra=5,6kΩ+1.06kΩ=6.66 kΩ

IT=Vs/RT=18V/6,66 kΩ=2,7mA

I2=Rb/(R2+Rb) IT=1.05kΩ/(2.2kΩ+1.05kΩ) *2,7mA =0,87 mA

I3=2,7mA - 0,87 mA =1,83 mA

I4=Ra/(R4+Ra) I3=1.06kΩ/(2.2kΩ+1.06kΩ) *2,7mA =0,88 Ma

I5=I6=1.83Ma-0,88ma=0,95Ma

Nodo A

VA=I2*R2=0,87 Ma*2,2kΩ=1,914V

Nodo B

VB= I4*R4=0,88 Ma*2,2kΩ=1,94V

Nodo C

VC= I6*R6=0,95Ma*1KΩ=0,95V

42. En la figura 7-79, ¿cuál es el voltaje entre los extremos de cada resistor con 10 V entre A y B?

![image](https://user-images.githubusercontent.com/105259459/176676813-38d6a476-34e2-46b2-b84b-49953f566e4e.png)

Rb=R4(R5+R6+R7) /(R4+(R5+R6+R7)) =(820Ω*880Ω) /1700Ω=424,47Ω

Ra= R2(R3+Rb+R8) /(R2+(R3+Rb+R8)) = (820Ω *864.47Ω) /1684.47Ω=420.82Ω

RT=R1+Ra+R9=620.82 Ω

Vx=(Rx/RT) Vs= (100/620.82 Ω)10V=1.61 V

Vx=(Rx/RT) Vs= (220/620.82 Ω)10V=3.55 V

Vx=(Rx/RT) Vs= (680/620.82 Ω)10V=10.95 V

Vx=(Rx/RT) Vs= (820/620.82 Ω)10V=13.21 V

44. Determine VSALIDA para la red R/2R en escalera mostrada en la figura 7-81 para las siguientes condiciones: 

![image](https://user-images.githubusercontent.com/105259459/176677166-6fee2f4c-3d95-4702-9902-f12e6d401b90.png)

(a) Interruptor SW2 conectado a +12 V y los demás conectados a tierra

R1‖R2=(R1*R2) /(R1+R2) =(24kΩ*24kΩ) /(24kΩ+24kΩ) =12kΩ

Ra=12kΩ+12kΩ=24kΩ

R5‖R6=(R5*R6) /(R5+R6) =(24kΩ*12kΩ) /(24kΩ+12kΩ) =8kΩ

Rb=8kΩ +12kΩ = 20kΩ

Vsalida=(R8/Rb+R8) Vs= (24/44)10=5.25 V

(b) Interruptor SW1 conectado a +12 V y los demás conectados a tierra

R3‖R4=(R3*R4) /(R3+R4) =(24kΩ*12kΩ) /(24kΩ+12kΩ) =8kΩ

Rb=8kΩ +12kΩ = 20kΩ

Rb‖R6=(Rb*R6) /(Rb+R6) =(24kΩ*20kΩ) /(24kΩ+20kΩ) =11kΩ

Ra=23 kΩ

Vsalida=(R8/Ra+R8) Vs= (24/47)10=5.10 V

**El puente Wheatstone**

46. Se conecta un resistor de valor desconocido a un circuito puente Wheatstone. Los parámetros del puente en equilibrio se establecen como sigue: RV =18 kΩ y R2/R4 = 0.02. ¿Cuál es RX?

Rx=RV(R2/R4)

Rx=18KΩ(0,02)=360Ω

48. Determine el voltaje de salida para el puente desequilibrado mostrado en la figura 7-83 a una temperatura de 60 C. La característica de resistencia según la temperatura del termistor se muestra en la figura 7-60

![image](https://user-images.githubusercontent.com/105259459/176677822-cb0ba192-4b61-4153-b2a1-fb10153284af.png)

![image](https://user-images.githubusercontent.com/105259459/176677824-efbf184c-ca80-46fd-afc5-373d5d2698d1.png)

Su resistencia a 60° C es 5kΩ

ΔVsalida ≡ ΔRtermisor(Vs/4R)=5kΩ(9V/27kΩ)=1.66 V

**Localización de fallas**

50. ¿Son correctas las lecturas del medidor mostrado en la figura 7-85?

![image](https://user-images.githubusercontent.com/105259459/176678025-70aaee89-0853-4f29-91a2-3786ae5f9bb7.png)

R4‖R5=(100kΩ*10kΩ)/( 100kΩ+10kΩ)=9,10kΩ

V=(9,10/42,10)18=3,89V

Este valor es incorrecto, y, como es más alto de lo que debería ser, o R4 o R5 está probablemente abierto

R1‖R2=(27kΩ*47kΩ)/( 27kΩ+47kΩ)=17,15kΩ

V=(17,15/50,15)18=3,89V=6.15 V

Este valor es incorrecto, y, como es más alto de lo que debería ser, probablemente tenga una abertura parcial que provoca una resistencia más alta de lo normal

52. Vea los medidores ilustrados en la figura 7-87 y determine si hay una falla en el circuito. Si la hay, identifíquela

![image](https://user-images.githubusercontent.com/105259459/176678319-99bfd836-4bfb-45e0-8a3d-bad7460b49f6.png)

54. Si en la figura 7-89 R2 se abre, ¿qué voltajes se leerán en los puntos A, B y C?

![image](https://user-images.githubusercontent.com/105259459/176678411-1a8817a6-0cb4-4c4b-b4e4-f9ce25c196fa.png)
***
CAPITULO 8
***
**Conversiones de fuente**

2. Convierta las fuentes de voltaje prácticas de la figura 8-67 en fuentes de corriente equivalentes.

![image](https://user-images.githubusercontent.com/105259459/176678756-9772cd6a-7137-40c3-a710-cc618356ff5d.png)

![image](https://user-images.githubusercontent.com/105259459/176678829-5791c064-0b45-4001-8dd7-b29066b3c16b.png)

4. Trace los circuitos equivalentes de fuentes de voltaje y corriente para la batería tipo D del problema 3

![image](https://user-images.githubusercontent.com/105259459/176678950-48a17194-666a-4de8-98fd-3e358a6802e6.png)

6. Convierta las fuentes de corriente prácticas de la figura 8-68 en fuentes de voltaje equivalentes.

![image](https://user-images.githubusercontent.com/105259459/176679077-753e5c72-a073-43b5-b70b-7efe05ac69eb.png)

![image](https://user-images.githubusercontent.com/105259459/176679136-a1574473-af5c-4f93-8272-27ae64c89bdd.png)

8. Use el teorema de superposición para determinar la corriente a través, y el voltaje entre, los extremos de la rama R2 de la figura 8-69.

![image](https://user-images.githubusercontent.com/105259459/176679787-0309a05b-6257-4eea-a11c-4eef4ae44d70.png)

a)

Re = (2.2)(1.0)/(2.2+1.0) = 0.7 + 1.0 = 1.7

Re = (1.7)(2.2)/(1.7+2.2) = 1.0 + 1.0 = 2.0

I = V/R = 2/2 = 1 A

b)

Re = (2.2)(1.0)/(2.2+1.0) = 0.7 + 1.0 = 1.7

Re = (1.7)(2.2)/(1.7+2.2) = 1.0 + 1.0 = 2.0

I = V/R = 2/2 = 2.2 A

10. Con el teorema de superposición, determine la corriente de carga en cada uno de los circuitos mostrados en la figura 8-71

![image](https://user-images.githubusercontent.com/105259459/176680282-50194db7-f1b3-4a4c-8c49-171cb4d4cdc2.png)

12. Repita el problema 11 si R2 es de 10 kΩ

Se coloca un cortocircuito entre A y B, teniendo como Rt:

Req1 = 2.2 kΩ + 1 kΩ = 3.1 kΩ

Rt = (3.2 kΩ * 2.2 kΩ / 3.2 kΩ + 2.2 kΩ) = 1.3 kΩ

It = 0.1 A

Ix = (1.3 kΩ / 3.1 kΩ) * 0.1 A = 0.0419 A 

IN= 0.1 A – 0.0419 A = 0.0581 A = 58.1 mA

Se reemplaza la fuente de voltaje con un cortocircuito:

RN = (3.2 kΩ * 2.2 kΩ / 3.2 kΩ + 2.2 kΩ) = 1.3 kΩ

14. Los interruptores mostrados en la figura 8-74 se cierran en secuencia, SW1 primero. Determine la corriente a través de R4 después del cierre de cada interruptor.

![image](https://user-images.githubusercontent.com/105259459/176680629-b43f079e-4dad-450a-ad75-5ef09a32e026.png)

Se coloca un cortocircuito entre A y B, teniendo como Rt:

Rt = (100 kΩ * 56 kΩ / 100 kΩ + 56 kΩ) = 35.9 kΩ

It = (15 – 10) V / 35.9 kΩ = 0.1393 mA = 139.3 µA

IN = (56 kΩ / 56 kΩ + 100 kΩ) * 139.3 µA = 50 mA

Se reemplaza la fuente de voltaje con un cortocircuito:

RN = (100 kΩ * 56 kΩ / 100 kΩ + 56 kΩ) = 35.9 kΩ

16. Para cada uno de los circuitos de la figura 8-76, determine el equivalente de Thevenin como se ve desde las terminales A y B.

![image](https://user-images.githubusercontent.com/105259459/176680835-3703fe60-ca00-4cc9-8622-063777e6b66b.png)

Se coloca un cortocircuito entre A y B, teniendo como Rt:

Rt = (100 Ω * 270 Ω / 100 Ω + 270 Ω) = 72.97 Ω

It = 3 V / 72.97 Ω = 0.0416 A = 41.6 mA

IN = (100 Ω / 100 Ω + 270 Ω) * 41.6 mA = 11.24 mA

Se reemplaza la fuente de voltaje con un cortocircuito:

RN = (100 Ω * 270 Ω / 100 Ω + 270 Ω) = 72.97 Ω

18. Con el teorema de Thevenin, determine el voltaje entre los extremos de R4 en la figura 8-78

![image](https://user-images.githubusercontent.com/105259459/176681173-fc4f70d9-1842-4954-a98d-f2896013cc7a.png)

Se coloca un cortocircuito entre A y B, teniendo como Rt:

Rt = 100 Ω + 47 Ω + (27Ω * 75Ω / 27Ω + 75Ω) = 166.85 Ω

It = 25 V / 166.85 Ω = 0.1498 A = 149.8 mA

IN = (75 Ω / 75 Ω + 27 Ω) * 149.8 mA = 110.15 mA

Se reemplaza la fuente de voltaje con un cortocircuito:

RN = [(100 Ω + 47 Ω) * 75 Ω] / [(100 Ω + 47 Ω) + 75 Ω] + 27 Ω = 76.66 Ω

20. Determine la corriente que se dirige al punto A cuando R8 es de 1.0 k, 5 k Ω, y 10 k Ω en la figura 8-80.

![image](https://user-images.githubusercontent.com/105259459/176681508-8cabdd94-983f-48b2-aab9-286050d6070e.png)

VTh = (2.2 kΩ / 1 kΩ + 2.2 kΩ) * 12 V – (1.2 kΩ / 0.82 kΩ + 1.2 kΩ) * 12 V = 6.38 V

RTh = (1 kΩ * 2.2 kΩ / 1 kΩ + kΩ) + (0.82 kΩ * 1.2 kΩ/0.82 kΩ + 1.2 kΩ) = 1.17 kΩ

VL = (10 kΩ / 10 kΩ + 1.17 kΩ) * 6.38 V = 1 V

IL = 1 V / 10 kΩ = 0.1 mA = 100 µA

22. Determine el equivalente de Thevenin del circuito mostrado en la figura 8-82 visto desde las terminales A y B.

![image](https://user-images.githubusercontent.com/105259459/176681881-07773526-dda2-4c5b-a0b2-a0fe30df3038.png)

Las tres resistencias están en paralelo

1/RTh = 1/100 Ω + 1/1200 Ω + 1/2200 Ω = 0.01129 Ω

RTh = 88.57 Ω

24. Con el teorema de Norton, determine la corriente que circula a través del resistor de carga RL en la figura 8-77.

R2 y R3 están en serie por lo que: Req1 = 5.6 kΩ + 2.7 kΩ = 8.3 kΩ

Req1 está en paralelo con la carga de 33 kΩ, por lo que: Rt = (8.3 kΩ * 33 kΩ) / (8.3 kΩ + 33 kΩ) = 6.63 kΩ

Vx = (Rt / (R1 + Rt)) * Vs = (6.63 kΩ / (10 kΩ + 6.63 kΩ)) * 22 V = 8.77 V

26. Con el teorema de Norton, determine la corriente que circula a través de R1 en la figura 8-80 cuando R8  8Ω .

Sin carga

Rt = (56 kΩ * 56 kΩ) / (56 kΩ + 56 kΩ) = 28 kΩ

Vx = (Rt / Rx) * Vs = (28 kΩ / 56 kΩ) * 15 V = 7.5 V 

Con carga

Rt = (28 kΩ * 1000 kΩ) / (28 kΩ + 1000 kΩ) = 27.24 kΩ

Vx = (Rt / Rx) * Vs = (27.24 kΩ / 56 kΩ) * 15 V = 7.296 V

28. En la figura 8-83, reduzca el circuito entre las terminales A y B a su equivalente Norton.

![image](https://user-images.githubusercontent.com/105259459/176682331-bcad2aa0-e370-4ecd-906b-f901ab639bbc.png)

R1 y R2 están en serie: Req1 = 3.3 kΩ + 3.3 kΩ = 6.6 kΩ

R3 y R4 están en paralelo: Req2 = (3.3 kΩ * 3.3 kΩ) / (3.3 kΩ + 3.3 kΩ) = 1.65 kΩ

Req2 y R5 están en serie: Req3 = 1.65 kΩ + 3.3 kΩ = 4.95 kΩ

Resistencia de AB = Req1 = 6.6 kΩ

Resistencia de BC = Req2 = 1.65 kΩ

Resistencia de CD = 0 Ω

30. En cada circuito mostrado en la figura 8-85, se tiene que transferir potencia máxima a la carga RL. Determine el valor apropiado de RL en cada caso.

![image](https://user-images.githubusercontent.com/105259459/176682608-2e1cdf0c-377d-4e70-b79f-52f6e94bc947.png)

(a)

I = V/R = 80/12 = 6.7 A 

P = I^2(R) = (6.7)(6.7)(12) = 538.7 W

(b)

P = I^2(R) = (50)(50)(8.2) = 20500 W

(c)

Re = (2)(4.7)/(2+4.7) = 1.4 + 1.0 = 2.4

P = V(V)/R = 1/2.4 = 0.4 W

(d)

Re = (680)(47)/(680+47) = 43.96

P = I^2(R) = 5^2*43.96 = 1099

32. ¿Cuánta potencia se suministra a la carga cuando RL es un 10% más alta que su valor para transferencia de potencia máxima en el circuito de la figura 8-86?

![image](https://user-images.githubusercontent.com/105259459/176683015-ff092294-da06-474d-83c4-d22f99b57f84.png)

Re = 8.2 + 8.2 = 16.4

Re = (16.4)(8.2)/(16.4+8.2) = 5.5

Re = (5.5)(15)/(5.5+15) = 4.02

Re = (4.02)(4.7)/(4.02+4.7) = 2.2

P = I^2*V

P = 1(1.5) = 1.5 W   

34. En la figura 8-88, convierta cada red delta en una red Y.

![image](https://user-images.githubusercontent.com/105259459/176683276-60f25601-6f5f-42f4-98d7-4cf49bde1c61.png)

(a)

R1 = (Ra*Rc)/(Ra+Rb+Rc) = (560*1000)/(560+1500+1000) = 183 kΩ

R2 = (Rb*Rc)/(Ra+Rb+Rc) = (1500*1000)/(560+1500+1000) =490.2 kΩ

R3 = (Ra*Rb)/(Ra+Rb+Rc) = (560*1500)/(560+1500+1000) = 274.5 kΩ

(b)

R1 = (Ra*Rc)/(Ra+Rb+Rc) = (1.0*2.7)/(1.0+2.2+2.7) = 0.46 Ω

R2 = (Rb*Rc)/(Ra+Rb+Rc) = (1.0*2.2)/(1.0+2.2+2.7)  = 0.37 Ω

R3 = (Ra*Rb)/(Ra+Rb+Rc) = (2.7*2.2)/(1.0+2.2+2.7)  = 1.0 Ω

36. Determine todas las corrientes que circulan en el circuito de la figura 8-90.

![image](https://user-images.githubusercontent.com/105259459/176683818-83b41cc7-179b-4104-a9fc-9097907a5e7b.png)

Hallando la intensidad en R1: I1 = VS / R1 = 220 V / 47 kΩ = 2.33 mA

Con la ley las corrientes de Kirchhoff en donde: It = I1 + I2 = 2.33 mA + 1mA = 3.33 mA

Hallando el VR3= 3.33 mA * 33 = 109.89 V

El voltaje de R1 es: VS – Vr3 = 220 V – 109.89 V = 110.11 V

Como R1 y R2 están en paralelo su caída de voltaje es igual: 110.11 V

Aplicando la ley de Ohm: R2 = 110.11 V / 1 mA = 110.11 kΩ 

P = V * I = 110.11 V * 1 mA = 110.11 mW
***
**VIDEO**
***
https://www.youtube.com/watch?v=5S0WgDUcQ7Q
***
**CONCLUSIONES**
***
- A partir de los resúmenes realizados mediante mapas conceptuales, se puede decir que se combinan los resistores en serie y en paralelo dentro de circuitos en serie-paralelo. Tenemos combinaciones tanto en serie como en paralelo dentro del mismo circuito y se aplica los métodos de análisis de circuitos en serie y circuitos en paralelo, el divisor de voltaje sometidos a carga es importante, ya que este tipo de circuito se encuentra en muchas situaciones prácticas. Se utiliza los teoremas y las conversiones para facilitar el análisis de ciertos tipos de circuitos, junto con a la ley de Ohm y las leyes de Kirchhoff. Los teoremas de Thevenin y de Norton ponen a nuestro alcance métodos fáciles s para reducir un circuito a una forma equivalente simple.

- En la resolución de los ejercicios pares del libro “Principios de circuitos eléctricos” de Floyd, se aplicó lo comprendido de los capítulos 7 y 8, donde comprobamos lo importante que es los métodos de análisis de la combinación de los resistores en serie y en paralelo dentro de circuitos en serie-paralelo; y los teoremas de Thevenin y de Norton que vuelven mas fácil su resolución .

- En el video se justifica 4 ejercicios que se realizaron en el desarrollo del informe, mediante una breve explicación de lo que trata el ejercicio y aplicando las formula dadas


***
**BIBLIOGRAFIA**
***
Floyd, T. (2007). Principios de circuitos electricos. PEARSON Educación. https://drive.google.com/file/d/15UCq2JrPEKKB8SwajlmtTcE07nMiowaK/view
***
**RUBRICA**
***
![image](https://user-images.githubusercontent.com/105259459/176684710-0b07887f-3c00-4d4b-9c48-e75c125161e2.png)
***
