# Modular Motor Driver using CAN Bus protocol

### Project Overview 
Making two custom board in sandwich design to use in actuators in rapid developments. So it will be better for Robotic arm with some degree of freedom each device can be attached with one motor and they can be connected in daisy chain pattern
for easy swap

### Key Features
- Easy Swaping capablities
- Tracking Arm movement better
- I/O flexiblity for other sensors
- USB interface for debugging on board

### Components Needed 
- STM32F4 MCU
- BTS7960 Motor driver
- USB Type-C port
- MPU6050 6-axis Accelerometer and Gyroscope
- CAN transciever
- Voltage Regulator
- Other common components like Resistor, Capacitor, inductor, push switches etc

### Project Plan
1. Designing the custom PCB
2. Printing The PCB
3. Gathering the parts neeeded
4. Manufacturing The PCB
5. Firmware Development
6. Testing in real life
7. Note down the issues checking the noise
8. if step  7 gives good results then Final Firmware will be written
9. if step 7 gives bad result then start from step 2 with better hardware design

### Final Validation 
- Connecting the device in a CAN bus network and Giving it a angle value
- Checking the Motor movement also checking the MPU6050 values to validate the movement
- Testing the Power Efficiency



