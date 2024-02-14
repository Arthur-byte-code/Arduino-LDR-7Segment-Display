# Preview (TinkerCad):
![Running](https://github.com/Arthur-byte-code/Arduino-LDR-7Segment-Display/assets/152222113/9ca38b49-dd6e-4357-bfa2-747496f0948d)

---

# Arduino Project with LDR and 7-Segment Display

This Arduino project utilizes a Light Dependent Resistor (LDR) to measure ambient light intensity and displays numbers from 0 to 9 on a 7-segment LED display. The code automatically maps the values read by the sensor to the desired range and lights up the corresponding LEDs to represent the number.


# What is LDR?
![image](https://github.com/Arthur-byte-code/Arduino-LDR-7Segment-Display/assets/152222113/bac39911-8414-42db-9cca-d26ecf766459)


LDR stands for "Light-Dependent Resistor." It is a type of resistor whose resistance changes with the amount of light falling on it. LDRs are also known as photoresistors or photocells.

When exposed to light, the resistance of an LDR decreases, and when in darkness, its resistance increases. This property makes LDRs useful in various electronic applications where light levels need to be detected or controlled.

LDRs are commonly used in light-sensitive devices such as automatic street lights, camera exposure control, and ambient light sensors in electronic gadgets. They provide a simple and effective way to sense and respond to changes in light levels in different environments.

## Required Components

- Arduino (any compatible model)
- LDR Sensor
- 7-Segment Display with LEDs
- Resistors and jumpers as needed

## Setup

1. Connect the LDR sensor to an analog port on the Arduino (e.g., A5).
2. Connect the 7-segment display to the specified output pins in the code.
3. Upload the code to the Arduino using the IDE.

## Usage

Upon powering the project, the LDR sensor reads the ambient light intensity. The code maps this value to a number between 0 and 9 and lights up the LEDs on the 7-segment display according to the corresponding number.

## Contributions

Contributions are welcome! Feel free to open issues, suggest improvements, or submit pull requests.

# How does the 7 segments display works
![976_203](https://github.com/Arthur-byte-code/Arduino-LDR-7Segment-Display/assets/152222113/bca6a9dc-4d8c-4dc8-b2b2-709c470d9799)


A seven-segment display is a visual representation of numerical digits or other characters using seven individual segments. These segments are arranged in the shape of the number "8" and can be illuminated in various combinations to display different numbers (0-9) or some alphanumeric characters. Each segment is designated a letter (A to G), and by selectively turning on or off these segments, different characters can be displayed. Seven-segment displays are commonly used in electronic devices, such as digital clocks, calculators, and electronic meters, due to their simplicity and efficiency in displaying numerical information.


# What is a protoboard and how it works:
![IMG_20240214_101631](https://github.com/Arthur-byte-code/Arduino-LDR-7Segment-Display/assets/152222113/45a25e54-94af-4ac2-ad6a-7469f8d434d1)

A protoboard, also known as a breadboard or solderless breadboard, is a plastic board with a grid of holes interconnected by conductive traces. It's used to build temporary electronic circuits without the need for soldering. Electronic components can be inserted into the holes of the protoboard and connected to each other using jumpers (conductive wires) inserted into near holes. This allows for quick assembly, disassembly, and modification of circuits for experimentation and prototyping purposes.

# What is Tinkercad:

![images (9)](https://github.com/Arthur-byte-code/Arduino-LDR-7Segment-Display/assets/152222113/a3608713-cce5-4583-9822-6a9632c05d69)

Tinkercad is an online 3D modeling and design platform developed by Autodesk. It provides simple and intuitive tools for creating 3D models, electronic circuits, and even coding projects. Tinkercad is widely used by students, teachers, makers, and technology enthusiasts for rapid prototyping, STEM learning (Science, Technology, Engineering, and Mathematics), and creative project creation.


