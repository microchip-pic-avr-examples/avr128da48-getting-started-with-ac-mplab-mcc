[![MCHP](images/microchip.png)](https://www.microchip.com)

# Getting Started with Analog Comparator (AC) Examples (MPLAB® X)

This repository contains examples of MCC generated source code for the Analog Comparator (AC), as described in [TB3211-Getting Started with Analog Comparator (AC)](http://ww1.microchip.com/downloads/en/Appnotes/TB3211-Getting-Started-with-AC-90003211A.pdf) document from Microchip. The repository contains three MPLAB® X projects inside:

* [<strong>Analog Signal Pulse Duration Measurement:</strong>](Analog_Signal_Pulse_Duration_Measurement) In this use case, the AC peripheral will be used to measure the input signal period and pulse duration (for more details, see [<strong>Analog Signal Pulse Duration Measurement</strong>](Analog_Signal_Pulse_Duration_Measurement)).
* [<strong>Level Crossing Detector:</strong>](Level_Crossing_Detector) This example shows a basic initialization and set up for the AC peripheral. The application monitors an analog input signal, compares it to a fixed voltage and notifies the user via interrupt and an output pin every time the input signal crosses the fixed voltage level (for more details, see [<strong>Level Crossing Detector</strong>](Level_Crossing_Detector)).
* [<strong>Preventing False Spike Detection:</strong>](Preventing_False_Spike_Detection) This example demonstrates the hysteresis features of the AC module that helps in avoiding frequent toggling of the AC when the positive input oscillates very close to the negative input level. This application is similar to the voltage level detector application. Additionally, it has the Hysteresis mode enabled (for more details, see [<strong>Preventing False Spike Detection</strong>](Preventing_False_Spike_Detection)).

## Related Documentation
More details and code examples on the AVR128DA48 can be found at the following links:
- [TB3211 - Getting Started with Analog Comparator (AC)](http://ww1.microchip.com/downloads/en/Appnotes/TB3211-Getting-Started-with-AC-90003211A.pdf)
- [AVR128DA48 Product Page](https://www.microchip.com/wwwproducts/en/AVR128DA48)
- [AVR128DA48 Code Examples on GitHub](https://github.com/microchip-pic-avr-examples?q=avr128da48)
- [AVR128DA48 Project Examples in START](https://start.atmel.com/#examples/AVR128DA48CuriosityNano)


## Software Used
- MPLAB® X IDE 5.40 or newer [(microchip.com/mplab/mplab-x-ide)](http://www.microchip.com/mplab/mplab-x-ide)
- MPLAB® XC8 2.30 or a newer compiler [(microchip.com/mplab/compilers)](http://www.microchip.com/mplab/compilers)
- MPLAB® Code Configurator (MCC) 4.0.1 or newer [(microchip.com/mplab/mplab-code-configurator)](https://www.microchip.com/mplab/mplab-code-configurator)
- MPLAB® Code Configurator (MCC) Device Libraries 8-bit AVR MCUs 2.5.0 or newer [(microchip.com/mplab/mplab-code-configurator)](https://www.microchip.com/mplab/mplab-code-configurator)
- AVR-Dx 1.6.88 or newer Device Pack


## Hardware Used
- AVR128DA48 Curiosity Nano [(DM164151)](https://www.microchip.com/Developmenttools/ProductDetails/DM164151)
