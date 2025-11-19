
# Exp 4 Experimental verification of frequency response of Analog fiber optic link
# Fiber Optic Link Analysis (660nm)

## AIM
To analyze the relationship between input and received signal of a 660nm fiber optic cable using analog and digital link.

---

## EQUIPMENTS REQUIRED
- Fiber optic trainer kit ST 2502  
- Power supply  
- Patch cords  
- CRO (Cathode Ray Oscilloscope)  
- 660 nm fiber cable  

---

## THEORY

Fiber optic links can be used for transmission of digital as well as analog signals. A fiber optic link typically consists of three main elements:
- **Transmitter**: Converts the electrical input signal into optical (light) energy.
- **Optical Fiber**: Serves as the transmission medium for the light signal.
- **Receiver**: Converts the received light back into an electrical signal, preserving the original signal pattern.

---

## PROCEDURE

1. Connect the power supply to the board.  
2. Ensure that all switched faults are set to ‘Off’.  
3. Make the following connections (as shown in Figure 19):  
   a. Connect the 1KHz sine wave output to emitter 1's input.  
   b. Connect the fiber optic cable between emitter output and detector input.  
   c. Connect detector 1's output to AC amplifier 1 input.  
4. On the board, switch emitter 1's driver to analog mode.  
5. Switch on the power.  
6. Observe the input to emitter 1 (TP5) and the output from AC amplifier 1 (TP28). Verify that both signals are identical.  
7. Vary the frequency between 10 Hz to 1 MHz and observe the output voltage for a constant input voltage of 5V.  
8. Calculate the bandwidth by determining the gain in decibels (dB).  

---
## BLOCK DIAGRAM
<img width="665" height="389" alt="image" src="https://github.com/user-attachments/assets/06278da9-a531-48d0-97eb-280081263fdd" />

## TABULATION  
![WhatsApp Image 2025-11-18 at 21 55 28_7b60ee9f](https://github.com/user-attachments/assets/9677f735-1a87-400e-afa6-b62f45930ef6)

## MODEL GRAPH
<img width="612" height="292" alt="image" src="https://github.com/user-attachments/assets/026afb9f-d48e-40fc-a158-5f5aef717553" />

## Graph
![WhatsApp Image 2025-11-18 at 21 57 21_3f505e0f](https://github.com/user-attachments/assets/efcd0941-a4f8-4f18-8926-9262059aaa47)

## RESULT
Thus the experimental verification of frequency response of an analog fiber optic link is studied and verified.
