# Optical Wireless Communication
This repository contains documents and circuit diagrams about the final project of the EE313 Analog Electronics Laboratory course. You can find documents and LTSpice Simulations collected throughout the process. 

<div align="center">
    <img width = 600 src="https://github.com/mehmetkurt20/OpticalWirelessCommunication/blob/master/schematics/diagram.png">
</div>

Optical wireless communication is a critical development in the invention of some crucial technologies which are widespread all around the world, such as the internet, mobile phones, etc. In this project, we will be setting up a complete optical wireless communication system, including the sound input transmitter, receiver, and output blocks. Our main aim in constructing this system is to investigate the theoretical background of electrical modulation and transmission of light, which forms the basis of fiber optics and internet technology. The construction process of this electrical system includes also the filters, amplifications, and automatic gain control systems required for the conservation of the waveform for the transmission.The explanations of the constructed sub-blocks are given below.

## Automatic Gain Controller

This unit is used to eliminate the effect of varying distance between the microphone and the input audio source. By using this sub-system, we keep the output amplitude at a proper level over a wide range of input voltage levels. To achieve this, we constructed a circuit that is called Automatic Gain Controller, which is a closed circuit that uses a feedback loop to balance the output against varying input amplitude levels. This circuitry uses a shunt-shunt feedback loop, meaning that it mixes voltage and samples current.


<div align="center">
    <img width = 600 src="https://github.com/mehmetkurt20/OpticalWirelessCommunication/blob/master/schematics/agc.png">
</div>


## Transmitter / LED Modulation Circuitry

For the transmission, we use an infrared LED to convert electrical signal into a light beam, as mentioned in the theoretical background section. To make the LED emit a light that carries the input voltage signal, we needed to provide a bias current which makes the LED operate in its linear region.


<div align="center">
    <img width = 300 src="https://github.com/mehmetkurt20/OpticalWirelessCommunication/blob/master/schematics/ledmodulation.png">
</div>


## Receiver Circuitry

To drive the phototransistor, we connected a resistor to the emitter pin and convert the current output coming from the transistor, named collector current into a voltage waveform.


<div align="center">
    <img width = 300 src="https://github.com/mehmetkurt20/OpticalWirelessCommunication/blob/master/schematics/phototransistor.png">
</div>

## Power Amplifier Circuitry

The main function of the power amplifier, which is also known as a “large signal amplifier” is to deliver power [3]. Therefore, we used a power amplifier at the output, which provides high switching currents, which we will need because the speaker we used is 16Ω, since power is resistance multiplied by the square of the current.

<div align="center">
    <img width = 300 src="https://github.com/mehmetkurt20/OpticalWirelessCommunication/blob/master/schematics/poweramp.png">
</div>

## Peak Detector [AC-->DC] Circuitry

To be able to compare the DC reference signal with the output voltage, we first needed the convert the AC waveform into a DC form. To achieve this, we used a peak detector circuit, which detects the peak value of a signal thanks to a capacitor charging mechanism.

<div align="center">
    <img width = 400 src="https://github.com/mehmetkurt20/OpticalWirelessCommunication/blob/master/schematics/peakdetector.png">
</div>

