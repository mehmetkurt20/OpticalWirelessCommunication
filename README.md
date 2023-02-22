# Optical Wireless Communication
This repository contains documents and circuit diagrams about the final project of the EE313 Analog Electronics Laboratory course. You can find documents and LTSpice Simulations collected throughout the process. 

Optical wireless communication is a critical development in the invention of some crucial technologies which are widespread all around the world, such as the internet, mobile phones, etc. In this project, we will be setting up a complete optical wireless communication system, including the sound input transmitter, receiver, and output blocks. Our main aim in constructing this system is to investigate the theoretical background of electrical modulation and transmission of light, which forms the basis of fiber optics and internet technology. The construction process of this electrical system includes also the filters, amplifications, and automatic gain control systems required for the conservation of the waveform for the transmission.The explanations of the constructed sub-blocks are given below.

## Automatic Gain Controller

This unit is used to eliminate the effect of varying distance between the microphone and the input audio source. By using this sub-system, we keep the output amplitude at a proper level over a wide range of input voltage levels. To achieve this, we constructed a circuit that is called Automatic Gain Controller, which is a closed circuit that uses a feedback loop to balance the output against varying input amplitude levels. This circuitry uses a shunt-shunt feedback loop, meaning that it mixes voltage and samples current.

![AGC](https://user-images.githubusercontent.com/64316648/216618023-2f6ca1f9-f4f1-413c-85b9-234ee46c0f03.jpg)

## Transmitter / LED Modulation Circuitry

For the transmission, we use an infrared LED to convert electrical signal into a light beam, as mentioned in the theoretical background section. To make the LED emit a light that carries the input voltage signal, we needed to provide a bias current which makes the LED operate in its linear region.

![image](https://user-images.githubusercontent.com/64316648/216618421-16a7a484-2009-4b0c-9a79-13ac41d26e98.png)

## Receiver Circuitry

## Power Amplifier Circuitry
![Class AB Power Amplifier](https://user-images.githubusercontent.com/64316648/216618899-ff46f8d4-091c-43e4-8da9-eaf15d730955.jpg)

## Peak Detector [AC-->DC] Circuitry
![Peak Detector Circuitry](https://user-images.githubusercontent.com/64316648/216618961-8d2e6e6f-c153-48ac-b640-9641af849b68.jpg)
