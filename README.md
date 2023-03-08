# Dual-Garage-Controller
ESP32 Controller to control dual garage doors with car presence detection and lighting control

Version 1 of the dual garage controller 
Using AMS1117-5v as the main power supply lets the unit be powered from 9v to 12v, Micro USB gives 5v supply and access for programing through the CH340G chip.

Main controller is an ESP32.
Outputs -2 relays to drive the garage doors, 2 relays opto-isolated for AC/DC to control lights if required
        -2 i2c headers for attaced devices eg. BME280
        -All unused GPIO's broken out for expandability.

Inputs  -2 terminals for garage closed detection with reed switches 
        -2 Ultrasonic sensors for car detection sensors

<a href="https://www.buymeacoffee.com/tfd0422i" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy Me A Coffee" height="41" width="174"></a
