# Intel-Equipathon

## Project Title - AI enabled Prosthetic Arm ##

## Overview ##

The goal of this project is to build a prototype of a prosthetic arm that can be controlled using advanced algorithms, with a focus on showcasing the use of Intel's oneAPI toolkit. We have developed a mechanical arm model by 3D printing it that will allow the user to perform the desired action using the signals provied by the brain.

The prosthetic arm will be equipped with sensors that can detect EEG signals from the brain. The transmitted signals will be processed using signal processing techniques to generate commands that will be processed by the raspberry pi and the designated movement will take place like grasping, pointing, releasing.

We are integrating the prosthetic arm and the Ai in such a way that the Ai can detect and remove the undesired or irregular signals produced by the brain during situations of seziures, panic attacks or any health issues related to the brain and the nervous system so that there is no malfunctioning in the working of the arm. 

We will be taking signals from the EEG device ( Neurosky Brainwave headset ) and colleting it in a text format which will be then transmitted to the raspberry pi, where the data is processed and the signals are transmitted to the servo motors in the form of pulses through the PWM pins.

The microcontroller software will be optimized for performance using Intel's oneAPI toolkit, and the arm movements will be programmed using servo motors and other components. For a variety of hardware platforms, developers can write high-performance programs using the toolkit's libraries, compilers, and other tools.

The code used to develop the software interface and to control the prosthetic arm is shared above in the repository.
 
