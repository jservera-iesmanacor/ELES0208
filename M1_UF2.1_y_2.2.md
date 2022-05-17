UF2 - Montajes en instalaciones domóticas en edificios.
=======================================================

**Para ilustrar con ejemplos esta unidad se seguirá paralelamente el manual de Zelio Home**

1.- Sistemas domóticos utilizados en edificios.
----------------------------------------------
La automatización o gestión técnica de edificios o viviendas, domótica, como se le suele llamar, es un área multidisciplinar que engloba conceptos de áreas como la electricidad, la electrónica, la informática y las comunicaciones.

Las áreas de gestión en las instalaciones domóticas es una forma modular de abordar los servicios que nos ofrece la automatización y la gestión de viviendas y edificios.

La última instrucción (ITC BT 51) del Reglamento electrotécnico de baja tensión habla de cuáles deben ser los requisitos que deben cumplir las instalaciones de los sistemas de automatización, gestión de la energía y la seguridad en viviendas y edificios, también llamados sistemas domóticos .

Los puntos más relevantes de la instrucción ITC BT 51 son:

* Objeto y campo de aplicación
* Tipo de sistemas
* Requisitos generales de la instalación
* Condiciones particulares de la instalación

### Sistemas domóticos utilizados en función de:

#### Seguridad.
Es diferente según el tipo de construcción donde se aplica. En la vivienda se utiliza el sistema de alarma con detectores de movimiento con la posibilidad, por ejemplo, de enviar mensajes al usuario advirtiéndole del suceso o accionar automáticamente todas las luces de la casa si la alarma salta por la noche.

En el caso del edificio, aparte de los detectores, también entran en funcionamiento cámaras de vigilancia, detectores de huellas dactilares para poder acceder a las distintas dependencias del edificio según el privilegio programado dentro de la instalación domótica, simulación de presencia, detectores de incendio, inundación, o gas.

Se clasifican los servicios que ofrece la seguridad en:

* **Control de accesos:** El control de accesos es más propio en edificios en los que accede un gran número de personas. La forma de controlar estos accesos va desde control mediante videocámaras, teclado numérico, con tarjeta electrónica, con detector de huellas dactilares o con Bluetooth sea con un mando con señales, con el móvil, o cualquier aparato que lleve este sistema.

* **Control de intrusión:** Se trata de una instalación de alarma convencional con la diferencia de que por estar domotizada queda integrada con el resto de servicios del edificio o vivienda, lo que hace que, además de lo que hace habitualmente una alarma convencional , pueda generar cualquier acción como encender todas las luces de la casa y la luz exterior, prácticamente sin costes añadidos, según sea la programación de la instalación domótica.

* **Alarmas técnicas:** Las alarmas técnicas son las encargadas de supervisar el funcionamiento de las instalaciones de electricidad, gas, gasoil, agua e incendios. En definitiva, son detectores que están instalados para supervisar una posible anomalía y evitar accidentes. Así pues, clasificaríamos las alarmas técnicas en:

    * Detección de avería o suministro eléctrico.
    * Detección de escape de gas o de agua.
    * Detección de carencia de gasoil.
    * Detección de incendios.
    
* **Simulación de presencia:** El servicio de simulación de presencia emula la presencia humana, encendiendo y apagando luces aleatoriamente, subida y bajada de persianas y otros elementos disuasivos de robo.

* **Alarmas médicas:** Este tipo de servicio va dirigido sobre todo a la tercera edad ya las personas con discapacidad. Se trata de utilizar la instalación domótica como elemento de control para el bienestar de las personas que la habitan. Por ejemplo, una persona de la tercera edad que vive sola y que tiene una rutina diaria, en el caso de sufrir una caída y no poder valerse por sí misma, mediante un pulsador portátil puede dar la señal de aviso al centro de salud.


#### Confort.
Tiene como propósito la comodidad en la utilización de las instalaciones domóticas existentes en la vivienda o edificio. Un ejemplo de confortabilidad se encuentra en la rutina del día a día en una vivienda en la que por la mañana y antes de levantarse ya se suben las persianas, se pone en marcha la música ambiental y la calefacción pasa de modo noche a modo confort. Una vez levantados se preparan para marcharse, y al abandonar la vivienda, cierran la puerta y automáticamente, al no detectarse movimiento dentro de la vivienda, se apaga la música ambiental, se conecta la alarma y la calefacción pasa de modo confort a modo standby .

#### Economía.
cuyo objetivo es el ahorro de la energía y esto se consigue con el control y la automatización de las instalaciones de climatización y de la iluminación principalmente, en las que se optimizará su utilización en base a la presencia de personas y de criterios estándares de ahorro como por ejemplo que la temperatura de confort no sobrepase los 22ºC recomendados. Así como la detección de fugas de agua o válvulas que repasan. Finalmente se puede programar el funcionamiento de electrodomésticos o equipos para el calentamiento de agua (aerotérmia), en los momentos en los que la producción de energías renovables sea máxima. 

### Elementos del sistema domótico:


#### Controlador

Son los elementos centrales del sistema domótico. Ellos reciben la información que le proporcionan los sensores, la procesan y deciden que actuadores entran en funcionamiento y cómo.

Son los llamados relés programables, PLC, autómata o controlador simplemente.

#### Sensores
Los sensores son los aparatos domóticos a través de los cuales introducimos o introducen de forma automática una o varias órdenes dentro de la instalación domótica para ejecutar una o varias acciones para satisfacer las necesidades del usuario.

* Físicos manuales: 
    * pulsadores
    * conmutadores
* Físicos automáticos:
    * Temperatura
    * Luminosidad
    * Infrarrojo
    * Movimiento
    * Radiofrecuencia
    * Velocidad
* Químicos
    * Humedad
    * Humo
    * Gas
    * Agua
* Biológico
    * Huellas dactilares
    * Reconocimiento facial

#### Interface de entrada

La interfaz de entrada son aquellas conexiones que utiliza el controlador para recibir información del exterior. Pueden ser entradas todo-nada digitales, buses de comunicación. Entradas analógicas y entradas digitales de más de un bit.

#### Interface de salida

Son las conexiones que utiliza el controlador para enviar ordenes al exterior. ya sea una salida analógica, un relé, una salida digital, un puerto serie, o un bus de datos.
 
#### Actuadores

Los actuadores son aparatos domóticos que son comandados por los sensores o por aparatos de supervisión y control como una pantalla táctil. Éstos se encargan de accionar los dispositivos o cargas de las instalaciones de la vivienda o edificio tales como luces, persianas, enchufes, puertas, electroválvulas de calefacción…

Pueden estar directamente conectados al sistema domótico, en el caso de actuadores de baja potencia y siempre que el Controlador lo permita (como en el caso de los relés programables o PLC). O bién ser controlados mediante un contactor situado en el cuadro eléctrico y comandado por el controlador, en el caso de actuadores de mayor potencia.


#### Fuente de alimentación

No todos los controladores funcionan a 230V en alterna. Es común que tanto la alimentación como sus inputs requieran de una tensión menor y continua. La fuente de alimentación es la encargada de transformar la tensión alterna de una red eléctrica doméstica a la alimentación requerida.

Los ínputs de sensores que trabajan a 230V, antes de llegar al controlador deberán pasar por un relé cuyo accionamiento lo controle el sensor y cuyos contactos normalmente cerrados o abiertos abran o cierren un circuito con la tensión de salida de la fuente de alimentación


2.- Montaje de los elementos de las instalaciones domóticas en edificios.
------------------------------------------------------------------------

### Preparado y tendido de conductores del sistema domótico utilizado.

El cable utilizado para el sistema elegido dependerá de la interfaz de entrada y salida elegida así como del controlador. Pudiendo ser cable UTP, un bus KNX, un cableado 400/750V. Cada cableado tiene unas particularidades concretas y se deberá atender a la normativa vigente así como a las instrucciones del fabricante.

No es posible enumerar todos los posibles cableados utilizados pero en el aula practicaremos con el cableado UTP y cableado 400/750. La finalidad del primero es comunicarnos utilizando algún protocolo como MODBUS-TCP/IP, el segundo es el destinado a leer los valores todo-nada de algunos sensores o pulsadores y enviar tensión o no a los actuadores, (como luminarias, o contactores). Se utiliza el mismo cable que en las instalaciones de baja tensión, ya que el voltage que deben soportar es el mismo, y además podrán circular por los mismos registros y canalizaciones al estar aislados para el valor de tensión de red.

### Montaje de sensores y actuadores.

Al igual que el cableado el montaje de sensores y actuadores sigue las instrucciones del fabricante. Se prestará especial atención a los parámetros de funcionamiento, no conectando sensores o actuadores de continua y bajo voltaje a tensión de red.

### Instalación del interface y controlador.

La programación del controlador queda fuera del alcance de este curso, y por lo tanto siempre se contará con un controlador preprogramado. Por ello, se deberán seguir las indicaciones de que bornes de la interfaz de entrada o salida utilizar para cada sensor o actuador respectivamente. Y además se deberán ubicar consecuentemente (por ejemplo, no se debe instalar un sensor de presencia en el aseo, si el controlador espera que se sitúe en la entrada de nuestra casa, aunque se cablee al borne correcto)


3.- Conexionado de los elementos de las instalaciones domótica.
---------------------------------------------------------------

### Procedimientos de conexionado.
### Conexión de sensores.
### Conexionado de actuadores.
### Conexión del equipo de control.


4.- Sustitución de los elementos averiados en las instalaciones domóticas.
--------------------------------------------------------------------------

### Características de las averías típicas de la instalación.
### Tipología de las averías:
#### Averías en sensores y actuadores.
#### Averías del sistema de control.
#### Procedimientos de sustitución de los elementos averiados.
#### Procedimientos de restablecimiento del funcionamiento de la instalación.