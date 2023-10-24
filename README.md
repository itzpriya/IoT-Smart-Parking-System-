# IoT-Smart-Parking-System-
## Project Overview:
The Smart Parking System is an Arduino-based solution aimed at providing an efficient way of handling parking spaces. Utilizing sensors and indicators, it keeps track of available parking slots, guiding drivers to empty spots, and manages entry through an automatic gate.

## Features:
Dynamic Slot Monitoring: Ultrasonic sensors are used to determine if a parking slot is occupied or available.
Vehicle Detection: An IR sensor placed at the entrance detects the presence of incoming vehicles.
Automatic Gate Control: A servo motor operates the entrance gate, granting access only when a slot is available.
Visual Indicators: LEDs provide a visual status of each parking slot. A green LED indicates the slot is free, while a red LED signifies it's occupied.
Real-time Display: An LCD screen at the entrance dynamically displays the number of available slots and their respective numbers.

## Components Used:
Arduino UNO
Ultrasonic Sensors (for parking slots)
IR Sensor (for vehicle detection at the entrance)
LCD Display (for displaying slot status)
Servo Motor (for controlling the gate)
Red and Green LEDs (for slot indicators)

## Implementation:
The system continuously monitors distances from the ultrasonic sensors to determine if a car is parked in a slot. This data is then reflected on the LCD display. When a vehicle approaches the gate, the IR sensor detects it. If a parking slot is available, the servo motor activates to open the entrance gate, allowing the vehicle to enter. As the vehicle occupies a slot, the corresponding LED changes from green (available) to red (occupied), giving a quick visual indication of slot availability.

## Future Scope:
With IoT integration, this system could be connected to a mobile application, allowing drivers to check for available slots remotely. Also, with the addition of more sensors and cameras, license plate recognition and other advanced features can be integrated to further enhance the parking experience.
