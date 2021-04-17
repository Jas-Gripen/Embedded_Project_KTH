# II1302
This is the C code for the project that I did in the course II1302 at KTH Kista together with Arthur Simonsson, Botan Cosar and Sebastian Thunberg. The code was written in CubeMX which generated initialization code for the peripherals according to our specifications. I wrote most of the code for the ESP8266 as well as the main project program which contains the super loop. I also did most of the initialization for the peripherals. 

## Hardware
- Microcontroller: STM32L476G Discovery
- WIFI Module: ESP8266
- OLED Display
- Breadboard
- Jumper wires
- Push button

## Functionality
The ESP8266 uses AT commands to contact a server, which stores messages, and sends them over UART to the microcontroller which displays them on the OLED Display. The owner of the product can chose which message that should be displayed on the OLED. The product also has a button that a user can press to toggle between the message and a QR-code which directs the user to the website wich stores the messages.
