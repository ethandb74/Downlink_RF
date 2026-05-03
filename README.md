# Downlink_RF
4-layer PCB LoRa Puck:

This is a usb powereed LoRA Transmitter made for long range comnmunication with a programmable OLED display. This project was built around the SX1262 Radio chip and the RP2040 microcontroller. 
This project is inteded to be used as an alternative to using esp32 wireless communcation protocol (ESPNOW). this provides longer range and a seperate module making it a workaround to (in my experience) an often unrealiable communcation protocol. I learned the basics of RF pcb desing with the ultimiate goal of understanding all the systems of a cubeSat. This Satlite subsystem focus inspired the name Downlink. 


This Trasmitter is a 4 layer PCB

:
-      Fcu - singal 
 -     In1.cu - GND plane (Earth)
  -     In3.cu- +3V3 power plane
   -     Bcu- secondary signal




Main power for the module is delived via USB-C

RF: traces are routed at 0.1756mm width for 50ohm impedance  and IPD handels most of the Frontend with the exception of a pi circuit 

Frequency and Band 
--
This Puck transmits at 915Mhz or the ISM band
This band is license free and causes no issue with the FCC 

Schematic
--
orginized into sections with power/ memeory/ RF/ Microcontoller/ 

<img width="1119" height="723" alt="Screenshot 2026-04-23 175019" src="https://github.com/user-attachments/assets/40afe50c-aa8e-4109-83b4-a37c389b4bb3" />


PCB
--
4-layer traces are routed at 0.1756mm width for 50ohm impedance no right angles tight via fencing around the RF section 

<img width="1110" height="646" alt="Screenshot 2026-05-01 164421" src="https://github.com/user-attachments/assets/1400858f-ea73-4ae5-ba33-98dcc7a3e9aa" />

Kepp in mind the photo above is before some final iterations This is a 3d model of the Finished PCB:
<img width="1468" height="832" alt="Screenshot 2026-05-02 165047" src="https://github.com/user-attachments/assets/4793b8dc-8ff6-426b-81df-c84f4176b279" />

BOM:
Attached is a link to the BOM with the individual Componants for the PCB
[Bom Link](BOM/Downlink_RF.csv)






