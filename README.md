# Laboratorio 1
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

### Sensor táctil: 
Puede detectar cuando se presiona o se lanza el botón rojo del sensor. Puede ser programado para actuar según tres condiciones: presionado, lanzado o en contacto.

### Sensor ultrasónico: 
Mide la distancia a un objeto que se encuentra frente a él mediante el envío y la recepción de ondas de sonido de alta frecuencia. Puede ser utilizado para detectar objetos y medir distancias.

### Sensor infrarrojo y Baliza infrarroja remota: 
Detecta luz infrarroja reflejada por objetos y puede también detectar señales de luz infrarroja enviadas por la Baliza infrarroja remota. Tiene tres modos de funcionamiento: Modo de proximidad, Modo de baliza y Modo remoto.

## 8. Simulación en CoppeliaSim del robot EV3
Utilizado el software CoppeliaSim, se crean la simulación del robot EV3, primero se determine las medidas del robot para hacer lo más realista la simulación.

![Medidas](https://github.com/JSDaleman/Robotica-movil-Lab1/assets/68557324/d26a90b7-827b-404d-a93e-35b39a9394ea)

Se crean la estructura general del robot utilizando un cubo, dos cilindros conectados con unión de revolución y una esfera conectada a un sensor de fuerza, como se muestra en la siguiente imagen:

![Estructura](https://github.com/JSDaleman/Robotica-movil-Lab1/assets/68557324/f6b937bd-442c-4cb4-9177-64cc825a8a77)

A continuacion se ve el resultado de la simulación:

![Simulacion](https://github.com/JSDaleman/Robotica-movil-Lab1/assets/68557324/7ed58f70-b1bd-4fe7-83f3-a5a6882d12fe)

Funcionamiento de la simulación:

https://github.com/JSDaleman/Robotica-movil-Lab1/assets/68557324/989df357-6d5c-4fc5-9b71-7a0bb20031db



