# Requirements:-

## Introduction

## ULTRASONIC SOUND SENSOR WITH ATmega328 MICROPROCESSOR

The project as the name suggests is based on Ultrasonic sensors.Ultrasonic sensors work by sending out a sound wave at a frequency above the range of human hearing.
 Our ultrasonic sensors, like many others, use a single transducer to send a pulse and to receive the echo.  The sensor determines the distance to a target by measuring time lapses between the sending and receiving of the ultrasonic pulse.

# Research:-

The requirements for the program to run or for the code to be in effect are basic and  a great solution for the detection of clear objects.

# Features,Hardware and Software:-

![App Screenshot] (C:\Users\patil\OneDrive\Documents\ANKITA PATIL\LLTS)

## a) HARDWARE :-
#### 1] SimulIDE:
      - SimulIDE provides AVR, Arduino and PIC microcontrollers that can be accessed just like other components. 
      - Features like gpsim and simavr allow you to use PIC and AVR microcontrollers, respectively.
#### 2] AVR:
      - An automatic voltage regulator (AVR) is an electronic device that maintains a constant voltage level to electrical equipment on the same load.
      - The AVR regulates voltage variations to deliver constant, reliable power supply.

## b) SOFTWARE :-
#### 1] ATmega328:
      - ATmega328 is commonly used in many projects and autonomous systems where a simple, low-powered, low-cost micro-controller is needed
      - Perhaps the most common implementation of this chip is on the popular Arduino development platform.
#### 2] Sound:
      - A sound sensor is defined as a module that detects sound waves through its intensity and converting it to electrical signals.
#### 3] Display:
      - A display device is an output device for presentation of information in visual or tactile form.
 
# Defining Our System:-

 Ultrasonic sensors work by sending out a sound wave at a frequency above the range of human hearing. The transducer of the sensor acts as a microphone to receive and send the ultrasonic sound. Our ultrasonic sensors, like many others, use a single transducer to send a pulse and to receive the echo

# SWOT ANALYSIS:-

 ## d) Strength:
The distance to an obstacle can be measured with the low cost ultrasonic sensor . The  sensors can measure distances form 2 to 400cm with an accuracy of 3mm. This sensors module includes ultrasonic transmitter, ultrasonic receiver and control circuit.


 ## b) Weakness:
Although we fully believe in the capability of our sensors, we understand that ultrasonics are not suited for every application. 
Focuses of low thickness, similar to froth and fabric, have a tendency to assimilate sound vitality; these materials may be hard to sense at long range.


 ## c) Opportunity:
 This project  Can be used as parking assistance systems in vehicles with high power ultrasonic transmitter.
This Project Can be used as burglar alarm with suitable additional 
software for homes and offices.

 ## d) Threats :
Ultrasonic sensors must view a surface (particularly a hard, level surface) unequivocally (oppositely) to get adequate sound reverberation. Additionally, solid detecting requires a base target surface range, which is indicated for every sensor sort.
If connection is wrong there might be chances of short-circuit.


# 4W's an 1H :-

- # What:
we have made a setup based on a microcontroller in which real time distance is sensed by an ultrasonic sensor and displays measured distance on an LCD display.


- # Where:
It measures accurate distance using a non-contact technology - A technology that involves no physical contact between sensor and object.

-3 When:
In 1959, Satomura created an ultrasonic flowmeter that used doppler technology.

-# Why:
I am Developing this project for easily measure the distance between objects 

- # How:
By using Atmega328 an display  an ultrasonic sensor mainly used to determine the distance of the target object. 


# Detail requirements :-



## High Level Requirements

| ID             | Description                                                           |
| ----------------- | ------------------------------------------------------------------ |
| HLR1 | Used to avoid and detect obstacles with robots like biped robot, obstacle avoider robot, path finding robot etc.  |
| HLR2 |Used to measure the distance within a wide range of 2cm to 400cm   |
| HLR3 |Depth of certain places like wells, pits etc can be measured since the waves can penetrate through water   |

## Low Level Requirements

| ID             | Description                                                           |
| ----------------- | ------------------------------------------------------------------ |
|           |• Power Supply :+5V DC.  |
| LLR_1_HLR1|• Measuring Angle: 30 degree.  |                                                                                                                                                  |
|           |• Trigger Input Pulse width: 10uS TTL pulse.  |
| LLR_1_HRL1|• Depth of certain places like wells, pits etc can be measured since the waves can penetrate through water.  |

# Structural Diagram

![ultra2](https://user-images.githubusercontent.com/94118726/143897055-31eeff08-deec-49d0-bc72-55f07e68ca4e.JPG)

# Block  Diagram


![ultra](https://user-images.githubusercontent.com/94118726/143897237-a742245d-ef65-4779-8586-bbd8e7f5786a.JPG)


# Behavioural of Project :

![Figure-3-Obstacle-detection-and-avoidance-using-ultrasonic-sensor](https://user-images.githubusercontent.com/94224849/144086135-364cb8e4-6db0-4110-93bd-e6924d1fc514.png)



# Bill Of Materials:

## a) SOFTWARE :-

#### 1] SimulIDE:
      - SimulIDE provides AVR, Arduino and PIC microcontrollers that can be accessed just like other components. 
      - Features like gpsim and simavr allow you to use PIC and AVR microcontrollers, respectively.
      - Editor/Debugger is still in its firsts stages of development, with basic functionalities, but it is possible to write, compile and perform basic debugging with
          breakpoints, watch registers and global variables.

      
#### 2] AVR:
      - An automatic voltage regulator (AVR) is an electronic device that maintains a constant voltage level to electrical equipment on the same load.
      - The AVR regulates voltage variations to deliver constant, reliable power supply.
      - Features:
        i] SENSING INPUT. Voltage.
        ii] POWER INPUT (PMG) Voltage.
        iii] REGULATION. +/- 1% (see note 1)


## b) HARDWARE :-


#### 1] ATmega328:
      - ATmega328 is commonly used in many projects and autonomous systems where a simple, low-powered, low-cost micro-controller is needed
      - Perhaps the most common implementation of this chip is on the popular Arduino development platform. 
      - ATMEGA328P is an 8-bit microcontroller based on AVR RISC architecture.
      
#### 2] Sound (HC-SR04 sensor):
      - A sound sensor is defined as a module that detects sound waves through its intensity and converting it to electrical signals.
      - The HC-SR04 sensor works best between 2cm – 400 cm (1" - 13ft) within a 30 degree cone, and is accurate to the nearest 0.3cm.
      - Features:
        i] Input Voltage: 5V
        ii] Current Draw: 20mA (Max)
        iii] Digital Output: 5V
        iv] Digital Output: 0V (Low)
        v] Working Temperature:  -15°C to 70°C
        vi] Sensing Angle: 30° Cone
        vii] Angle of Effect: 15° Cone 
        viii] Ultrasonic Frequency: 40kHz
        ix] Range: 2cm - 400cm

#### 3] Display (16x2 lcd):
      - A display device is an output device for presentation of information in visual or tactile form.
      - Features:
        i] The operating voltage of this LCD is 4.7V-5.3V.
        ii] It includes two rows where each row can produce 16-characters.
        iii] The utilization of current is 1mA with no backlight.
        iv] Every character can be built with a 5×8 pixel box.
        
#### 4] Potentiometer:  
      - the input impedance to be an order of magnitude (10 times) higher than the output (source) impedance.
      - Potential gradient is calculated as K = V/L, where V is the voltage across the potentiometer wire and the L is the length of the wire in the potentiometer.
      - Features:
        i] Resistance :	1K Ohm 
        ii] Potentiometer Type 	Pot Potentiometer 
        ii] Material	Carbon Film and Metal
        iv]Interface	3 Pin
        v]Shaft Length	15mm
        vi]Dimensions 	1 x 1 x 1cms 
        vii]Weight :15 grams

# Circuit Diagram


![Circuit_diagram](https://user-images.githubusercontent.com/94118726/144074359-548a8b4f-10af-4f73-927f-d82e208a613b.jpg)



# Simulation on Simul IDE

![out1](https://user-images.githubusercontent.com/94118726/144175612-ed6c3db1-e5ee-4556-a22e-9f51698de7a3.JPG)


# Test Plan


## Obstacle Detection:
### How: Our implementation for this step requires multiple steps :
#### Step 1: Find a distance value between each pair of sensors. To test the distance
value, we may use the numbers we see for the height and length, as well as the
Pythagorean Theorem.
####Step 2: Check the angle found between each pair of sensors using the distance value
initially found.
####Step 3: Using these values, determine what each angle should approximately be to
detect different types of obstacles.
####Step 4: Detect the obstacles.


## Output: As we had steps for each test, we will again make steps for the expected outputs:
#### Step 1: Compare the outputted (through serial) value for the hypotenuse to the
Pythagorean calculated value. We expect them to be the same.
####  Step 2: Using the same technique as step 1 except calculating the angle, we should
see the same value for this calculation as well.
#### Step 3 : The values and outputs for the “obstacle detected” will be constantly
checked and rechecked to make sure the angles determine the correct obstacle.
#### Step4 : Adding Audio to the Ultrasonic Sensors.

## Testing cases

| Average Speed(m/s)                    | 0.8                           | 1.5    | 2.0    |
| ----------------- | -----------------------|-------------|---------|
| Mean RMS error (cm)* | 19.4  |12.7  |10.2|
|SD** |11.2   |14.3  | 13.4|
|Sensing error (%) | 5.0 | 1.6| 1.0|
|----------------------------------------------------------|


#### RMS error : Root mean square error between actual and sensing distance.
#### SD** : Standard deviation of the RMS errors.

# Communication Protocols
## Wired
#### In this project we use UART communication protocol.
### UART  - TX & RX (2 devices)
* 2 Wire
* Individual clocks used by the both parties
* Standard speed (9600, 115200) - Baud rate
* Parity

## Factors to decide on which communication prototocol to select
### * Frequency :
We need 2oKHz frequency for this project because of this UART is suitable for this model.
### * Data throughput
### * Number of pins available :
There are two pins are avaiable.
#### [1] TX (Pin no 3)
#### [2] RX (Pin no 2).
TX and RX pins we need to display our result .

# Output
```bash
Output:1
```
![out1](https://user-images.githubusercontent.com/94118726/144073307-d3856545-054c-4a28-afbb-3cef3479f6b4.JPG)


```bash
Output:2
```

![out2](https://user-images.githubusercontent.com/94118726/144073341-7fb598c1-40ab-4472-9fda-46da9b9ab729.JPG)

```bash
Output:3
```
![out3](https://user-images.githubusercontent.com/94118726/144073364-fbec5d54-7aa8-49b3-8a69-fa51d0d2b5e5.jpg)



# Conclusion
The objective of the project was to design and implement an ultrasonic distance meter. The device described here can detect the 
target and calculate the distance of the target. The ultrasonic distance meter is a low cost, low a simple device for distance 
measurement. The device calculates the distance with suitable accuracy and resolution. It is a handy system for non-contact 
measurement of distance. The device has its application in many fields. It can be used in car backing system, automation and 
robotics, detecting the depth of the snow, water level of the tank, production line. This device will also have its application in civil 
and mechanical field for precise and small measurements.
For calculating the distance using this device, the target whose distance is to be measured should always be perpendicular 
to the plane of propagation of the ultrasonic waves. Hence the orientation of the target is a limitation of this system. The ultrasonic 
detection range also depends on the size and position of the target. The bigger is the target, stronger will be the reflected signal 
and more accurate will be the distance calculated. Hence the ultrasonic distance meter is an extremely useful device.
