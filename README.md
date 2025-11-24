
Exp 6 Simulation of Optical Communication System
## Introduction to OptiPerformer 

## AIM
Download and install OptiPerformer software on your computer and run a sample file.

---

## Overview

Optiwave introduces **OptiPerformer**, a free photonic design automation tool that harnesses the full power of OptiSystem and creates specific dynamic design scenarios for student use.

In this exercise, you will:
- Download and install OptiPerformer on your PC/laptop.
- Use your license to load and run OptiSystem simulations prepared for this course.

The first simulation file (`Introduction_OptiPerformer.osp`) models a basic fiber optic system consisting of:
- A transmitter
- A fiber
- A receiver

The system includes:
- An optical power meter at the receiver input (fiber output)
- A Bit Error Rate (BER) analyzer

---

## Theory

Optiwave introduces OptiPerformer, a free photonic design automation tool which harnesses the full power of OptiSystem and creates specific dynamic design scenarios which can be used by students.

In this exercise, you will download and install OptiPerformer on your PC/laptop. Your license of OptiPerformer will be capable of loading and running OptiSystem simulations prepared for this course.

Once you have installed OptiPerformer, you can copy the first file (named: ‘Introduction_OptiPerformer.osp’) to your PC and run the simulation. The first file is a basic fiber optic system consisting of a transmitter, a fiber and a receiver. The system is “instrumented” with an optical power meter at the input to receiver (or the output of the fiber) and a bit error rate (BER) analyzer.
<img width="729" height="367" alt="image" src="https://github.com/user-attachments/assets/46888a2f-9c55-4616-9d8a-8a44eee776ca" />


## Instructions

1. Download and install OptiPerformer from [optiwave.com](https://optiwave.com).  
2. Copy the `Introduction_OptiPerformer.osp` file to your PC.  
3. Launch OptiPerformer.  
4. Use the **File** menu or **Open File** button to open the fiber optic system file.  
5. Study the layout:
   - **Transmitter** section includes:
     - Binary source (PRBS generator)
     - Electrical pulse generator
     - Laser diode
     - External modulator  
   - **Receiver** section includes:
     - Photodiode
     - Low-pass filter
     - Decision circuit with BER analyzer  
6. Run the simulation using the **Start** button.  
   - Progress will be displayed.
   - Message “Calculation Finished!” appears upon completion.  
7. Double-click the **optical power meter** and **BER analyzer** windows.  
   - Check “Show Eye Diagram” in the BER window.  
   - Optical power meter shows power in watts and dBm.  
   - BER window displays:
     - Eye diagram
     - Max Q Factor
     - Min BER  
8. The simulation runs 5 iterations with fiber length varying from 50 to 150 km.  
   - Use forward/reverse buttons to step through iterations.  
   - Observe changes in received power, BER, Q factor, and eye diagram.

---

## Report

1. Cover sheet (as per attached example).  
2. Tabulation of received power, Q factor, and BER for 5 fiber lengths.  
3. Plot of received power, Q factor, and BER vs. fiber length.  
4. Description of eye diagram changes with increasing fiber length.

---

## Tabulation

**Transmission Analysis Across Fiber Lengths**

 <img width="1280" height="485" alt="image" src="https://github.com/user-attachments/assets/4f4b82da-a63d-4761-a774-56eb1e736c9c" />
            

---

## Graphs

<img width="832" height="301" alt="image" src="https://github.com/user-attachments/assets/b83a74fe-4ebb-4129-b15a-e749cddb4adc" />


## RESULT

The OptiPerformer simulation successfully demonstrated how increasing fiber length causes reduced received power, degraded Q-factor, higher BER, and a progressively closing eye diagram in an optical communication system.
