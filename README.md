# **A**nti-**B**oilerplate **C**ode


ABC is a project that was devised in an attempt to reduce the ammount of boilerplate code that has to be written when creating applications written in C/C++. We aren't striving to provide the most efficient code or the code with the smallest memory footprint, but rather are attempting to create flexible and easy to use modules that give developers a jump off point so that they may more efficiently prototype ideas and concepts. 

There are a couple goals that we strive to meet with the code provided through this project:
 * All source is agnostic of the architecture for which it may be used on. You should have no issue using these modules in a project being developed for an 8-bit micro while also having no issues using these with a 64-bit multi-core desktop computer. 
 * Each module should contain automated testing to ensure to a reasonable degree that the module can be reliably used.
 * Each module should contain no dependencies aside from the standard libraries and other modules within this project. This is done to improve long term stability of the project.  
 * Each module should be documented using Doxygen and follow the precedent of documentation style. The more standardized this is the easier the code should be to read. 

## Modules
### Currently Implmeneted
* **None....** Still getting the ball rolling

### Planned
* **Signal Processing**
  * FIR filter
  * IIR filter
  * Generation of fundamental waveforms (square, sine, ramp, triangle)
* **Buffer/Queue**
  * FIFO
  * LIFO
* **Control**
  * PID
  * MFA
  * Fuzzy
* **Communication**
  * Serial Command Interface (Human - Computer)
  * Serial Data Interface (Computer - Computer) 
* **Safety**
  * Mutex
  * Error types
* **Math**
  * Vector math (dot, cross, etc.)
  * Matrix math
  * Fast trig (LUT)
* **Interface**
  * Button input 
  * Encoder input
  * Potentiometer input
  * LED control (RGB, 'smart' LED, single color, multiplexed, etc.)
* **System**
  * Basic bootloader (FW update ability)
  * Time
* **Security**
  * Checksum confirmation/generation
  * Encryption algs
 
---

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
