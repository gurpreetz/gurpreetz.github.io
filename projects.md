---
layout: page
title: Projects & Patents
permalink: /projects/
---

## Patents
### Orientation based transmission power ([USPTO 11,917,554](https://uspto.report/patent/app/20220295420))
Disclosed are embodiments of a device that includes an orientation sensor. Based on the device's orientation,
a transmit power of the device is limited to ensure that transmission of the device do not exceed regulatory
requirements. The transmit power limit is based, in some embodiments, on a manufacturer or model of the device,
which indicates a position of one or more antennas relative to the device, and allows for a determination of
an amount of power transmitted above the horizon in a given orientation.


### Method for conveying AP error codes over BLE advertisements ([USPTO 10,862,742](https://uspto.report/patent/grant/10862742))
Methods and apparatus for automatically obtaining status from an isolated AP that cannot connect to the cloud.
The obtained status information is then used to automatically mitigate the issue and accelerate connecting the
isolated AP back to the cloud. The methods are well suited for use in a system with a variety of access points,
e.g., wireless and/or wired access points, which can be used to obtain access to the Internet or another network
such as "the cloud". Network management system has been configured to monitor the network and use preconfigured
data to determine a remedial action to be automatically taken when an AP loses connectivity with the cloud.

## Projects
### [I'm Home](https://github.com/gurpreetz/imhome)
##### May 2019
A simple introduction to some IoT work in a GoLang based system. 

This project turns on the lights in my apartment whenever a specifiend device connects to the wireless network. 
I leverage a Mist access point and its open [APIs](https://api-class.mist.com/) to determine when my phone connects to 
my home WiFi network. This then automatically triggers a push to [IFTTT](https://ifttt.com/) to trigger my 
smart outlet to turn on, thus ensuring I never walk into my apartment in the dark. 


### [BLE Tools](https://github.com/gurpreetz/ble-tools)
##### Summer 2016
An open-source GoLang based tool to help with Bluetooth Low Energy device development. The tool can
  * Scan for all devices advertising in the area, and connect to them
  * Connect to specific devices and create an XML as well as human readable summary of services and characteristics supported by the BLE device
  * Compare BLE interface design with implementation to detect inconsistencies
