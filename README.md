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
