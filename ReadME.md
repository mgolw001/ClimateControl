# Temperature Control Bot
## Overview
The input of this system is the ambient temperature that is sensed by the DHT11 Temperature
and Humidity Module. This value is stored as the sole input and is a shared variable so that all
the concurrent state machines can use this value. When the arduino is given power, it
immediately starts sensing without user interaction. Then on its own the temperature gets
displayed and constantly updated onto the 4 digit 7 segment display, and when the threshold
temperature is reached, the fan will turn on, on its own to cool down the surroundings. And again
to limit user interaction, the fan will turn off on its own if the input temperature no longer crosses
the threshold, so when it gets a bit cooler in the room the user does not have to manually turn it
off.

## Materials
- Arduino Uno
- DHT11 Temperature & Humidity Module
- 4 Digit 7 Segment Display
- Motor Driver
- Motor
- Fan
- Shift Register
- Power Supply Module
- 9V Battery
- Resistors - 220 ohms
- Wires

## Software Libraries
- DHT Library
