# ESP IoT Dimmer


![](https://github.com/SasaKaranovic/ESP-IoT-Dimmer/raw/master/Images/IOT-Dimmer-300x169.jpg)
![](https://github.com/SasaKaranovic/ESP-IoT-Dimmer/raw/master/Images/WebInterface-300x203.png)

## Introduction
The ESP IoT Dimmer allows you to create a customizable LED dimmer that can be controlled via any device connected to the network such as PCs, mobiles, or tablets. This project focuses on building a three-channel LED dimmer to manage single RGB LED strips or three distinct LED channels, offering flexible lighting solutions for work or entertainment.

Making a IoT LED dimmer that you can control through your PC, your mobile, tablet or any other device connected to the network is super simple, and I'm going to show you how.

In this project I'm making a three channel LED dimmer that you can use to dim single RGB LED strip or dim three separate LED channels. I want to be able to control lights above my desk and also mix warm white and cool white strip to give me more flexibility over lighting while I'm working, taking pictures or watching movies.

## Features
- **Multi-Channel Control:** Enables management of RGB LED strips or three distinct LED channels.
- **Web-Based Interface:** Allows adjustment of LED intensities via any web-enabled device.
- **Wi-Fi Connectivity:** Provides the ability to connect and control through the local Wi-Fi network.

## Quick Start Guide
1. **Prerequisites:**
   - **LED Strip:** RGB, or 1/2/3 single color LED strip.
   - **NodeMCU:** ESP8266 dev board. [Learn more](https://www.nodemcu.com/index_en.html)
   - **Three N-Channel Power MOSFET:** For driving the LEDs.
   - **Three N-Channel Signal MOSFET:** For controlling the LED's power MOSFETs.
   - **12V Power Adapter:** For powering the LED strip.


2. **Setup:**
   - Follow the [setup guide](https://sasakaranovic.com/projects/iot-led-dimmer/) on the project's home page to set up the hardware and install necessary firmware.

3. **Configuration:**
   - Modify the `ssid` and `password` in the firmware to connect the device to your Wi-Fi network.

4. **Access Interface:**
   - Type `http://dimmer.local` in a web browser to access the web control interface.

