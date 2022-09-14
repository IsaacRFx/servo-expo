# SPBB22-Exposiciones de los sensores del Simulador

## Servo

Para poder utilizar motores tipo servo, vamos a utilizar pulseio. En teoría uno puede realizar llamadas directas a pulseio para definir una frecuencia de 50 Hz y con eso definir el ancho de los pulsos. ¡Pero preferimos hacerlo un poco más elegante y sencillo!

Así que en cambio, ¡vamos a utilizar adafruit_motor la cual te maneja los motores tipo servo de buena manera! adafruit_motor es una librería, ¡así que asegúrate de obtenerla del compilado de liberías si no lo has hecho! Si necesitas ayuda con la instalación puedes revisar la página de Librerías de CircuitPython.

Los servos vienen en dos tipos: 

Un servo estándar para hobbies - el puntero se mueve 180 grados (90 grados en cada dirección desde cero grados).
Un servo de rotación continua - el puntero se mueve una rotación completa como un motor DC. En lugar de indicarse un ángulo, se define una velocidad de movimiento donde 1.0 es toda velocidad hacia adelante, 0.5 la mitad de la velocidad hacia adelante, 0 detenido, -1 es toda velovidad en reversa con sus valores intermedios.

### Servo demo - Circuitpython

![Servo demo](https://wokwi.com/projects/342100078704460371)