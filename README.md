# Object Detection with Ultrasonic Sensor Using Arduino

## Project Overview
This project involves implementing an object detection system using an ultrasonic sensor and Arduino. The system uses the ultrasonic sensor to emit signals and measure the distance to an object. The Arduino IDE is used to upload the code to an Arduino UNO board, which is connected to a laptop via USB. The distance is displayed on an LCD screen, and object detection is indicated using LEDs and a buzzer. This project addresses the limitations of traditional surveillance systems by providing a radar-like functionality for indoor applications.

## Components Used
- **Arduino UNO**: Microcontroller board
- **Ultrasonic Sensor**: For measuring distance to the object
- **LCD Screen**: For displaying the distance
- **Red and Green LEDs**: For indicating object detection status
- **Buzzer**: For producing sound when an object is detected within 20 cm
- **USB Cable**: For connecting Arduino UNO to a laptop

## Functionality
- **Distance Measurement**: The ultrasonic sensor calculates the distance of an object and displays it on the LCD screen.
- **LED Indicators**: 
  - Green LED: Indicates that the object is within the defined range.
  - Red LED: Indicates that the object is outside the defined range.
- **Buzzer**: Emits sound if the object is detected within a distance of 20 cm.
- **Radar Implementation**: The system simulates a radar function to detect objects in its defined range, suitable for indoor applications.

