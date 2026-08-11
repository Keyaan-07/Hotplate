# Hotplate
An open-source hotplate designed to take power from USB type-C and then be configured and controlled over Wi-Fi. It uses the ESP32-C3 microcontroller, along with 16MB of storage. There are two terminal blocks to connect with the heating element and it's temperature sensor. There is short circuit protection along with accurate current measurement on the power lines. The control frequency is 10KHz for the heating element.

### Why i made this project
I really wanted to build a custom hotplate so that i could make my own PCBs with ease and not struggle!
The heating element is made up of an aluminium PCB so that there is good thermal conductivity.


### Assembly instructions
1. Upload the gerber files from the [production](/hardware/production/) folder to your specific PCB fab. 
2. Order PCBs and a stencil for soldering. 
3. Order all the parts from the links in the [bom.csv](/bom.csv) file. 
4. Get some solder paste and paste it onto the PCB. pick and place all the components. 
5. heat the PCB in an oven/a reflow station. 
6. connect all the THT components
7. flash the firmware via a USB to UART converter. 
8. connect the heating element. You are done!

