# SPP_Over_BLE
An Ionic app that emulates something similar to Serial Port Profile (SPP) over Bluetooth Low Energy (BLE) devices

SPP Over BLE

In recent years, and for good reason, Bluetooth Low Energy (BLE) has all but supplanted Classic Bluetooth in most major devices such as mobile phones and tablets. The low power consumption of BLE has also enabled a whole new slew of devices, peripherals and applications that were not possible with BT Classic.

However, communicating with BLE is inherently different than with BT Classic devices. Gone are the old “Profiles” of BT and have been replaced with Attributes and Characteristics. There are good reasons for these radical changes...

However, for many folks who are not intimately familiar with BLE protocols and/or are not professional programmers (many hobbyists or folks who need to rapidly prototype something), not having a simple communication protocol such as the Serial Port Profile (SPP) of BT Classic presents a challenge that is beyond the scope of the project these folks are trying to execute.

The IONIC BLE SPP library is a simple solution to this challenge, solving two fundamental problems:

First, it provides a ready-2-compile Ionic App that can be used as a starting point for folks wanting a mobile app element to their BLE enabled project (for example for having a mobile app interact with an Arduino project). And secondly, it provides a simple “serial port” communications interfaces over BLE, similar to that which was commonly known as SPP in BT Classic. The goal is to remove the nuances of sending and receiving data from a BLE device so that folks can focus on rapidly getting a mobile app communicate with their BLE-enabled hardware.

To do so, we have selected the HM-10 BLE device that is widely and inexpensively available in the marketplace.
