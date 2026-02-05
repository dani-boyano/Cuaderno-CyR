
# Cuaderno-CyR de Daniel Boyano Lomas
¡Bienvenidos! Esta es mi página web creada con GitHub, en la cual relataré los trabajos de la asignatura de Computación y Robótica.
## **Proyecto 1 Microbit Maestro y Esclavo**
### Presentación del proyecto y finalidad:
En este proyecto, debemos conseguir controlar eficazmente a un robot maquuen con una placa microbit, para sortear una serie de obstáculos en un circuito en constante cambio, la finalidad es parar el robot al final de dicho circuito sin rozar o mover ninguna pieza. Este proyecto puede ser desglosado en dos partes, maestro y esclavo:
### <ins>**Maestro:**</ins>
El objetivo del maestro en este proyecto, consiste en controlar eficazmente al esclavo, en este caso, a un robot maquuen, usando una placa microbit previamente codificada con señales de radio.
En mi caso, al esclavo del grupo 5, por lo que este programa está diseñado par solofuncionar con dicho esclavo.


**Programa:**
![IMG-20260204-WA0028 (2)](https://github.com/user-attachments/assets/12abf5d2-3dc5-4691-b733-f971ade7d6cf)
En este programa podemos observar diferentes señales de radio, en forma de números, enviadas al pulsar distintas partes de la placa, como los botones, el logotipo o simplemente agitándo la microbit. Esto no sería posible sino tuviéramos una frecuencia de radio común, como es en nuestro caso la frecuencia número 167, común a la frecuencia del esclavo del grupo 5. Por otra parte, al enviar ciertos valores, la microbit maestro encenderá una serie de leds, formando figuras, que corresponden al sentido en el cuál el maquuen se dirigirá.


**Diagrama de flujo:**

<img width="660" height="681" alt="Diagrama en blanco (1) (1)" src="https://github.com/user-attachments/assets/893f05d7-b789-451a-9273-5bdda06b6c08" />

Este diagrama nos viene a decir que cuando la frecuencia de radio es común, al realizar una acción con dicha placa, enviará diferntes valores, en función de dicha concreta acción.



### <ins>**Esclavo:**</ins>
El objetivo del esclavo en este proyecto es traducir adecuadamente las señales numéricas enviadas por el maestro en acciones visibles, en este caso, el movimiento, sonido o figuras led del robot maquuen.


**Programa(Grupo4):**
![IMG-20260204-WA0009 (1)](https://github.com/user-attachments/assets/bd8bf610-2840-42c8-af5c-bca448dbbdfa)
En este programa observamos el funcionamiento del esclavo controlado por el grupo 3, siendo nuestro esclavo el controlado por dicho maestro. En este caso se establece en la frecuencia de radio 5, apartir de ahí, al recibir determinados números, el robot maquuen realiza ciertas acciónes, todo esto sujeto bajo diferentes condicionales que igulan los valores de entrada a números como el 51, el 34, el 72, etc si estos valores son igualados, se ejecutará una acción a mano del robot, si por ejemplo llega el número 51, el robot maquuen encenderá su motor derecho mientras para el izquierdo, por lo que el maquuen girará hacia la izquierda, si recibe el 34, el robot girará en sentido contrario, al recibir el 72, retrocederá, 48 avanzará.




**Diagrama de flujo:**

<img width="640" height="681" alt="Diagrama en blanco (3) (1)" src="https://github.com/user-attachments/assets/5c174663-41c0-4b22-ab1b-0253cd9e816c" />

Lo que transmite dicho diagrma, es que al recibir un valor numérico, si maestro y esclavo comparten la misma frecuencia de radio, el maquuen ejecutará una acción u otra, depndiendo del valor numérico enviado por el maquuen.




### **Vídeo del resultado final:**
![u35xTeP2W2k_320x180 (2)](https://github.com/user-attachments/assets/0028d161-3798-48f4-976e-0b49a2992de0)https://www.youtube.com/watch?v=u35xTeP2W2k&authuser=0

Como podemos ver en el vídeo, el robot logra sortear los obstáculos y llegar al cuadrdo blanco dejando sonar una melodía.



### Materiales físicos requeridos:
1.2 Placas Microbit(Maestro y esclavo)


2.Robot maquuen


3.5 pilas(1.5V) y sus correspondientes portadores TENGO ESTE CÓDIGO DE GITHUB, MEJORALO PARA HACER LA PÁGINA WEB MAS EST´ÑETICA
