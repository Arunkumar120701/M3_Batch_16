# Description

• Remote Keyless entry systems allow you to unlock and lock the doors to your vehicle without using a key. It is an electronic access system that can be controlled from a distance. RKEs, which are typically used to remotely lock or unlock doors, require the end user to initiate an action that will cause a physical or software key fob to transmit a radio signal to a receiver that controls an electronic lock.

# Identifying features

• Car should get LOCK when the Button is pressed ONCE

• Car should get UNLOCK when the Button is pressed TWICE

. Car should get ACTIVATION/DEACTIVATION alarm when the Button is pressed THREE times

. Car should get APPROACH LIGHT when the Button is pressed FOUR times

# SWOT ANALYSIS:

## STRENGTHS:

> RKE-actuated vehicle-immobilization technology minimizes car theft.

> There is no human interaction with the car as it is keyless.

> Every function is managed by the buttons on the remote.

## WEAKNESS:

> A remote can stop working because of dead battery & reprogramming of the remote can also be needed.

> Two or more commands cannot be functioned at the same time.

## OPPORTUNITIES:

> The RKE systems has a huge cope in automobiles as the RKE system can be programmed in such a way to handle/protect the automobiles from panics, like noise other than car theft by activating new features like alarms in it.

> Enabling RKE systems in vehicles not only improves security of car access but also facilitates convenience to the users.

> Reasonable cost.

## THREATS:

> RKE system introduces many threats like key fob cloning, jamming, & so on.



# 5W's and 1H

## WHAT

* The term remote keyless system (RKS), also called keyless entry or remote control locking, refers to a lock that uses an electronic remote control as a key which is activated by a handheld device.

## WHY

* When within a few yards of the car pressing a button on the remote can lock or unlock the doors, and may perform other functions.

## WHERE

* It is used in automobiles like cars etc.

## When

* In automobiles when to lock or unlock the doors and others functions.

## WHO

* It will be used by the owner of the automobiles.

## HOW

1. When we press the blue button once all four leds should ON that indicate car door is locked.

2. When we press the blue button twice all four leds should Of that indicate cae door is unlocked.


3. When we press the blue button thrice all four leds should ON in clockwise manner which indicate alarm activate/deactivate.

4. When we press the blue button four times all four leds should ON in anticlockwise manner which indicate approach fight.


## High Level Requirements
|ID|Description|
|------|------|
|HLR_01|RKE key fob shall send signal to the car ECU|
|HLR_02|Car shall get locked on pressing blue switch once|
|HLR_03|Car shall get unlocked on pressing blue switch twice|
|HLR_04|Car alarm shall get activated/deactivated on pressing blue switch thrice|
|HLR_05|Car Approach Light shall get activated on pressing blue switch four times|

## Low Level Requirements
|ID|ID|Description|
|------|------|------|
|HLR_01|LLR_01|Key shall be in detectable range of the car|
||LLR_02|Key Battery must be charged|
|HLR_02|LLR_01|System shall print message "Lock"|       
||LLR_02|All LED lights shall get turned on at the same time|
|HLR_03|LLR_01|System shall print message "Unlock"|              
||LLR_02|All LED lights shall get turned off at the same time|
|HLR_04|LLR_01|System shall print message "Alarm Activated/Deactivated"|              
||LLR_02|All led shall get turned on in clockwise manner|
|HLR_04|LLR_01|System shall print message "Approach Light"|              
||LLR_02|All led shall get turned on in anti-clockwise manner|
