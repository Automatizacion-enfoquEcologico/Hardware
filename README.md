# Hardware

En este modulo se encuentra la impelemnetacion de la instrumentacion de todos los circuitos utilizados durante el proyecto.

## Implementación 
- [Sensores](#sensores) 
- [Salidas](#salidas)
- [Circuitos de adquisición](#circuitos-de-adquisición) 
- [Datasheet](#datasheet) 

## Sensores: 
  1. **Analógicos**:
      - **Sensores de Temperatura LM35**: Se implementaron dos sensores de temperatura, uno se encarga de medir la temperatura  interna del hogar, y el otro la externa. Con estas variables el usuario podrá decidir la temperatura interna de su hogar.            

      - **Sensor de corriente**: Este sensor le permitirá al usuario monitorear el consumo eléctrico de su hogar ayudando a que el mismo se pueda optimizar. 

      - **Sensor de luz (LDR)**: Permite saber cuánta luz del sol están recibiendo las plantas, y así en conjunto con la información proporcionada por el higrómetro (Sensor de Humedad), el sistema de manera automática podrá decidir cuándo regar las plantas.     
  
      - **Sensor de Caudal (Simulado)**: Permite medir la cantidad de agua que fluye por las tuberías del hogar. Este sensor mediante un encoder, debido a  que el laboratorio C no cuenta con uno y el mismo es demasiado costoso para su adquisición.
      
  2. **Digitales**:
      -**Sensor de humedad (Higrómetro)**: Permite medir la cantidad de humedad en el suelo, esta información la utilizara el sistema para decidir cuándo regar las plantas.
      
      -**Sensor de Movimiento (PIR)**: Permite saber cuándo hay o no movimiento en una habitación, de esta forma el sistema sabrá cuando apagar de manera automática el aire acondicionado y las luces.
      
      -**Sensor magnético (Apertura de puertas)**: Permite al sistema saber cuándo la puerta de la habitación se encuentra abierta para de esta manera avisar al usuario, si el aire acondicionado en esta habitación se encuentra encendido 

## Salidas:
  Se implementaros 3 salidas del sistema:
  
  -**Salida  PWM**: Se encarga de regular la intensidad de la luz en la habitación. 
  
  -**Salida Digital**: Son el riego y el aire acondicionado, las mismas activan dos Relés Asociados a cada una de estas.
 
 ## Circuitos de adquisición:
  Los siguientes circuitos fueron los implantados para adquirir las señales analógicas provenientes de los sensores. 
  
  **LDR**:
  
   ![Circuito de acondicionamiento del LDR](https://github.com/Automatizacion-enfoquEcologico/Hardware/blob/master/circuito%20de%20acondicionamiento%20LDR.JPG)
  **Corriente**:
  
  ![Circuito de acondicionamiento del sensor de corriente](https://github.com/Automatizacion-enfoquEcologico/Hardware/blob/master/circuito%20de%20acondicionamiento%20Sensore%20de%20Corriente.JPG)
  **Temperatura**:
  
   ![Circuito de acondicionamiento del sensor de temperatura](https://github.com/Automatizacion-enfoquEcologico/Hardware/blob/master/circuito%20de%20acondicionamiento%20LM35.JPG)

## Datasheet:
  Datasheet de los sensores implementados:
  
  -[LM35](http://www.ti.com/lit/ds/symlink/lm35.pdf)
  -[LDR](http://kennarar.vma.is/thor/v2011/vgr402/ldr.pdf)
  -[Corriente]()
  -[Caudal](http://www.elco-holding.com/Upload/pdf/product/ProcessSensors/FS/FS400.pdf)
  -[REED](https://standexelectronics.com/wp-content/uploads/OKI_Reed_Switch_ORD213.pdf)
  -[PIR](https://cdn-learn.adafruit.com/downloads/pdf/pir-passive-infrared-proximity-motion-sensor.pdf)

