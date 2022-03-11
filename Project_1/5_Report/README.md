
# RKE (Remote Keyless Entry)

## Abstract:
Remote keyless entry (RKE) is an electronic access system that can be controlled from a distance. RKEs, which are typically used to remotely lock or unlock doors, require the end user to initiate an action that will cause a physical or software key fob to transmit a radio signal to a receiver that controls an electronic lock. Typically, the action is to press a button on a physical fob or mobile app.

## Description:
An RKE system consists of an RF transmitter in the keyfob (or key) that sends a short burst of digital data to a receiver in the vehicle, where it is decoded and made to open or close the vehicle doors or the trunk via receiver-controlled actuators.The carrier is amplitude modulated between two levels: To save power, the lower level is usually near zero, producing complete on-off keying (OOK).RKE-actuated vehicle-immobilization technology minimizes car theft.

![RKE](https://user-images.githubusercontent.com/98833151/157844146-c6697708-a00e-4a83-90f5-9dfb467ebdf5.jpg)</br>

## High Level Requirements:

|ID|Description|
|:---|:---|
|HLR_1|	The system shall consist the locking feature.|
|HLR_2|	The system shall consist the unlocking feature.|
|HLR_3|	The system shall consist the alarm activation & de-activation feature.|
|HLR_4|	The system shall consist the approach light feature.|

## Low Level Requirements:

|ID|Description|HLR ID|
|:---|:---|:---|
|LLR_1|	By pressing blue switch once the device shall lock and all the LED's get turned on at the same time.|HLR_1|
|LLR_2|	By pressing blue switch twice the device shall unlock and all the LED's get turned off at the same time.|HLR_2|
|LLR_3|	By pressing blue switch thrice the alarm shall activate/de-activate and all the LED's get turned on in a clockwise manner.|HLR_3|
|LLR_4|	By pressing blue switch four times all the LED's get turned on in a anti clockwise manner.|HLR_4|


## SWOT Analysis:

<img width="577" alt="SWOT_RKE" src="https://user-images.githubusercontent.com/98833151/157857408-d864f812-0e8e-490e-993c-94b5b7bf699f.png">

## 5W's and 1H:

<img width="544" alt="5W1H_RKE" src="https://user-images.githubusercontent.com/98833151/157872039-a9fc634a-62be-46cb-bcf7-446575b8fe62.png">



# Architecture

## Behavioural High Level Diagram

![](/Project_1/6_ImagesAndVideos/Behavioural%20High%20Level%20Diagram%201.png)

## Behavioural Low Level Diagram

![](/Project_1/6_ImagesAndVideos/Behavioural%20Low%20Level%20Diagram%201.png)

## Structural High Level Diagram

![](/Project_1/6_ImagesAndVideos/Structural%20High%20Level%20Diagram.png)

## Structural Low Level Diagram

![](/Project_1/6_ImagesAndVideos/Structural%20Low%20Level%20Diagram.png)

# Test Plan
* For every feature, define a test case </br>
 :point_right: How to run that feature </br>
 :point_right: Define expected behaviour </br>
 :point_right: Capture the actual result

## Table
* ID, Description of Test case, Input values, Expected Output, Actual Output & Status.</br>

Table : </br>

|Test ID|	Description|	Input values|	Expected Output| Actual Output | Status|
|:------|:-----------|:-------|:-------|:---|:---|
| H_01 |Locking Feature|User presses blue switch once| Door Locked | Door Locked | ✅|
| H_02 |Unlocking Feature|User presses blue switch twice| Door Unlocked | Door Unlocked | ✅|
| H_03 |Alarm activating/de-activating Feature|User presses blue switch thrice| Alarm activated/de-activated | Alarm activated/de-activated | ✅|
| H_04 |Approach Light Feature|User presses blue switch four times| Approach Light turns ON | Approach Light turns ON | ✅|
