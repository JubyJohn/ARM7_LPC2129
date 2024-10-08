# ARM7_LPC2129

ARM7 is a group of 32-bit RISC processor cores that can be used in microcontrollers. ARM7 is part of the Advanced RISC Machines (ARM) family of microprocessors.

## LPC2129 Specification:

<br> NXP LPC 2129 with 10 MHz Crystal Oscillator (With Boot loader Software)

<br> High Performance 32-bit ARM7TDMI-S™ CPU

<br> 256 KB Programmable Flash Memory provides a minimum of 100,000 erase/write cycles and 20 years of data retention.

<br> 16 KB Data Memory (SRAM)

<br> In-System/In-Application Programming (ISP/IAP) via on-chip boot-loader software. 

<br> Flash programming takes 1 ms per 512 byte line. Single sector or full chip erase takes 400ms.

<br> Embedded ICE-RT interface enables breakpoints and watch points.

<br> Two interconnected CAN interfaces with advanced acceptance filters

<br> Four channel 10-bit A/D converter with conversion time as low as 2.44 us.

<br> Multiple serial interfaces including two UARTs , Fast I2C (400 kbits/s) and two SPIs 

<br> 60MHz maximum CPU clock available from programmable on-chip Phase-Locked Loop 

<br> Vectored Interrupt Controller with configurable priorities

<br> Two 32-bit Timers. 

<br> Four Capture and four Compare channels. 

<br> PWM unit with six output pins.

<br> Watch Dog Timer

<br> Up to forty-six 5V tolerant general purpose I/O pins. 

<br> Up to nine edge or level sensitive external interrupt pins. 

<br> On-chip crystal oscillator with an operating range of 1MHz to 30MHz. 

<br> Two low power modes - Idle and Power-down. 

<br> Processor wake-up from Power-down mode via external interrupt. 

<br> Individual enable/disable of peripheral functions for power optimization. 

<br> CPU operating voltage range of 1.65V to 1.95V and I/O power supply range of 3.0V to 3.6V

<br> PORT0 - 32 PIN  and  PORT1 - 16 PIN

### IODIR:GPIO Direction Control Register - 32 bit register
<br> 0-input
<br> 1-output

### IOSET:Port Output Set Register - 32 bit register
<br> 0 - no effect
<br> 1 - high

### IOPIN: GPIO Port Pin Value Register - 32 bit register
<br> port pins perform only digital functions

### IOCLR:Port Output Clear Register - 32 bit register
<br> 0 - no effect
<br> 1 - low

### PINSEL: Pin Function Select Register - 32 bit register
<br> PINSEL0 – Controls functions of Port0.0 – Port0.15
<br> PINSEL1 – Controls functions of Port0.16-Port0.31
<br> PINSEL2 – Controls functions of Port1.16-Port1.31


## BINARY TO HEXADECIMAL CONVERSION

![b2h](https://github.com/user-attachments/assets/c38418aa-aa48-46aa-bb84-6c4d9ac992a4)

<br> 1 hex value = 4bit binary
<br> 0x00000000 = 8*4 => 32 bit binary


<br> 0x00010000
<br> &ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;<--
<br> 0-3  => 1st value
<br> 4-7  => 2nd value
<br> 8-11  => 3rd value
<br> 12-15  => 4th value 
<br> 16-19  => 5th value
<br> 20-23  => 6th value
<br> 24-27  => 7th value
<br> 28-31  => 8th value

<br> eg:0x00008000 =15 pin
<br>
![Screenshot 2024-09-05 112047](https://github.com/user-attachments/assets/2e012987-4a5d-4aea-95b6-f4e586099a23)


## 7 SEGMENT DESIGN

![7_segment_display_labeled svg (1)](https://github.com/user-attachments/assets/acbec58b-5c58-47a5-9be9-2312c812bf90)
![Screenshot 2024-09-07 100800](https://github.com/user-attachments/assets/5b97bc19-22b1-45ab-8ae3-db3ea54468ea)

## LIQUID CRYSTAL DISPLAY 16X2 (LCD)
![16x2-lcd](https://github.com/user-attachments/assets/a7c45bc9-fb74-4990-ba5f-d645e6ccc585)


<br> - VSS (Ground/Source Pin):
<br> &ensp;&ensp;&ensp;&ensp;This is a GND pin of display, used to connect the GND terminal of the microcontroller unit or power source.
<br> - VDD (VCC/Source Pin): 
<br> &ensp;&ensp;&ensp;&ensp;This is the voltage supply pin of the display, used to connect the supply pin of the power source.
<br> - VEE (V0/VEE/Control Pin): 
<br> &ensp;&ensp;&ensp;&ensp;This pin regulates the difference of the display, used to connect a changeable POT that can supply 0 to 5V.
<br> - RS (Register Select/Control Pin): 
<br> &ensp;&ensp;&ensp;&ensp;This pin toggles among command or data register, used to connect a microcontroller unit pin and obtains either 0 or 1(0 = data mode, and 1 = command mode).
<br> - R/W (Read/Write/Control Pin): 
<br> &ensp;&ensp;&ensp;&ensp;This pin toggles the display among the read or writes operation, and it is connected to a microcontroller unit pin to get either 0 or 1 (0 = Write Operation, and 1 = Read Operation).
<br> - E (Enable/Control Pin): 
<br> &ensp;&ensp;&ensp;&ensp;This pin should be held high to execute Read/Write process, and it is connected to the microcontroller unit & constantly held high.
<br> - Pins 7-14 (Data Pins): 
<br> &ensp;&ensp;&ensp;&ensp;These pins are used to send data to the display. These pins are connected in two-wire modes like 4-wire mode and 8-wire mode. In 4-wire mode, only four pins are connected to the microcontroller unit like 0 to 3, whereas in 8-wire mode, 8-pins are connected to microcontroller unit like 0 to 7.

Reference: https://www.elprocus.com/lcd-16x2-pin-configuration-and-its-working/





  



