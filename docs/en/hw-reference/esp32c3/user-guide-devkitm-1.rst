==================

ESP32C3-Connect&Control-Mini-PCB 
==================


This documentation is a description of PCB Module named "ESP32C3-Connect&Control-Mini-PCB".
The purpose of this module is to connect two power tools for them to work in coordination and synchronization. 
As a basis Module, later implement in , to internet of ... This document also provide in-depth information for further development of "Internet of power tools".


ESP32C3-Connect&Control-Mini-PCB  is a self-made PCB circuit board based on ESP32-C3-MINI-1, a module named for its small size. This board integrates complete Wi-Fi and Bluetooth LE functions.

# General function description

Communication protocol:
using ESP-NOW communication mechanism, a master/slave hierarchy, Message transfer (Tool status, Current draw, Error, ID, …)
Current and Voltage sensing
Power Switch



there are several versions:
Small version (SMT):
DC<24v 
Current sense 10A  (easy to change)


Cheap version (THT):
DC<24v 
Current sense 10A  (easy to change)
MosFet







.. figure:: ../../../_static/Flex_THTMosPlatine.PNG
    :align: center
    :alt: ESP32-C3-DevKitM-1
    :figclass: align-center



# AI application