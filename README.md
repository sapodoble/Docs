Overview
========

This documentation will try to cover different aspects of the Thinger.io platform in terms of hardware integration, cloud console, server a API, and server deployment.

Hardware Integration
==================

This section will cover how to program your hardware to connect and use the Thinger.io platform. As there are many IoT hardware available nowadays, this section is divided in different categories.

There is a category related with Arduino compatible hardware, which is any board you can program with the Arduino IDE (Arduino + Ethernet, Arduino + Wifi, ESP8266, NodeMCU, TI CC3200, etc). There is other general category related with Linux powered devices like the Raspberry Pi, Intel Edison, or any other Linux computer running Ubuntu or MacOS. Finally, there is a section that will cover the integration with the ARM Mbed platform and compatible devices.

So, to start using the platform select the hardware platform you want to use.

## Arduino

This category is related with any hardware that can be programmed over the Arduino IDE and its libraries. So it is not exclusively for Arduino Devices, as you can also program different boards like the ESP8266, or Texas Instruments CC3200 board. Of course, you can still use any other Arduino Board with Ethernet of Wifi capabilities.

<p align="center">
<a href="arduino">
<img src="assets/arduino-logo.png" width="300px">
</a>
</p>

## Linux

If you want to develop an IoT product or project based on a device running Linux OS, there is also an special client for this platform. There are some specific examples for each common Linux board like Raspberry Pi or Intel Edison. But you can run the client in practically any computer running a Linux distribution, including a computer with Mac OS.

<p align="center">
<a href="linux">
<img src="assets/raspberry-pi.png" width="175px">
</a>
</p>

<p align="center">
<img src="assets/computer_edison.png" width="325px">
</p>

<p align="center">
<img src="assets/linux-logo.png" width="300px">
</p>

## ARM Mbed

ARM is building its own IoT ecosystem in the cloud, mainly to simplify the development process in any ARM mBed compatible hardware. So, if you have an ARM mBed compatible board, this is your place.

<p align="center">
<img src="assets/mbed-enabled-logo.png" width="200px">
</p>


Cloud Console
=============

The Cloud Console is related with the management front-end designed to easily manage your devices and visualize its information in the cloud. In this section you will learn how to register devices, create real-time dashboards, access the devices API, and other management operations.

<p align="center">
<a href="console">
<img src="assets/console.png" width="350px">
</a>
</p>


Server API
==========

The Thinger.io Cloud is supported by a REST API designed to easily integrate your IoT projects with other applications like WebServices, mobile phones, or desktop applications. So if you want to integrate your device with your own application or service, then this is the starting point.

<p align="center">
<img src="assets/api.png" width="250px">
</p>

Server Deployment
=================

This section is related with the Cloud configuration and deployment in your own infrastructure, both in local machines or in the cloud.

<p align="center">
<img src="assets/docker-logo.png" width="300px">
</p>

