# M2_Distance_Measurement

# REQUIREMENTS

## Introduction:-

## ULTRASONIC SOUND SENSOR WITH ATmega328 MICROPROCESSOR

The project as the name suggests is based on Ultrasonic sensors.Ultrasonic sensors work by sending out a sound wave at a frequency above the range of human hearing.
 Our ultrasonic sensors, like many others, use a single transducer to send a pulse and to receive the echo.  The sensor determines the distance to a target by measuring time lapses between the sending and receiving of the ultrasonic pulse.

# Research:-

The requirements for the program to run or for the code to be in effect are basic and  a great solution for the detection of clear objects.

# Features :-

![App Screenshot] (C:\Users\patil\OneDrive\Documents\ANKITA PATIL\LLTS)

Sound velocity = 343.00 m/s = 34300 cm/s

Distance of Object (in cm) = (Sound velocity * TIMER Value) / 2

                    = (34300 * TIMER Value) / 2

                    = 17150  * Timer Value
we have selected internal 8 MHz oscillator frequency for ATmega32, with No-presale for timer frequency. Then time to execute 1 instruction is 0.125 us So, timer gets incremented after 0.125 us time elapse.

             = 17150 x (TIMER value) x 0.125 x 10^-6 cm

             = 0.125 x (TIMER value)/58.30 cm

             = (TIMER value) / 466.47 cm
 
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

