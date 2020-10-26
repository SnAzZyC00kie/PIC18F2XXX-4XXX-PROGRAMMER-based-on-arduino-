# PIC18F2XXX-4XXX-PROGRAMMER-based-on-arduino-
this is a PIC18F2XXX/4XXX  programmer using arduino UNO and a simple Windows console app ,
it simple to use , just copy the HEX file path generated by MPLAB or other programes  then pass it 
to the app and connect your arduino UNO to your computer then  press OK ,  the programmer start programming immediately 
with a nice progress bar showing up , after the programmer finish programming a message box will pop up telling you the programming proccess was done 

# list of supported PIC devices 

• PIC18F2221    • PIC18F2580    • PIC18F4480  
• PIC18F2321    • PIC18F2585    • PIC18F4510  
• PIC18F2410    • PIC18F2610    • PIC18F4515  
• PIC18F2420    • PIC18F2620    • PIC18F4520  
• PIC18F2423    • PIC18F2680    • PIC18F4523  
• PIC18F2450    • PIC18F2682    • PIC18F4525  
• PIC18F2455    • PIC18F2685    • PIC18F4550  
• PIC18F2458    • PIC18F4221    • PIC18F4553  
• PIC18F2480    • PIC18F4321    • PIC18F4580  
• PIC18F2510    • PIC18F4410    • PIC18F4585  
• PIC18F2515    • PIC18F4420    • PIC18F4610  
• PIC18F2520    • PIC18F4423    • PIC18F4620   
• PIC18F2523    • PIC18F4450    • PIC18F4680  
• PIC18F2525    • PIC18F4455    • PIC18F4682  
• PIC18F2550    • PIC18F4458    • PIC18F4685  
• PIC18F2553  

# pin connection 

**notice :** The programmer use the LVP mode to program the PIC18F
                                        


|    pin name   | pin name  | pin type |  pin Description       |            Arduino UNO pins           |
|:---:|:---:|:---:|           :---:        |                 :---:                 |
| MCCRL/Vpp/RE3 |   VPP     |     P    | Programming Enable     | connected to  pin 2 on Arduino UNO    |
|      VDD      |   VDD     |     P    | Power Supply           | connected to pin 5V on Arduino UNO    |
|      VSS      |   VSS     |     P    | Ground                 | connected to pin GND on Arduino UNO   |
|      RB5      |   PGM     |     I    | Low_Voltage ICSP input | connected to pin 5 on Arduino UNO     |
|      RB6      |   PGC     |     I    | Serial Clock           | connected to pin 4 on Arduino UNO     |
|      RB7      |   PGD     |    I/O   | Serial Data            | connected to pin 3 on Arduino UNO     |


for more details on PIC18 memory programming  read the **Flash Microcontroller Programming Specification  (by microchip)** found on **PIC18F_EEPROM** pdf file 


# programmer testing 

<iframe width="560" height="315" src="https://www.youtube.com/embed/b8vQ04u813Y" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>






