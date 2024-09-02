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




