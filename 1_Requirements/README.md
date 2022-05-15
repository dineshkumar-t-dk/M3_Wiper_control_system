# WIPER_CONTROL_SYSTEM
## INTRODUCTION
A wiper speed control system regulates the operational speed of a wiper based on frequencies. To generate a control signal, the pulse signal is digitally processed. The control signal is received by a wiper driving circuit, which then adjusts the operational speed or time accordingly.  
## SOFTWARE REQUIREMENTS
 STM32 CUBE IDE
 # Requirements
## High Level Requirements
ID | Description | Status
-- | -- | --
HR_01 | It will LOCK the vehicle. | Implemented
HR_02 | It will unlock the vehicle. | Implemented
HR_03 | It will turn on the wiper system. | Implemented
HR_04 | It will turn off the wiper system. | Implemented
## Low Level Requirements
ID | Description | Status
-- | -- | --
LR_01 | ON LED RED - if the button is pushed ONCE. | Implemented
LR_02 | OFF RED LED - if the button is pushed TWICE | Implemented
LR_03 | ON BLUE,GREEN,ORANGE LEDS - if the button is pushed THREE TIMES | Implemented
LR_04 | ON ORANGE, GREEN, and BLUE LEDS - if the button is pushed FOUR times | Implemented
## COMPONENTS
  STM32F4O7VG MICROCONTROLLER BOARD
### DESCRIPTION
## STM32F407VG
 The STM32F407 Kit takes advantage of the high-performance STM32F407 microcontroller’s capabilities to make it simple for users to create audio-based applications. It comes with an ST-LINK embedded debug tool, an ST-MEMS digital accelerometer, a digital microphone, an audio DAC with an integrated class D speaker driver, LEDs, pushbuttons, and a USB OTG micro-AB connector. Ethernet connectivity, an LCD display, and other features have been added to the STM32F4 DISCOVERY kit. The STM32F405xx and STM32F407xx families are built around the high-performance Arm® Cortex®-M4 32-bit RISC core, which runs at up to 168 MHz.
 ## FEATURES OF STM32F407VG MICROCONTROLLER
  * In a LQFP100 package, the STM32F407VGT6 microcontroller has a 32-bit ARM Cortex-M4 with FPU core, 1-Mbyte Flash memory, and 192-Kbyte RAM.
  * On-board ST-LINK/V2 or ST-LINK/V2-A on STM32F4 DISCOVERY (old reference) or STM32F407G-DISC1 (new order code)
  * USB ST-LINK with three separate interfaces and re-enumeration capability.
  * Virtual Com port Debug port (with new order code only)
  * Large-scale storage (with new order code only)
  * Board power is supplied through USB or an external 5 V supply source.
  * 3 V and 5 V external application power supply
 ## USES
  * This Microcontroller is used in various applications such as printing and scanning machines, heat ventilation, air conditioning and security systems. 
  * This Microcontroller can be found in a variety of household products.
 ## WORKING PRINCIPLE
Consider the automobile as microcontroller. If the button is hit, the first LED (red) will turn on. Pressing the button again the wiper will start and the second LED (blue) will turn on for the desired rate. If the button is pressed again, the third LED (green) will turn on and the wiper's speed will be increased in comparison to the previous one. The fourth press will turn on the fourth LED (orange) and the wiper speed will be increased in accordance with the previous one. The microcontroller (vehicle) is turned off after the fifth click.
## FOLDER STRUCTURE
Folder | Description
-- | --
0_Abstract | Explaination of the project
1_Requirements | Documents detailing requirements and research
2_Design	| Behavioural and Structural UML Diagrams along with Block diagrams and flow charts
3_Implemenatation	 | All code and documentation
4_TestCases	| Documents with test plans and procedures and Output
5_Report	| Overall report of the project
6_Output	| Code Execution Images and Video
 ### 4 W'S & 1 H
 ## WHAT 
  Windscreen wipers are necessary for maintaining sufficient view for the driver, especially in modern high-speed cars.
 ## WHY 
   To keep the windscreen clean enough to give adequate view at all times.
 ## WHEN 
  The windshield wipers remove rain and snow from the windshield, while the headlights improve visibility at night.
 ## WHO 
  Mark Anderson invented on 1903
  ## HOW 
  The control system includes a rain sensor which detects the rain condition. An analog signal having an amplitude depending upon the detected rain conditions has been identified.A converter is used to convert analog signal into digital pulse signal and is transferred to a digital circuit system.The pulse signal is digitally processed where a control signal is produced.The control signal is applied to a wiper driver circuit to adjust the operational speed or timing in accordance with the control signal.
  ## SWOT ANALYSIS
# STRENGTH
* Low cost 
* High reputation
* Clarity of vision 
# WEAKNESSES
* Replacement cost are higher.
* Chances of wiper motor failure.
# OPPORTUNITIES
* High possibilities for safety.
# THREATS
* Wiper mix might be an issue in rain.
* Replaced  by advanced technology.

