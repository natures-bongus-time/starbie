# Starbie



Starbie is a tiny motion-controlled digital pet
## What it is

It's a tamagotchi-like pet that has two keys, a screen and a temperature and humidity sensor, and it's based off of a [starboy](https://lilguy.net)

## Features
- It can tell you the temperature with a dht 11 sensor
- sense motions with an accelerometer
- it has stats that you have to keep up to keep it happy, which are programmed on Arduino ide
- be fed, play, sleep and more all of which are animations selectable from a motion controlled radial menu
- it will react if you shake it from the motion sensor, but it doesn't really like that

## Why?

This project was created for my week 1 beginner project for [half-life](https://halflife.hackclub.com/)!
I chose it because I'm super new to hardware, so the project guide was super helpful. I wanted to learn how to make projects like this because it's a new and interesting challenge that is super engaging for me, and I had a lot of fun with it.

## Project status

the design and firmware are included, and they're both finished.
## Software

[`Firmware/`](Firmware/) contains one self-contained Arduino IDE sketch for the XIAO ESP32-C3. I added some code and keyboard compatibility.
## Images
<img width="676" height="370" alt="Screenshot 2026-10-25 093637" src="https://github.com/user-attachments/assets/0691529e-4373-4f88-a810-c1c4fe77cec2" />
<img width="749" height="441" alt="Screenshot 2026-10-25 093643" src="https://github.com/user-attachments/assets/3c3644a3-9dfe-4965-85b3-8286ab61ed79" />
above: renders of the PCB
below: the schematic
<img width="1453" height="770" alt="Screenshot 2026-10-25 093653" src="https://github.com/user-attachments/assets/ee6db62d-1918-4af7-a96f-7dcd523b7d70" />
<img width="408" height="134" alt="Screenshot 2026-10-08 173905" src="https://github.com/user-attachments/assets/0de9a782-876e-47d6-9734-e6835257b7c2" />
 <img width="696" height="720" alt="image" src="https://github.com/user-attachments/assets/0b6801a8-a435-4d35-b59f-301ad88e4a07" />

 
# BOM

|Item                   |Qty,      |Supplier    |,Cost/item,|Total Cost|link                                                                                      |
|-----------------------|----------|------------|-----------|----------|------------------------------------------------------------------------------------------|
|XIAO ESP32 C3          |1         |Seeedstudio |$5.00      |          |https://www.seeedstudio.com/Seeed-XIAO-ESP32C3-p-5431.html                                |
|0.96 OLED              |1         |digikey     |$5.00      |$5.00     |https://www.digikey.com/en/products/detail/universal-solder-electronics-ltd/26377/16822115|
|3647-26098-ND          |1         |digikey     |$2.75      |$2.75     |https://www.digikey.com/en/products/detail/universal-solder-electronics-ltd/26098/26606388|
|DHT11                  |1         |digikey     |$2.39      |$2.39     |https://www.digikey.com/en/products/detail/universal-solder-electronics-ltd/26085/16822119|
|MX Switches            |2         |digikey     |$0.89      |$1.78     |https://www.digikey.com/en/products/detail/e-switch/TL2201OAYA/583531                     |
|10k Resistor           |1         |digikey     |$0.20      |$0.20     |https://www.digikey.com/en/products/detail/stackpole-electronics-inc/CF14JT10K0/1741265   |
|PCB                    |1         |JLCPCB      |$7.10      |$7.10     |https://www.jlcpcb.com/                                                                   |
Estimated total shipping|          |            |           |$5.00     |                                                                                          |

