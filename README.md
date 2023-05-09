# IR Remote Light

Arduino code to turn lights on/off using an Infrared (IR) remote control, plus sleep operation for low power consumption.

&nbsp;

This project use the following electronic components:
- 1 x Arduino Nano v3.0
- 1 x Infrared sensor
- 1 x Relay 5v
- 3 x LED 5mm
- 2 x 4.7k ohm resistors
- 1 x 470k ohm resistor
- 1 x ON/OFF button
- 1 x Push-button

The circuit:
- When pressing the toy surface it moves the empty pen tubes, making some presure on the piezo-electric.
- The piezo-electric generates some voltage on presure, activating the electronic circuit.
- The NE555 IC handles the 12 seconds enabled delay.

Notes:
- IR Codes changes from remote control to remote control.
- You can look after your's remote control codes conecting the IR sensor to the Arduino board, and within the Arduino IDE using the serial monitor.
- The provided source code can do this for your, just make sure to change the DEBUG macro value to 'true'.

&nbsp;

### Screenshots

| Diagram - Schematics 01                         | Diagram - Schematics 02                         |
|-------------------------------------------------|-------------------------------------------------|
| ![](Resources/01-photo-coming-soon.jpg)         | ![](Resources/02-photo-coming-soon.jpg)         |

| Diagram - PCB Render                            | Diagram - PCB Render                            |
|-------------------------------------------------|-------------------------------------------------|
| ![](Resources/03-photo-coming-soon.jpg)         | ![](Resources/04-photo-coming-soon.jpg)         |

| Prototype                                       | PCB Manufacturing                               |
|-------------------------------------------------|-------------------------------------------------|
| ![](Resources/06-photo-coming-soon.jpg)         | ![](Resources/15-photo-coming-soon.jpg)         |

| PCB Assembly                                    | Project Assembly                                |
|-------------------------------------------------|-------------------------------------------------|
| ![](Resources/19-photo-coming-soon.jpg)           | ![](Resources/24-photo-coming-soon.jpg)       |

| Project Final                                   | Project Final (YouTube video)                   |
|-------------------------------------------------|-------------------------------------------------|
| ![](Resources/25-photo-coming-soon.jpg)          | ![](Resources/26-photo-coming-soon.jpg)        |

See 'Rescources' sub-folder for more pictures of the proyect.

&nbsp;

### Version History

v1.0 (2023.05.07) - Initial release.  
v1.1 (2023.05.08) - Adding use of sleep mode + interrupts to reduce power consumption.  

&nbsp;

This source code is licensed under GPL v3.0  
Please send me your feedback about this app: andres.garcia.alves@gmail.com