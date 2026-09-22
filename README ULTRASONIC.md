## **Ultrasonic-Based Proximity Alert System** 

## **1\. Abstract**

The Ultrasonic Distance Measurement with Buzzer Alert project is designed to detect objects within a specific distance range using an ultrasonic sensor and an Arduino board. In this project, the ultrasonic sensor measures the distance of an object. When the object is detected between 20 cm and 50 cm, the buzzer produces a beep sound. This project helps beginners understand distance measurement, sensor interfacing, and alert systems.

## **2\. Description**

This project uses an Arduino board, an ultrasonic sensor, and a buzzer connected through a breadboard. The ultrasonic sensor measures the distance between the sensor and an object by transmitting ultrasonic sound waves and receiving the reflected waves. The Arduino processes the distance information and activates the buzzer when the object is detected within the range of 20 cm to 50 cm. If the object is outside this range, the buzzer remains OFF.

## **3\. Materials Required**

* Arduino Uno  
* HC-SR04 Ultrasonic Sensor  
* Buzzer  
* Breadboard  
* Jumper wires  
* USB cable  
* Computer or laptop

## **4\. Procedure**

First, place the Arduino board and breadboard on a suitable surface. Connect the ultrasonic sensor to the Arduino using jumper wires. Connect the VCC pin of the sensor to 5V and the GND pin to GND. Connect the Trig and Echo pins to suitable digital pins on the Arduino. Connect the positive terminal of the buzzer to a digital output pin and the negative terminal to GND. Upload the Arduino program using the Arduino IDE. Place an object in front of the ultrasonic sensor and observe the buzzer. The buzzer will produce a beep sound when the object is between 20 cm and 50 cm.

## **5\. Working Principle**

The ultrasonic sensor sends ultrasonic sound waves toward an object and receives the reflected waves. The Arduino calculates the distance based on the time taken for the sound waves to return.

The Arduino continuously checks the measured distance. If the distance is between 20 cm and 50 cm, the Arduino activates the buzzer to produce a beep sound. If the distance is outside this range, the buzzer remains OFF. This process repeats continuously.

![](WORKING(2).jpg)

## **6\. Applications**

This project can be used in parking assistance systems, obstacle detection systems, security alert systems, smart dustbins, distance monitoring systems, and basic automation projects.

## **7\. Advantages**

This project is simple to build and easy to understand. It uses low-cost and easily available components. It provides a contactless method of distance measurement. The buzzer gives an immediate alert when an object enters the specified distance range. The system can be easily modified for different distance limits.

## **8\. Conclusion**

The Ultrasonic Distance Measurement with Buzzer Alert project successfully demonstrates how to measure distance using an ultrasonic sensor and provide an alert using a buzzer. The Arduino processes the sensor data and activates the buzzer when an object is detected between 20 cm and 50 cm. This project provides a basic understanding of sensor interfacing, distance measurement, and automated alert systems.

**RESULT**

![](RESULT(2).jpg)

