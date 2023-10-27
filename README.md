# HW5-PWM-And-Logic-Analyzer

Group : 9  
Member : B09901043 陳昱樺 B09901134 林容丞

Function
---
Here are what this project does:
1. Implement telecommunications with PWM programming. 
2. Generate two signals: clock and the message to be sent. 
3. Show clock signal and message in the Logic Analyzer software.
4. The period is 100ms, and we set 10ms as an unit. The duty cycle represents the number to be sent. For example, a pulse with pulsewidth 70ms corresponds to the number 7.
5. The real message is after a full duty cycle and an empty cycle.
6. The default message is [1, 2, 3, 4, 5].

Prerequisites
---
There are two things a user should prepare to run this project:
* STM32 development board
* Zeroplus Logic Cube Analyzer and corresponding software (can be found at http://www.zeroplus.com.tw/logic-analyzer_en/technical_support_search.php?model=LAP-C%2816128%29&class1=1)

Usage
---
Here are some steps to run this project properly:
1. Import the project into Mbed Studio. 
2. Connect PA15 and PA2 on STM32 board to the logic analyzer. 
3. Run main.cpp in Mbed Studio. 
4. Run the logic cube software. 
5. Clock signal and message sent are shown in the logic analyzer software. 

License
---
None.

Acknowledgements
---
Here are some resources we refer to to finish this project:
* https://en.wikipedia.org/wiki/Pulse-width_modulation#Telecommunications
* Course slides: STM32 timer and PWM-.pdf and Lab_STM32_PWM_LA.pdf
