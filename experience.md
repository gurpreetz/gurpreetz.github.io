---
layout: page
title: Experience
permalink: /experience/
---
### [Juniper Networks](https://www.juniper.net), Cupertino, CA
##### (Mist Systems acquired by Juniper Networks)
###### Dec 2021 – Present
_Software Engineering Sr Manager, AP Firmware_
* Manage a global team of 5 engineers to design and implement:
  * Wired Synthetic Testing on a network
  * Mesh and Client Bridge on all Access Points
  * Local distribution of 11r keys to allow for faster and seamless roaming
  * Cloud based power tables to better handle regulatory changes of wireless networks

###### Apr 2019 – Dec 2021
_Senior Staff Software Engineer, AP Firmware_
* Team Lead for the bring up of the 6GHz Wireless Access Points([AP45](https://www.juniper.net/us/en/products/access-points/ap45-access-point.html) & [AP34](https://www.juniper.net/us/en/products/access-points/ap34-access-point.html))
* Cloud driven Access Point Upgrades
  * Systemic improvements to all Cloud to AP upgrades
  * Productized peer to peer AP upgrades
    * Successfully upgraded over 5000 APs at a time, across various customer sites 
* Architect for AP FIPS Development
  * Designed, Implemented and Verified a FIPS (140-2) [Certified](https://csrc.nist.gov/projects/cryptographic-module-validation-program/certificate/3901) upgrade process
  * Firmware improvements to allow for crypto and firmware self validation on demand as well as on system boot
  * Zeroization of APs in case of extreme security violations
  * Implemented an SP800-90B Compliant HWRNG Device Driver based on the ATECC608A TPM
* Designed, Implemented and [Patented](https://uspto.report/patent/grant/10862742) a method for conveying AP error codes over BLE advertisements
* Firmware stability and scalability improvements including, but not limited to
  * Automatic recovery from bad configuration
  * Prevent booting into unreliable, or bad, firmware partitions
* Created a Wireless Hardware Abstraction Layer to simplify application development across the 802.11ac and 802.11ax family of APs

### [Mist Systems](https://www.mist.com/), Cupertino, CA
###### Nov 2016 – Present 
_Member of Technical Staff, AP Firmware_

* Technical Lead for BLE related development on the Access Point
  * Development of firmware on the Mist family of [wireless access points](https://www.mist.com/wireless-access-points/) 
for all BLE related functionality, including, but not limited to
    * interleaving of Mist's patented vBLE, iBeacon, Eddystone-UID, and Eddystone-URL BLE beacon frame formats 
    * scanning as well as advertising together, to allow functionality such as way-finding and asset tracking 
to run in conjunction
    * packet decoding to facilitate BLE analytics
    * power control for transmission of the BLE Signal from the Access Point
  * Design and prototyping of BLE functionality on the nrf52 family using [Zephyr](https://github.com/zephyrproject-rtos/zephyr)
  * Research in [passive analytics](https://www.mist.com/bluetooth-le-privacy/) of BLE devices including decoding 
of standard as well as proprietary BLE advertisements 
* WiFi threat detection and mitigation for
  * Rogue access points and clients
  * HoneyPots
* Bring up of 802.11ax wireless utility and driver
* Implemented mechanisms and new messaging schemes to reduce load on the cloud based micro-services while reporting information from the access points such as
  * BloomFilter based filtering on Connected Wireless Clients and BLE Assets of Interest
  * Creation of new, smaller kafka topics to reduce load on cloud based subscribers
* Prototyped means of peer to peer upgrades of Access Points
* Work closely with the factory for device certification and to facilitate ease of manufacturing

### [Blue Clover Devices](https://www.bcdevices.com/), San Francisco, CA
###### July 2015 – Nov 2016    
_Senior Firmware Engineer, Internet of Things R&D_

* Firmware development of an Apple HomeKit (WiFi) compliant, IoT environmental mult-sensor ([iHome ISS50](https://www.ihomeaudio.com/iSS50/)) for the home
  * Implemented Device Drivers for Ambient Light, Motion, Temperature & Humidity Sensors as well as for the LCD Panel and Display Backlight
  * Created an algorithm to automatically adjust the backlight based on ambient light 
  * Worked with the Hardware team to calibrate temperature, humidity and light readings
  * Held regular meetings with the customer to gather requirements, and subsequently to report on the project status 
* Initiated and Created an [open-source GoLang based tool](https://github.com/gurpreetz/ble-tools) to help with BLE 
device development which can
  * Scan for all devices advertising in the area, and connect to them
  * Connect to specific devices and creates an XML as well as human readable summary of services and characteristics supported by the BLE device
  * Compare BLE interface design with implementation to detect inconsistencies
* Designed and implemented the Firmware and BLE Interface and for a smart lamp

### [Alcatel-Lucent](https://networks.nokia.com/), Mountain View, CA
###### September 2009 – July 2015                                                                           
_Senior Staff Engineer, IP Division (Mobile Group)_

* Led the design and development of the session manager for the Alcatel-Lucent GGSN. 
* Designed and developed UE initiated call flows, at the Gn interface, viz. Create, Update, and Delete of PDP Contexts, handovers (inter and intra SGSN), support for bearer binding (without and without PCRF support), and triggers for accounting (at the Ga interface).
* Led the design and implementation of Lawful Intercept (LI) support for the GGSN, SGW, and PGW, including support for all Intercept Related Information (IRI) messages on the Control Plane
* Designed and developed handling of Time-Of-Day support for policy rule installation when signaled from the PCRF
* Implemented a DNS based white-listing mechanism on the PGW and GGSN to divert traffic for Deep Packet Inspection (DPI)
* Add support for handling of Gx Time of Day Procedures for the PGW and GGSN, processing extremely high scale messaging between various modules on the control and data planes.
* Developed a message batching mechanism to reduce the latency in messaging between the control and data planes for the [SGW, PGW, and the GGSN](https://networks.nokia.com/products/7750-service-router/mobile-gateway). 
* Added support for handling the Protocol Configuration Options (PCO) at the PGW and the GGSN. 

### [Cisco Systems Inc](https://www.cisco.com/), San Jose, CA 
##### June 2008 – September 2009
_Software Engineer (Mobility Services and Location Engineering) Wireless and Security Technology Group_

* Designed the network calibration tool on the Wireless Control System ([WCS](https://www.cisco.com/c/en/us/products/wireless/wireless-control-system/index.html)) to improve location accuracy on WiFi Networks.
* Added support for Network Mobility Services Protocol (NMSP) version 2 on the Mobility Services Engine (MSE)  to improve the accuracy of indoor wireless location. Collaborated with the Cisco Wireless LAN Controller team to ensure the protocol changes were seamless to the overall system.
* Improved the overall usability of the location aspects of the WCS. 
* Created and tested a demo iPhone application to show the basic alarm dashboard of the WCS. This was demonstrated at the Cisco Global Sales Meeting, 2008.

### [Apple Inc](https://www.apple.com/), Cupertino, CA
##### May 2007 – August 2007
_Engineering Intern, Exploratory Design Group_

 Developed a prototype command and event mechanism for seamless network handover between IEEE 802.11, Ethernet, and HSDPA networks based on the draft IEEE 802.21 standard.
 
### [Tata Consultancy Services Ltd](https://www.tcs.com/), Bangalore, India 
##### July 2004 – July 2006
_Assistant Systems Engineer, Wireless Communications R&D_

* Led the research on Game Theory and its applications to Medium Access issues in Wireless Communications.
* Conducted research on various aspects of the IEEE 802.15.3 and IEEE 802.15.4 standards to develop an adaptive personal network.
* Developed simulation environment in ns2 for simulating 802.15.3 and 802.15.4 based WPANs which was demonstrated at International Wireless Summit 2005, Aalborg, Denmark in September 2005, and at the MOCCA-WWI symposium at Paris in December 2005.
* Developed the Medium Access Control (MAC) layer of the IEEE 802.15.3 standard.   
