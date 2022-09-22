# SPBB22-Exposiciones de los sensores del Simulador

![SERVO](https://images.cooltext.com/5620229.gif)

Un servomotor es un actuador rotativo o motor que permite un control preciso en términos de posición angular, aceleración y velocidad, capacidades que un motor normal no tiene. En definitiva, utiliza un motor normal y lo combina con un sensor para la retroalimentación de posición.

Pero, los servomotores no son en realidad una clase específica de motor, sino una combinación de piezas específicas, que incluyen un motor de corriente continua o alterna, y son adecuados para su uso en un sistema de control de bucle cerrado.


![image](https://user-images.githubusercontent.com/81411699/191141213-82cdf2d3-ec8d-4db7-9df8-05af9feb9d0e.png)

Por lo que una definición más exacta de un servomotor sería la de un servomecanismo de bucle cerrado que utiliza la retroalimentación de posición para controlar su velocidad de rotación y posición. La señal de control es la entrada, ya sea analógica o digital, que representa el comando de posición final para el eje.

Por otro lado, el codificador o encoder sirve como sensor, proporcionando retroalimentación de velocidad y posición. En la mayoría de los casos, sólo se informa de la posición. La posición final se informa al controlador y se compara con la entrada de posición inicial, y luego, si hay una discrepancia, se mueve el motor para llegar a la posición correcta.

Hay varios tipos de servos como los que utilizan motores de corriente continua y detección de posiciones a través de un potenciómetro y también utilizan un control de gran potencia, lo que significa que el motor se mueve a la velocidad máxima hasta que se detiene en la posición designada.

![image](https://user-images.githubusercontent.com/81411699/191632436-83dfd2cc-b08c-48b1-8ead-593afcd891dc.png)

En cambio, los servos para uso industrial disponen de sensores de posición y velocidad, así como de algoritmos de control proporcional-integral-derivativo, lo que permite llevar el motor a su posición de forma rápida.

Este tipo de dispositivos están disponibles en una gran variedad de tipos, formas y tamaños. El término servo fue utilizado por primera vez en 1859 por Joseph Facort, que implementó un mecanismo de retroalimentación para ayudar a controlar los timones de un barco con vapor.

![image](https://user-images.githubusercontent.com/81411699/191139491-6b0461f6-eb22-40f2-9cd8-c30fb9d0c56e.png)

### [Servo live demo](https://wokwi.com/projects/342100078704460371)

![2022-09-14 03-58-39_1](https://user-images.githubusercontent.com/81411699/190139171-79c74d3e-7624-48f3-998d-9a04b40374a9.gif)
