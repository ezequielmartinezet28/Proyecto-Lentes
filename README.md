Lentes con Alerta de Obstáculos mediante Sensor Ultrasónico

#Descripción del Proyecto

Este proyecto consiste en un par de lentes inteligentes diseñados para alertar a las personas sobre objetos que se encuentran frente a ellas. Utilizando un sensor ultrasónico, el dispositivo detecta la proximidad de obstáculos y envía esta información a un Arduino Nano, el cual activa un buzzer para emitir un sonido de advertencia.

El objetivo principal de este proyecto es mejorar la seguridad y facilitar la navegación, especialmente para personas con dificultades visuales o en entornos donde se requiere atención adicional a los obstáculos.

#Funcionamiento

El sensor ultrasónico emite ondas sonoras de alta frecuencia que rebotan en los objetos cercanos.

El sensor mide el tiempo que tarda la onda en regresar, calculando así la distancia al objeto.

Cuando la distancia detectada es menor a 100 cm (1 metro), el Arduino activa el buzzer.

La frecuencia de los pitidos del buzzer aumenta a medida que el objeto se acerca, proporcionando una alerta más intensa y urgente cuanto más cerca se encuentre el obstáculo.

De esta forma, el usuario puede percibir intuitivamente la proximidad de los objetos y reaccionar a tiempo.

#Características

Compatible con Arduino Nano.

Detección de objetos hasta 1 metro de distancia.

Intensidad de alerta proporcional a la cercanía del obstáculo.

Sistema compacto y portátil, integrable en gafas o lentes.

#Componentes Utilizados

Arduino Nano

Sensor ultrasónico HC-SR04 (o equivalente)

Buzzer piezoeléctrico

Cables de conexión y protoboard o circuito impreso

Instalación y Uso

Conecta el sensor ultrasónico al Arduino según el esquema de conexión.

Conecta el buzzer al pin designado en el Arduino.

Carga el código en el Arduino Nano utilizando el IDE de Arduino.

Coloca los lentes o el sistema cerca de la cara del usuario y enciende el dispositivo.

Los pitidos indicarán la cercanía de los objetos frente al usuario.

#Posibles Mejoras

Ajustar la distancia máxima de detección según necesidades específicas.

Incorporar diferentes tonos o patrones de alerta para distintos rangos de distancia.

Integrar vibración o señales hápticas además del sonido para mayor accesibilidad.

Añadir conectividad Bluetooth para monitoreo en tiempo real desde un dispositivo móvil.
