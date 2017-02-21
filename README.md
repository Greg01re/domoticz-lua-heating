# domoticz-lua-heating
A Domoticz heating regulation lua script.

This script provides heating control in a room, providing different modes (Comfort, Eco), according to presence in the room and to a couple of setpoints.

The heating control is proposed with two differents algorithms (Hysterisis or PID). The script supports multiple temperature control devices used in fallback, and multiple heating devices used simultaneously. A power consumption computation is made, based on the declared power consumption of each heating device.
