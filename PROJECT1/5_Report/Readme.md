# BICOM_SYSTEM


# INTRODUCTION 

This BiCom system is the extention of the unidirectional RKE to bidirectional RKE system. Here the bi-directional communication takes place in between the keyfob and the car. As we have seen the unidirectional in Remote Keyless Entry(RKE), now in BiCom system we will witness bi-directionaL. Information from keyfob to car viceversa. The status of the car will also be displayed on the keyfob by LED or display.

# DISCRIPTION

Description Keyless remotes contain a short-range radio transmitter, and must be within a certain range, usually 5-20 meters, of the car to work. When a button is pushed, it sends a coded signal by radio waves to a receiver unit in the car, which locks or unlocks the door. This is dual communication system where the vehicle sends the car battery info, window, door and alarm status to the user. Most RKES operate at a frequency of 315 MHz for North America-made cars and at 433.92 MHz for European, Japanese and Asian cars. When you press a button on your key fob, you're waking up its Central Processing Unit (CPU) inside. The CPU sends a data stream to the radio frequency (RF) transmitter. The keyless remote is actually a radio.This data stream contains command and for security, rolling codes. The remote keyless system's receiver in the car captures the RF signal, extracts it and sends the data stream to the CPU. The CPU decodes it and sends commands to the command module. The toggling of LEDs happen according to the command. The functions of a remote keyless entry system are contained on a key fob. Buttons are dedicated to locking or unlocking the doors. Some remote keyless fobs also feature a red panic button which activates the car alarm as a standard feature.Description Keyless remotes contain a short-range radio transmitter, and must be within a certain range, usually 5-20 meters, of the car to work. When a button is pushed, it sends a coded signal by radio waves to a receiver unit in the car, which locks or unlocks the door. This is dual communication system where the vehicle sends the car battery info, window, door and alarm status to the user. Most RKES operate at a frequency of 315 MHz for North America-made cars and at 433.92 MHz for European, Japanese and Asian cars. When you press a button on your key fob, you're waking up its Central Processing Unit (CPU) inside. The CPU sends a data stream to the radio frequency (RF) transmitter. The keyless remote is actually a radio.This data stream contains command and for security, rolling codes. The remote keyless system's receiver in the car captures the RF signal, extracts it and sends the data stream to the CPU. The CPU decodes it and sends commands to the command module. The toggling of LEDs happen according to the command. The functions of a remote keyless entry system are contained on a key fob. Buttons are dedicated to locking or unlocking the doors. Some remote keyless fobs also feature a red panic button which activates the car alarm as a standard feature.

# FEATURES

> It shall display door satus of car for Four User Button Clicks. 

> It shall display alarm satus of car Two User Button Clicks. 


> It shall display window satus of car for one User Button Click.


>  It shall display battery information of car for Three User Button Clicks.


# APPLICATIONS

* Bi-directional communication makes this possible. When the door handle is pulled (or some similar trigger is activated) the base unit located within the vehicle emits a short range, low frequency signal- polling for a nearby key fob transponder.

* if present, the key fob recognizes the signal and responds with a UHF (ultra-high frequency) signal, transmitting a code to be authenticated by the base unit encryption firmware, such as Microchip Technology's Keylock.

* Remote keyless entry systems, now fairly commonplace devices, provide car owners with a degree of convenience, making the task of physically inserting a key unnecessary.



# HIGH LEVEL REQUIREMENTS

| ID | HIGH LEVEL REQUIREMENTS |
| ---- | --------- |
| HLR 1 | It shall print THE STATUS OF THE WINDOW IN THE CAR |
| HLR 2 | It shall print THE STATUS OF ALARM IN THE CAR |
| HLR 3 | It shall print THE STATUS OF DOOR IN CAR |
| HLR 4 | It shall print THE STATUS OF BATTERY IN CAR |

# LOW LEVEL REQUIREMENTS 
| ID | LOW LEVEL REQUIREMENTS |
| ---- | --- |
| LLR_01 | If the user presses the value the blue botton one time, all led should be turn on |
| LLR_02 | System shall print message WINDOW STATUS |
| LLR_03 | if the user presses the blue button two times, all led should turn off |
| LLR_04 | system shall print message ALARM STATUS |
| LLR_05 | If the user presses the blue button three times , all led should rotate in clockwise direction |
| LLR_06 | system shall print message CAR BATTERY STATUS |
| LLR_07 | If the user presses the blue button four times, all led should rotate in anti-clockwise direction |
| LLR_08 | System shall print message DOOR STATUS |

# SWOT ANALYSIS 
## Strengths:

### No need of human interaction with car Status with different features is provided. "Easy usage of features with a user press button.

## Weaknesses:

### Limited Usage Range Less security to our system Interrupts or Timers would be good instead of delay so system works faster.

## Opportunities:

### Wide scope in field of automobiles Cost Efficient Car features are tremendous which in ases car value.

## Threat:

### Less accurate time we should wait until completing one task to complete another task

# 5W's AND 1H


## *WHAT*

* BiCom System for Car is a system that uses a 40-bit rolling code that creats an encryption in between the key and car (transmitter and recever).

## *WHO*

* Any person who is having car that is able to use this type of tecnology.

## *WHERE*

• Inside and Outside car

* At particular range for instance 50 to 60 feet far from the vehicle.

## *WHEN*

* When we need to lock, unlock doors and identify car

* when we need to check the status of the door, alarm, car battery and window.

## *WHY*

* Better Security - Traditional keys are easy to lose, can be copied easily, and are simply outdated when it comes to modern security locks. 
• BiCam System systems require every authorized user to have a unique credential that provides then access to the building.

## *HOW*

* The controller chip in any modern controller uses something called a hopping code or a rolling code to provide security. 
• For example, it describes a system that uses a 48-bit rolling code. Forty bits provide 240 (about 1 trillion) possible codes. 





