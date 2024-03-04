# Laboratorio 1
Juan Sebastian Daleman

Juan David Chica Garcia

## 1. ¿Que es un robot móvil?.Definir qué es un robot y cuáles son sus principales características.  
Según la norma ISO 8373:2021 se difine a un robot como:  
**3.1 Robot**  
Mecanismo actuado programable con un grado de autonomia para realizar locomoción, manipulación o posicion.  
*Nota 1*: Un robot incluye el sistema de control.  
*Nota 2*: Ejemplos de estructuras mecanicas de robots son manipuladores, plataformas moviles y robots vestibles.  
**4.15 Robot móvil**  
Es un robot el cual es capaz de viajar bajo su propio control.  
*Nota 1*: Un robot móvil puede ser una plataforma móvil con o sin manipuladores.  
*Nota 2*: Adicionalmete a una operación autonoma, un robot móvil puede tener medios para ser controlado remotamente.  

**Partes de un robot**  
* Mecanismo: Parte mecanica que permite el movimiento del robot.  
* Controlador o sistema de control: Conjunto componentes de hardware y software implementado un control logico y de energia, y otras funciones las cuales permiten motoreo y control del comportamiento de un robot y sus intereacciones y comunicación con otros objetos y humanos en el entorno.  
* Interface humano maquina (HMI): Interfaz que permite la interaccion entre la persona y el sistema de control del robot.  
* Comunicaciones: Sistemas que permiten la adquición y envio de señales para la interacción de las partes del robot.  

## 2. Presentación del mindstorms EV3, incluyendo sus características físicas y capacidades.
El robot mindstorms EV3 es un robot hecho por la empresa lego el caul es compatible con las piezas de lego technic para la contrucción de armaduras mecanicas o mecanimos, el bloque EV3 que es el centro de control y central electrica, diversidad de sensores (Para ver más detalladamente ver el punto 6), motores de tamaño grande le permite programar acciones robóticas precisas y potentes y motores de tamaño mediano mantiene la precisión, mientras cambia algo de potencia por un tamaño compacto y una respuesta más rápida, sistema de comunicaciones por cable mini USB para conecciones con un PC, comunicación bluethoot y wifi, puertos USB para ser usado con otros bloques EV3 y microSD para expandir la memoria del bloque de control. Es un sistema muy versatil que permita atravez de la creatividad del uso de los bloques de lego la creación de diferentes sistemas roboticos con las limitantes mecanicas que estos bloques poseen. Asimismo el bloque solo puede manejar de forma simultanea cuatro motores y cuatro sensores.


## 3. Estado actual del robot y sistema de control.
El robot actualmente se encuantra en buen estado sin maltratos significativos en sus piezas, adicionalmente se encuntra con su conjunto de piezas completo [es-ev3re-elementsurvey.pdf](https://github.com/JSDaleman/Robotica-movil-Lab1/files/14476164/es-ev3re-elementsurvey.pdf) adicional mente posee un senor infrarrojo adicional al conjunto de piezas original cuyo lego ID es 6009811. su controlador se encuantra en buen estado con conectivada a PC, bluethoot y wifi funcionale.

## 4. APIs y lenguajes de programación para robots EV3 de LEGO
**4.1 APIs disponibles:**

* API EV3: Es la API oficial de LEGO para programar robots EV3. Proporciona acceso a todas las funcionalidades del robot, como el control de motores, sensores, sonidos y pantalla.
* API LabVIEW: Permite programar robots EV3 utilizando el lenguaje de programación gráfico LabVIEW.
* API RobotC: Proporciona una interfaz de programación similar a C para controlar robots EV3.
* API NXT-G: Permite programar robots EV3 utilizando el lenguaje de programación NXT-G, diseñado para principiantes.

**4.2 Lenguajes de programación compatibles:**

* Python: Se puede usar Python para programar robots EV3 mediante la API EV3-Python.
* Java: La API EV3-Java permite programar robots EV3 utilizando el lenguaje de programación Java.
* C/C++: Es posible programar robots EV3 en C/C++ utilizando la API EV3-C.
* MATLAB: Se puede usar MATLAB para programar robots EV3 mediante la API EV3-MATLAB.

## 5. Herramientas de desarrollo propias

Para programar un EV3, actualmente los mas populares son:

**LEGO® MINDSTORMS® EV3 Home Edition (LabVIEW)**

*Enfoque:* Basado en bloques de funciones que representan operaciones y comandos específicos.

*Estructura:* Los bloques se conectan mediante cables para representar el flujo de datos y la lógica del programa.

*Funcionamiento:*

* Bloques: Cada bloque tiene una función específica, como leer un sensor, controlar un motor o realizar cálculos matemáticos.
* Cables: Los cables transportan datos entre los bloques, determinando el orden en que se ejecutan las acciones.
* Flujo de datos: El programa se ejecuta siguiendo el flujo de datos desde la entrada hasta la salida.
* Programación gráfica: La interfaz visual facilita la comprensión del programa y la identificación de errores.

*Utilidad:*

* Control preciso: Permite un control preciso del robot y de sus componentes.
* Programas complejos: Permite crear programas complejos y personalizados para una amplia gama de aplicaciones.
* Flexibilidad: Ofrece mayor flexibilidad para adaptar el programa a las necesidades específicas del proyecto.

*Funciones:*

* Amplia biblioteca de bloques: Contiene una amplia biblioteca de bloques predefinidos para controlar sensores, motores, la pantalla y otros elementos del robot.
* Acceso a hardware: Permite acceder y configurar el hardware del robot a un nivel más profundo.
* Creación de funciones: Permite crear funciones y bloques personalizados para ampliar las capacidades del robot.
* Depuración avanzada: Ofrece herramientas de depuración avanzadas para identificar y corregir errores en el programa.

**EV3 Classroom App v. 1.5.3:**

*Enfoque:* Basado en Scratch, un software, un entorno y un lenguaje de programación visual. A través de su interfaz en línea o sin conexión, permite a los usuarios crear un algoritmo ensamblando bloques para crear una simulación o una historia interactiva.

*Estructura:* Los bloques se ensamblan como piezas de un rompecabezas para crear secuencias de comandos.

*Funcionamiento:*

* Bloques: Cada bloque representa una acción simple, como mover el robot, reproducir un sonido o mostrar un mensaje en la pantalla.
* Arrastrar y soltar: Los bloques se arrastran y sueltan en el área de trabajo para crear la secuencia de comandos.
* Programación visual: La interfaz gráfica facilita la comprensión del programa y la identificación de errores.
* Interfaz intuitiva: Diseñada para principiantes sin experiencia previa en programación.

*Utilidad:*

* Fácil de usar: Interfaz intuitiva y fácil de usar para principiantes sin experiencia en programación.
* Aprendizaje guiado: Ofrece una experiencia de aprendizaje guiada con tutoriales y proyectos predefinidos.
* Programación básica: Permite crear programas básicos para explorar conceptos de robótica y programación.


*Funciones:*

* Bloques visuales: Interfaz con bloques visuales que representan acciones y conceptos básicos de programación.
* Programación por bloques: Arrastrar y soltar bloques para crear la secuencia de comandos del programa.
* Proyectos predefinidos: Amplia biblioteca de proyectos predefinidos para explorar diferentes aplicaciones de robótica.
* Interfaz de usuario: Permite crear interfaces gráficas simples para interactuar con el robot.


## 6. Sensores del robot: Identificar los sensores incorporados en los robots y explicar su funcionamiento. Que compatibildiad tienes con otros sensores.
### Sensor de color: 
Funciona utilizando una combinación de fotorreceptores que son sensibles a diferentes longitudes de onda de la luz. Cuando la luz entra en el sensor a través de su ventana, los fotorreceptores detectan la intensidad de la luz en diferentes rangos de longitud de onda, lo que permite al sensor determinar el color del objeto que está siendo observado. Además, en el modo de intensidad de la luz reflejada, el sensor mide la cantidad de luz reflejada desde una fuente, mientras que en el modo de intensidad de la luz ambiental, mide la cantidad de luz que ingresa desde el entorno. Esto se logra mediante el uso de circuitos electrónicos que convierten la luz en señales eléctricas que pueden ser interpretadas por el microcontrolador del robot.

![image](https://github.com/JSDaleman/Robotica-movil-Lab1/assets/125931563/a199e149-e00b-45ef-b9d3-3594278f1765)

![image](https://github.com/JSDaleman/Robotica-movil-Lab1/assets/125931563/668fbd51-50c4-4096-9f08-1c827b5887f4)


### Girosensor: 
Este sensor utiliza un componente llamado giroscopio para detectar el movimiento de rotación en un eje. Un giroscopio consiste en un rotor que gira libremente dentro de un marco, y cuando el marco gira, el rotor tiende a mantener su orientación original en el espacio. La velocidad a la que el rotor tiende a mantener su orientación se traduce en una señal eléctrica proporcional a la velocidad de rotación, que puede ser interpretada por el microcontrolador del robot. Además, el ángulo de rotación total se calcula integrando la velocidad de rotación en el tiempo.




### Sensor táctil: 
Este sensor funciona mediante la detección de cambios en la resistencia eléctrica cuando se presiona el botón rojo del sensor. Cuando se presiona el botón, se produce un contacto eléctrico que permite que la corriente fluya a través del sensor, lo que se traduce en una señal eléctrica que indica que el botón ha sido presionado. Cuando se suelta el botón, el contacto eléctrico se interrumpe y la corriente deja de fluir, lo que también se detecta como una señal eléctrica por el microcontrolador del robot.



### Sensor ultrasónico: 
Este sensor emite pulsos de sonido de alta frecuencia y luego mide el tiempo que tarda cada pulso en reflejarse de vuelta desde un objeto cercano. Utiliza la velocidad del sonido en el aire para calcular la distancia al objeto según la fórmula distancia = velocidad x tiempo. Esta información se convierte en una señal eléctrica que indica la distancia al objeto, que puede ser interpretada por el microcontrolador del robot.

![image](https://github.com/JSDaleman/Robotica-movil-Lab1/assets/125931563/b4171fec-c9dc-4e2f-8557-c3e93ca237d8)

### Sensor infrarrojo y Baliza infrarroja remota: 
Estos sensores funcionan detectando la luz infrarroja reflejada por objetos sólidos o las señales de luz infrarroja enviadas por la baliza remota. Utilizan fotorreceptores sensibles a la luz infrarroja para convertir la luz en señales eléctricas que pueden ser interpretadas por el microcontrolador del robot. Dependiendo del modo de operación (proximidad, baliza o remoto), el sensor interpreta estas señales para determinar la distancia al objeto, la dirección de la baliza y otros parámetros relevantes.

![image](https://github.com/JSDaleman/Robotica-movil-Lab1/assets/125931563/7a53cc18-befe-4ee1-8e02-f04fa5950357)

### Compatibilidad con otros sensores:

El EV3 es compatible con los sensores y motores de la versión NXT, ya que utilizan los mismos cables conectores (RJ12) y el software EV3 los reconoce. Sin embargo, los sensores del EV3 no funcionan en el ladrillo NXT, solo los motores. En foros se habla del uso de sensores cumunmente usados con diferentes tarjetas de desarrollo como arduino, pero se requiere de un enlace I2C entre la tarjeta de desarrollo y el EV3.

## 7.  Práctica de identificación y uso de los sensores integrados en los robots, explicando cómo interactúan con el entorno.

### Sensor de color: 
Este sensor puede detectar el color o la intensidad de la luz que ingresa por su ventana. Tiene tres modos de funcionamiento: Modo color, Modo intensidad de la luz reflejada y Modo intensidad de la luz ambiental. En Modo color, reconoce siete colores diferentes y puede ser utilizado para clasificar objetos por color. En Modo intensidad de la luz reflejada, mide la intensidad de la luz reflejada desde una fuente, lo que permite detectar líneas o códigos de color. En Modo intensidad de la luz ambiental, mide la luz que ingresa desde el entorno. La tasa de muestreo del sensor es de 1 kHz.

![image](https://github.com/JSDaleman/Robotica-movil-Lab1/assets/125931563/53aaf8ce-a5f8-446c-92c1-a03229c53ac6)

![image](https://github.com/JSDaleman/Robotica-movil-Lab1/assets/125931563/ba5d5cae-ccc1-4e55-ab4f-f30cd078e4e1)

![image](https://github.com/JSDaleman/Robotica-movil-Lab1/assets/125931563/aa4b997b-556b-475c-8e57-f739506115f0)

![image](https://github.com/JSDaleman/Robotica-movil-Lab1/assets/125931563/b526172e-ef57-469a-9d71-71839c15cb83)


### Girosensor: 
Detecta el movimiento de rotación en un eje simple y puede medir la razón de rotación en grados por segundo, así como el ángulo de rotación total en grados. Es útil para detectar el movimiento de partes del robot o si el robot se ha caído.

![image](https://github.com/JSDaleman/Robotica-movil-Lab1/assets/125931563/c8bd9834-1bf3-4b86-8f11-918e0435142c)

![image](https://github.com/JSDaleman/Robotica-movil-Lab1/assets/125931563/6036c926-a010-414d-9345-5c2396cfff70)

### Sensor táctil: 
Puede detectar cuando se presiona o se lanza el botón rojo del sensor. Puede ser programado para actuar según tres condiciones: presionado, lanzado o en contacto.

![image](https://github.com/JSDaleman/Robotica-movil-Lab1/assets/125931563/20f25503-82f5-4d34-aed5-60b1a9abab76)

![image](https://github.com/JSDaleman/Robotica-movil-Lab1/assets/125931563/f98a56e2-1bbf-47a1-b8ba-ecbd62c46be2)

![image](https://github.com/JSDaleman/Robotica-movil-Lab1/assets/125931563/a1f68e9f-6eb1-494d-b7a0-e127c161f76e)

### Sensor ultrasónico: 
Mide la distancia a un objeto que se encuentra frente a él mediante el envío y la recepción de ondas de sonido de alta frecuencia. Puede ser utilizado para detectar objetos y medir distancias.

![image](https://github.com/JSDaleman/Robotica-movil-Lab1/assets/125931563/62fc483a-122d-42eb-8ffa-88db28e37def)

![image](https://github.com/JSDaleman/Robotica-movil-Lab1/assets/125931563/99d50214-cecf-4a2a-b67a-d370b54ed58b)


### Sensor infrarrojo y Baliza infrarroja remota: 
Detecta luz infrarroja reflejada por objetos y puede también detectar señales de luz infrarroja enviadas por la Baliza infrarroja remota. Tiene tres modos de funcionamiento: Modo de proximidad, Modo de baliza y Modo remoto.

![image](https://github.com/JSDaleman/Robotica-movil-Lab1/assets/125931563/ce09fd32-bb8e-41f6-a09a-ab5711d6bf34)

![image](https://github.com/JSDaleman/Robotica-movil-Lab1/assets/125931563/f2f968af-4c06-406b-be54-22706728012a)

![image](https://github.com/JSDaleman/Robotica-movil-Lab1/assets/125931563/1d38e38b-8aeb-4f66-8172-048d1795f158)


## 8. Simulación en CoppeliaSim del robot EV3
Utilizado el software CoppeliaSim, se crean la simulación del robot EV3, primero se determine las medidas del robot para hacer lo más realista la simulación.

![Medidas](https://github.com/JSDaleman/Robotica-movil-Lab1/assets/68557324/d26a90b7-827b-404d-a93e-35b39a9394ea)

Se crean la estructura general del robot utilizando un cubo, dos cilindros conectados con unión de revolución y una esfera conectada a un sensor de fuerza, como se muestra en la siguiente imagen:

![Estructura](https://github.com/JSDaleman/Robotica-movil-Lab1/assets/68557324/f6b937bd-442c-4cb4-9177-64cc825a8a77)

A continuacion se ve el resultado de la simulación:

![Simulacion](https://github.com/JSDaleman/Robotica-movil-Lab1/assets/68557324/7ed58f70-b1bd-4fe7-83f3-a5a6882d12fe)

Funcionamiento de la simulación:

https://github.com/JSDaleman/Robotica-movil-Lab1/assets/68557324/989df357-6d5c-4fc5-9b71-7a0bb20031db

## 9. Programa de simple movimiento

Utilizando  LEGO® MINDSTORMS® EV3, se crea un programa donde al iniciar el robot mostrara en su pantalla ojos enojados, después avanzara hacia el frente hasta que el sensor de contacto sea presionado por algún obstáculo, cuando esto se cumpla el robot emitirá un beep por 1 segundo, después avanzará hacia atrás durante 1 segundo y girará su rueda B en el sentido de las manecillas del reloj por 0.5 segundos, y continuará hacia adelante hasta que se vuelva cumplir la condición.

La estructura del programa se muestra en la siguiente imagen utilizando el lenguaje de programación Scratch:

![prom1](https://github.com/JSDaleman/Robotica-movil-Lab1/assets/68557324/fb79ea86-da05-47c1-9cb5-7270cd996c53)  
https://github.com/JSDaleman/Robotica-movil-Lab1/blob/main/Codigos/PrimerrMovimiento.lmsp

Se muestra el funcionamiento del programa cargado en el robot:


https://github.com/JSDaleman/Robotica-movil-Lab1/assets/68557324/7ac74b6c-7c99-497d-bf72-70879847625e


Se crea un segundo programa, esta vez en Python y diagramas de bloques, donde el robot realizara un segimiento a las paredes a su lado derecho en su recorrido, se muestra la estructura del programa en la siguiente imagen:

![prom2](https://github.com/JSDaleman/Robotica-movil-Lab1/assets/68557324/10ed6e31-daeb-4ece-ac56-7d3281a2e42d)  
https://github.com/JSDaleman/Robotica-movil-Lab1/blob/main/Codigos/Prueba.ev3


y el video del funcionamiento del programa cargado en el robot:


https://github.com/JSDaleman/Robotica-movil-Lab1/assets/68557324/6359e798-f963-488b-8a3a-c7fdaef0f26e



## 10. Reflexión y discusión

La utilización del robot EV3 es fácil e intuitiva utilizando las herramientas propias y el lenguaje de programación Scratch, para la programación en diagrama de bloques y Python, ya se necesita tener cierto conociendo sobre todo en Python, la conexión de los sensores al robot es fácil  y permite modifica su diseño estructural para adaptarse a las necesidades en su funcionamiento.

Las posibles mejoras que se plantean es la de utilizar otras plataformas o lenguajes para la programación del robot, permitiendo así que sea más atractivo y utilizado por diferentes personas independiente de su nivel de conocimiento en el área, también permitiendo expandir usos a áreas más técnicas o de mayor complejidad.

