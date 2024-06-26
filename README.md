# RC-Car-Microprocessors-
Operate and control a remote control car using a control board ( STM32F401 )

#Idea:
I want to try to accomplish a high safety level car, like VOLVO, but as an RC Car

# Functional Unit
1. UART:
   A serial communication protocol used for data exchange between a computer and peripheral devices such as microcontrollers and modules. It does not require a synchronous clock signa.
2. PWM:
   A technique used to simulate an analog signal using a digital signal by varying the width of pulses.
3. ADC:
   A module that converts analog signals into digital data.
4. TIMER:
   A technique used to simulate an analog signal using a digital signal by varying the width of pulses.
5. GPIO:
   GPIO pins are versatile pins on a microcontroller or processor that can be configured as either inputs or outputs.
6. INTERRUPTS:
   Interrupts are mechanisms by which a microcontroller can be notified of an event and temporarily halt its current task to execute a special function called an interrupt service routine (ISR).
   
#RC Car function:
1.Horn
2.Ultrasonic sensor
3.Motor
4.Control Speed

#Controller Function:
UIUX
1.Arrow keys
2.Horn
3.Gear display
4.Gear control

#How to implement the functions
1. Using the Buzzer as a horn
2. Using Ultrasonic Sensor to detect the barriers.
   <br>If the obstacle is too close, an interrupt will be generated to perform emergency handling, immediately stopping the vehicle,    and then setting the gear indicator to 0.
   
4.
5.
