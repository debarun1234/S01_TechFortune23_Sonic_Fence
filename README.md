# Sonic Fence - Using Ultrasound to Keep Wildlife Away from Railway Tracks

## About
The Sonic Fence is an effective solution to the serious issue of train-animal collisions. It utilizes ultrasound sensors to detect trains and scare off animals from railway tracks. The Sonic Fence can reduce the number of accidents caused by these collisions. This innovative and socially responsible solution can help protect wildlife and prevent future accidents. 

## Problem Statement
Train-animal collisions are a serious and often fatal problem that pose a risk to both animals and humans. Conventional approaches like fencing and wildlife crossings are often costly and may not be effective in preventing such collisions. The Sonic Fence project aims to address this issue by using ultrasound sensors to detect trains and scare off animals from railway tracks, thereby reducing the number of accidents caused by train-animal collisions.

## Solution
The Sonic Fence is a social innovation that uses ultrasound sensors to detect trains and scare off animals from railway tracks. It employs an Arduino Nano, two HC-SR04 ultrasound sensors, a Piezo buzzer, and a SIM800C module to detect the presence of trains and animals. When a train is detected, the Piezo buzzer emits a high-pitched sound that scares away animals from the tracks. Once the train has passed, the sound stops. The second ultrasound sensor is used to detect the presence of animals on the tracks. If an animal is detected, the Piezo buzzer is triggered to scare off the animal and keep the tracks clear. Additionally, the inclusion of the SIM800C module sends text messages to local wildlife conservation organizations whenever a train is detected or an animal is present on the tracks. This will alert professionals to the presence of wildlife in the area and help prevent future accidents. By making use of these technologies, the Sonic Fence project stands out as an innovative and socially responsible solution to a pressing problem.

## Hardware and Software
* Hardware
  * Arduino Nano
  * HC-SR04 Ultrasound (x2)
  * GSM SIM 800L Module
  * Buzzer
  * LED
  * Mini Breadboard
  * Wires
* Software
  * Arduino IDE

## Working Procedure
* The Sonic Fence project uses two HC-SR04 ultrasound sensors to detect trains and animals.
* When a train is detected, the Arduino triggers the Piezo buzzer to emit a high-pitched sound, which helps to scare away animals from the tracks.
* Once the train has passed, the sound stops.
* The second ultrasound sensor is used to detect the presence of animals on the tracks.
* In case of detection, the Piezo buzzer is triggered to scare off the animal and keep the tracks clear.

## Libraries Used
SoftwareSerial.h file used to enable _GSM Module_ to function, every other commponents will work from the predefined libraries given to **Arduino IDE**.

## Team Prospects
* Leader and Software - Debarun Ghosh
* Hardware Engineer - Ayan Kumar Mal
* Technical Documentation - Pooja Mallik

## Event Prospects
* HackToFuture - Hackathon
* St. Joseph Engineering College, Mangalore
* Domain - Social Innovations

**ANY QUERIES PLEASE REACH US TO debarun.ghosh.2000@gmail.com**
