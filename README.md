# SunSynk-ESPHome

ESPHome Project to establish communication with SunSynk 8.8kW & 5.5kW Inverter via RS485 Modbus.
The code is based on Modbus registers from SunSynk.


## Components.

WEMOS ESP32 Lite V1.0.0 Lolin32 Wifi Bluetooth Board CH340G MicroPython.

 ![image](https://github.com/tmh88/SunSynk-ESPHome/assets/64529041/9e1ca95e-830e-4158-8557-add443563313)

https://kunkune.co.uk/shop/esp32-esp8266/wemos-lolin32-esp32-lite-v1-0-0-wifi-bluetooth-board-ch340g-micropython/?fbclid=IwAR130c3W75-MvHVIQRkaq919oVmQM71DfNW_I4CI16sr6qBjoB76vTmjVCs

RS485 module to TTL with Isolation Single Chip Microcontroller UART Serial Port.

 ![image](https://github.com/tmh88/SunSynk-ESPHome/assets/64529041/abfc6147-6111-4ed7-9103-4789ae8c0975)

https://kunkune.co.uk/shop/communication-boards/rs485-module-to-ttl-with-isolation-single-chip-microcontroller-uart-serial-port/?fbclid=IwAR0-Ap4bn00M6TSlwINBr1PfITM7QJWwbq9NOitrLwNkRpegcCKPePa97Lg

USB power supply and suitable enclosure.

## Connections.

![image](https://github.com/tmh88/SunSynk-ESPHome/assets/64529041/cb059cfb-b86a-4b3e-90fb-8a866dfeb952)

## 5.5kW & 8.5kW with combind BMS 2in1 Port.

![image](https://github.com/tmh88/SunSynk-ESPHome/assets/64529041/ed9f2e3b-a0c9-498f-b86a-3d12ec07efef)

The 8kW inverter uses a combined BMS 2in1 Port located below.

![image](https://github.com/tmh88/SunSynk-ESPHome/assets/64529041/91324677-d395-4286-b9b7-e1a9dc8699b6)

## 5.5kW with Separate CAN & RS485 Ports.

Use Pins 1 & 7 as pin2 isn’t connected on the PCB

Pin1 = Orange/White = (A)

Pin7 = Brown/White = (B)


![image](https://github.com/tmh88/SunSynk-ESPHome/assets/64529041/fee9901a-87c0-4516-ad39-8ca6d112aaee)

![image](https://github.com/tmh88/SunSynk-ESPHome/assets/64529041/6c15d0b7-b05d-4d2e-a625-35e3ad27b5b8)


## Inverter Settings.

Under the Advance Tab ensure the following settings are set.

![image](https://github.com/tmh88/SunSynk-ESPHome/assets/64529041/4641d8dc-8c1d-43dc-8bd5-9fc7c54d045b)

## Home Assistant Sensors.

![image](https://github.com/tmh88/SunSynk-ESPHome/assets/64529041/4e40d330-c75b-4e63-85e4-fb7a0d046c6a)

![image](https://github.com/tmh88/SunSynk-ESPHome/assets/64529041/0908f798-dca5-463e-8943-8493e75a6e39)

![image](https://github.com/tmh88/SunSynk-ESPHome/assets/64529041/f9592d58-171e-40f5-b8e7-29be796c736c)

![image](https://github.com/tmh88/SunSynk-ESPHome/assets/64529041/5c232b77-ab9a-44dc-9515-f1f7ecec5444)

![image](https://github.com/tmh88/SunSynk-ESPHome/assets/64529041/defb8fb8-c872-4492-8885-efc5e764e6a8)

![image](https://github.com/tmh88/SunSynk-ESPHome/assets/64529041/1232b788-0735-48ec-b512-598f9044d842)

![image](https://github.com/tmh88/SunSynk-ESPHome/assets/64529041/482d19ca-f02a-4635-a1be-2d37faf92526)

![image](https://github.com/tmh88/SunSynk-ESPHome/assets/64529041/0321d98f-12a8-40d4-a2b0-d4031d7213e6)



## Disclaimer.
The project is something I have developed and researched myself. I cannot accept any responsibility for any damage caused to your equipment. Please install at your own risk.

