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




# Advantages :-

1.Convenience

 - No more, do you have to fumble around or juggle with inserting your key and a handful of groceries or children. With a key fob, the brush of a hand will open doors, the wave of a foot under the rear bumper will lift boot lids, and pushing the ignition button will start your drive.

 

2.Better Security

 - The latest systems require a unique code for unlocking the car, making it harder to steal. The system involves electronic key fob recognition through a specific code authorization.  Only if the car computer finds that particular code, will the vehicle be unlocked or started. Certain car brands use computer-encrypted microchips in their keyless system enhancing the security layers further.

 

3.Automatic Locking

 - Although, locking your car should come as second nature, very often, that niggling thought “have I locked the car?” does make you walk back just to be sure. Now, the keyless system saves you that trouble, because after the car is parked and you have walked a certain distance away, the car automatically locks itself. However, should you leave, forgetting the key fob in the car, the vehicle will stay unlocked. This of course ensures that you are not locked out of your car.



# Disadvantages :-

1.Cost of Replacement

 - Replacing a lost fob costs much more than a traditional key. Moreover, electronic components wear out over time, which then means replacement of either the key or system repair. This is a pretty hefty price to pay just to unlock your car.

 

2.Chances of theft

 - The layers of security in a keyless system are strong, but hackers are constantly developing newer ways to steal cars. Key programming tools are easily available both online and off, and in the wrong hands, one could reprogram a blank fob to your car’s transponder, thus compromising security.





## Block Diagram :- 

![Block Diagram](https://user-images.githubusercontent.com/98821876/157870641-799b400a-7753-4470-a393-aca9e214be83.png)

## Flowchart :- 

![Flowchart_rke](https://user-images.githubusercontent.com/98821876/157870752-8dd12ff4-7237-4f8c-a9f3-80a18003a54a.jpg)




# Testplan

-----------------------------------------------------------------------------------------------
| Test ID  |    Description                   | Expected output | Actual output | Type of test |  Passed or Not|
|-------|--------------------------|------------|-----------|-------|-----|
|  H_01    | Door Lock |     ALL LEDs On at same time    |    ALL Leds on at same time    |   Technical  | ✅ |
|-------|--------------------------|------------|-----------|-------|-----|
|  H_02    | Door Unlock |      ALL Leds off at same time   |   ALL Leds off at same time    |   Technical  | ✅ |
|-------|--------------------------|------------|-----------|-------|-----|
|  H_03    | Alarm ACtivation/Deactivation|ALL Leds On in clockwise manner| ALL Leds On in clockwise manner  |   Technical  | ✅ |
|-------|--------------------------|------------|-----------|-------|-----|
|  H_04    | Car Approach Light |ALL Leds On in anticlockwise manner| ALL Leds On in anticlockwise manner |   Technical  | ✅ |

