
# Bi-Com system

## Abstract
 BiCom system is a communication system between car and its remote(Keyfob). The system gets its name as it performs two way communication (i.e) from remote to car and car to remote.This project is an extension of previous one. Here the transmission of data is from car to keyfob. The functionalities here are Window status, alarm status, car battery information, door status.These four functionalities will be implemented in this project. The previous project has Four functionalities for locking, unlocking, alarm activation and approach light which are transmitted to car. These functionalities are performed in project 1 RKE (Remote Keyless Entry)

## Identifying features
 * Blue switch pressed once-> Print window status - All led on at the same time
 * Blue switch pressed twice -> Print alarm status - All led off at the same time
 * Blue switch pressed thrice -> Print car battery info - All led on in clockwise manner
 * Blue switch pressed four times -> Print Door status - All led on in anti-clockwise manner


## High Level Requirements
ID     | Description
-------| -----------------------------------------
HLR 1  |The system shall display the window status of the car.
HLR 2  |The system shall display the status of alarm.
HLR 3  |The system shall display the Information about battery.
HLR 4  |The system shall display the door status of the car.

## Low Level Requirements
ID     | Description
-------| -----------------------------------------
LLR 1  |By pressing blue switch once the device shall display the status of windows.
LLR 1.1| All the LED's get turned ON at the same time(When pressed once).
LLR 2  |By pressing blue switch twice the device shall display the status of alarm.
LLR 2.2|All the LED's get turned OFF at the same time (When pressed twice).
LLR 3  |By pressing blue switch thrice the device shall display the battery information.
LLR 3.1| All the LED's get turned ON in clockwise direction (When pressed thrice).
LLR 4  |By pressing blue switch four times the device shall display the door status. 
LLR 4.1|All the LED's get turned ON in anti-clockwise direction(When pressed four times)

## SWOT Analysis
<img width="577" alt="SWOT_RKE" src="https://user-images.githubusercontent.com/98833151/157857408-d864f812-0e8e-490e-993c-94b5b7bf699f.png">

## 4W's and 1H
<img width="544" alt="5W1H_RKE" src="https://user-images.githubusercontent.com/98833151/157872039-a9fc634a-62be-46cb-bcf7-446575b8fe62.png">


# Architecture

## Behavioural High Level Diagram

![](/Project_2/6_ImagesAndVideos/Behavioural%20High%20Level%20Diagram%202.png)

## Behavioural Low Level Diagram

![](/Project_2/6_ImagesAndVideos/Behavioural%20Low%20Level%20Diagram%202.png)

## Structural High Level Diagram

![](/Project_2/6_ImagesAndVideos/Structural%20High%20Level%20Diagram%202.png)

## Structural Low Level Diagram

![](/Project_2/6_ImagesAndVideos/Structural%20Low%20Level%20Diagram%202.png)

## TestPlan and Output


- For every feature, define a test case
  - ???? How to run that feature
  - ???? Define expected behaviour
  - ???? Capture the actual result


Test ID   |   Description                        |  Input Values                  |  Expected Output                      |  Actual Output                        | Status |
----------|--------------------------------------|--------------------------------|-------------------------------------- |---------------------------------------|--------|
TC_01     | Display the window status of the car | Blue Switch Pressed Once       | All LED on at the same time           | All LED ON at the same time           | Pass   |
TC_02     | Display the alarm status of the car  | Blue Switch Pressed Twice      | All LED OFF at the same time          | All LED OFF at the same time          | Pass   |
TC_03     | Display the Info about battery       | Blue Switch pressed Thrice     | All LED ON in clockwise direction     | All LED ON in clockwise direction     | Pass   |
TC_04     | Display the door status of the car   | Blue Switch pressed four times | All LED ON in Anticlockwise direction | All LED ON in anticlockwise direction | Pass   |

