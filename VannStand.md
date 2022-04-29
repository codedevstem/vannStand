# Codename: VannStand

This document is a work in progress.

## Introduction

Using established technology (transit-time-flow-meter) we can measure the flow rate in any pressurised pipe. 
This will enable the consumer to have a live overview of their e

## Prototype parts

Description and functionality of the parts of the units that will measure and send data to a server and database.

### Ultrasonic sensors

Positioned so the sending sensor and the receiving sensor has the same angle on the backside of the inner lining of the pipe, it will measure the flow rate and interperete the output of the sensor to a numeric value. See Links for the ultrasonic sensor amazon sells. 

### Wifi module

Should be able to connect to the home wifi 2.4Ghz, and pass the data onwards to a server cluster where the data can be presented back to the home owner in near real-time. 

### Fastening module

Clamps down on the pipe. In the first prototype this should be created with the dimentions of the test pipe known.
In time this should regulate the ultrasonic sensors to automatically match the pipe inner dimentions.
This should be possible to calculate using the same ultrasonic sensors through trial and error. 

### Estimated total cost

The cost for producing one unit is estimated to total around $ 30-50 per unit excluding assembly. 

## Business case

- Sale of hardware.
- Subscription for analysis / comparison / historical data.
- Backup (Delivery of units for governmental efforts to archive this goal)


## Abilities

- Low wear and tear
- Instant read of water volume (**V = 0.408 × Flow rate/Pipe Diameter^2**)
- Low effort to install
- Non-intrusive design

## Links 

- [Explatation of the technology](https://instrumentationtools.com/transit-time-flow-meter/)
- [Ultrasonic sensors for production](https://www.amazon.com/HiLetgo-HC-SR04-Ultrasonic-Distance-MEGA2560/dp/B00E87VXH0/ref=sr_1_8?keywords=ultrasonic+sensors&qid=1651234982&sr=8-8)

