# ozm10_appliances_transitorios
Analisis medida de 10 aplicativos incluyendo transitorios  hasta el orden 150 de tension, corriente y potencia. Las Medidas  se realizan con 3  OpenZMeter  Trifásico  (cada uno con 4 canales de medida)  para  10 aplicativos, mas el agregado.

Las medidas corresponden a W, VAR, VA,f, VLN,PF y A, mas los transitioros  hasta el orden 150 de W, V y A,   todas con un marca de tiempo ( Timestamp) de 13 dígitos.

Las medidas se realizaron el 10 de Marzo de 2033  en el Laboratorio de Electrotecnia de la  Escuela de Ingenieria Industrial de la Universidad de Almeria.

Las medidas fueron tomadas entre las 11:10 y las 13:12.
  
Para el  entrenamiento se  han definido tres periodos:

 - TRAIN: 11:10 a 12:10 

 - VAL: 12:10 a 12:41
 
 - TEST: 12:41 a 13:12
 
 Estos datos se entrenaron, tanto con el algoritmo CO, como el algoritmo FHMM,


Los aplicativos  usados en el experimento son los siguintes:

 1 -Main
 
2 - Electric Furnace ( Horno)

3- Microwave (Microonda)

4 - Television

5 - Kettle ( hervidor de agua)

6 - Vacuum Cleaner ( Aspiradora)

7- Electric Space Heater ( Radiador de aceite)

8 - Electric Shower Heater  (Calentador de agua)

9 - Fan  ( Ventilador)

10 - Fridge  ( refrigerador)

11 -  Freezer (congelador)


