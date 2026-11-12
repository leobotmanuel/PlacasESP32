En un sistema de control unos dispositivos (microcontrolador, sensores, actuadores) y tipos de configuración de los dispositivos que forman el sistema de control.

### <FONT COLOR=#007575>**Dispositivos**</font>

Los dispositivos básicamente de agrupan en tres bloques.

![dispositivosBloques](../img/sistControl/dispositivosBloques.png)

* **Elementos de entrada**: serán sensores que se le pueden conectar a nuestro sistema de control, pueden ser: pulsadores, interruptores, finales de carrera, ntc, ldr, etc.
  
* **Elementos de proceso o control**: son los que se van a programar, recibirán datos de los elementos de entrada para decidir que realizar con los elementos de salida.

* **Elementos de salida**: van a ser los actuadores, los que va a decidir nuestro programa poner en funcionamiento y de que manera o parar, como: diodos leds, zumbadores, motores, etc.

### <FONT COLOR=#007575>**Configuraciones**</font>

### <FONT COLOR=#007575>Lazo Abierto</font>

No hay una realimentación, lo que significa el controlador da una orden de puesta en marcha a los actuadores sin que se vigile en ningún momento la señal de los sensores (elementos de entrada).

![lazo_abierto_01](../img/sistControl/lazo_abierto_01.png) 

![lazo_abierto_02](../img/sistControl/lazo_abierto_02.png)

### <FONT COLOR=#007575>Lazo Cerrado</font>

Hay realimentación, lo que quiere decir que el sistema de control siempre está vigilando los sensores (elementos de entrada) para realizar una acción u otra en función del estado de los mismos.

![lazo_cerrado_01](../img/sistControl/lazo_cerrado_01.png)

![lazo_cerrado_02](../img/sistControl/lazo_cerrado_02.png)