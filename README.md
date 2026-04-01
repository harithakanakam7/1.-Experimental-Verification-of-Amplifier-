#**EX.NO:** 1  # EXPERIMENTAL VERIFICATION OF AMPLIFIER INVERTING, NON INVERTING , DIFFERENTIAL AMPLIFIER AND INSTRUMENTATION AMPLIFIERS
**DATE:**  
---

## AIM
To design and construct an Inverting, Non-Inverting, Differential and Instrumentation amplifiers.

---

## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 1 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors | 1K, 10K, 2.2K | 2 |
| 7 | Connecting wires and probes | As required | — |

---

## THEORY

Op-amp in open-loop configuration has limited application due to its enormous open-loop gain. Controlled gain can be achieved by taking a part of the output signal to the input through feedback.  
This is called a **Closed-Loop Configuration**.

The four basic types of closed-loop amplifier configurations are:
- Inverting amplifier  
- Non-inverting amplifier  
- Differential amplifier
- Instrumentation amplifier 

The entire configuration can operate with either AC or DC input.
		
 

---

### **Inverting Amplifier**

This is the most widely used op-amp configuration.  
The output voltage Vo  is fed back to the inverting input terminal through the  Rf - R1 network.  
The negative sign in gain indicates a **phase shift of 180°**.


Acl = -RF/R1

PIN DIAGRAM


<img width="900" height="1600" alt="image" src="https://github.com/user-attachments/assets/d0d70cfc-e50b-44f7-bc43-916b1f9cf482" />


CIRCUIT DIAGRAM: INVERTING AMPLIFIER:


<img width="738" height="1600" alt="image" src="https://github.com/user-attachments/assets/9d2eab24-03da-4940-9e77-7d71396c1233" />


MODEL GRAPH 

<img width="738" height="1600" alt="image" src="https://github.com/user-attachments/assets/7475f92e-3bd7-4514-816f-ec676d5ec038" />



DESIGN:


<img width="738" height="1600" alt="image" src="https://github.com/user-attachments/assets/3d224a5f-d281-4cb2-b361-d0080f04690b" />


Inverting amplifier:

A = -Rf/R1
Take  A = 10
Rf =10 R1
Choose R1 = 1kΩ, Rf=10kΩ

PROCEDURE:
Inverting amplifier:

1.	Select R1 as a constant value and choose a value of Rf.
2.	Connect the circuit as per as the circuit diagram.
3.	Apply the constant amplitude input voltage to the circuit.
4.	Measure the output voltage amplitude for different value of V1 from DSO.
5.	Calculate the practical Voltage for different value of V1 & compare it with theoretical output.
6.	Practical gain & theoretical voltage should be approximately equal.
7.	Plot the graph of the input wave versus output wave for any one practical case.


## TABULATION

<img width="738" height="1600" alt="image" src="https://github.com/user-attachments/assets/847df930-fff2-422e-ba81-31fddfcc3909" />
	
 


---
## OUT PUT WAVEFORM AND DISCUSSION 
<img width="738" height="1600" alt="image" src="https://github.com/user-attachments/assets/ba2fbc36-10f1-4d43-9d13-33de5f357310" />
<img width="1600" height="738" alt="image" src="https://github.com/user-attachments/assets/c07c51fd-4393-45b6-8ebe-e585edb69e5a" />


---
### **Non-Inverting Amplifier**

If the signal is applied to the non-inverting input terminal without inversion, it is called a **non-inverting amplifier**.  
Here, the output is fed back to the inverting terminal, and **no phase shift** occurs.


ACL = 1 + RF/R1


---

## CIRCUIT DIAGRAM


<img width="738" height="1600" alt="image" src="https://github.com/user-attachments/assets/28128285-8388-4885-8cf8-f9b5b5202725" />


---

## MODEL GRAPH

<img width="900" height="1600" alt="image" src="https://github.com/user-attachments/assets/46437733-fa30-46b2-9954-05e8a5070b81" />


---
PROCEDURE:
### **For  Non-Inverting Amplifier**
1. Select R1  as a constant value and choose a value for Rf .  
2. Connect the circuit as per the diagram.  
3. Apply constant amplitude input voltage.  
4. Measure the output voltage amplitude for different V1 using DSO.  
5. Compare practical and theoretical values of Vo .  
6. Verify that practical gain ≈ theoretical gain.  
7. Plot the input vs. output waveform for one practical case.

## TABULATION

<img width="738" height="1600" alt="image" src="https://github.com/user-attachments/assets/e87de1d1-e5c9-4c81-842b-09c2342a630e" />


---
## OUT PUT WAVEFORM AND DISCUSSION 

<img width="738" height="1600" alt="image" src="https://github.com/user-attachments/assets/a098f6a7-edd3-451f-ad90-32cc454849f4" />
<img width="738" height="1600" alt="image" src="https://github.com/user-attachments/assets/ad3f0a45-6c17-454a-8d93-fb650254d5fc" />


---
## DIFFERENTIAL AMPLIFIER

A circuit that amplifies the **difference** between two input signals is called a **Differential Amplifier**.  
It is useful in instrumentation applications.  
If the two input signals are identical, the output is ideally **zero**.


A = Vo/{V2 - V1} = -Rf/R1
## CIRCUIT DIAGRAM
<img width="738" height="1600" alt="image" src="https://github.com/user-attachments/assets/c8939e10-70af-4289-8a93-609c9c278df8" />


## MODEL GRAPH
<img width="738" height="1600" alt="image" src="https://github.com/user-attachments/assets/589b554e-0484-43bb-8284-63b0707b4abd" />


---

## DESIGN
<img width="1148" height="1333" alt="image" src="https://github.com/user-attachments/assets/2e1968c5-353a-40cd-99a0-cd7c48e64a0a" />



### **Differential Amplifier**

AV = Vo/{V1 - V2} = -Rf/R1


Take  A = 10 
⇒  Rf = 10R1   
Choose  R1 = 1kOhm, Rf = 10kOhm

---



## PROCEDURE (Differential Amplifier)
1. Select  R1, R2, R3, Rf  such that R1 = R2  and  R3 = Rf .  
2. Connect the circuit as per the circuit diagram.  
3. Apply constant inputs Vin1 and  Vin2 .  
4. Measure output voltage using DSO.  
5. Compare theoretical and practical  Vo .  
6. Verify practical ≈ theoretical output.  
7. Plot the input vs. output waveform.

---

## TABULATION (Differential Amplifier)

<img width="738" height="1600" alt="image" src="https://github.com/user-attachments/assets/8adb63a6-d16e-48ea-85ed-79cebcf110da" />


---
## OUT PUT WAVEFORM AND DISCUSSION 
<img width="738" height="1600" alt="image" src="https://github.com/user-attachments/assets/f361a089-a715-47d2-8278-2c8b2a61e771" />


---
## INSTRUMENTATION AMPLIFIER

THEORY:

An instrumentation amplifier is the intermediate stage of a instrumentation system. The signal source of the instrumentation amplifier is the output of the transducer. Many transducers output do not have the ability or sufficient strength to drive the next following stages. Therefore, instrumentation amplifiers are used to amplify the low-level output signal of the transducer so that it can drive the following stages such as indicator or displays.
The major requirements of a instrumentation amplifier are precise, low-level signal amplification where low-noise, low thermal and time drifts, high input resistance & accurate closed-loop gain, low power consumption, high CMRR & high slew rate for superior performance.
The output of Instumentation amplifier is given by
Vo = RF/R1[1+ 2R’/R][V2-V1]
 

## CIRCUIT DIAGRAM: INSTRUMENTATION AMPLIFIER

<img width="738" height="1600" alt="image" src="https://github.com/user-attachments/assets/1ee2bb3d-1ff1-4398-bcf7-8942270f0e01" />


PROCEDURE:

1.	Select the entire resistor with the same value. Let R be the gain varying resistor with different values of resistance for simplicity let R be a constant value.
2.	Connect the circuit as shown in the circuit diagram.
3.  + Vcc and - Vcc supply is given to the power supply terminal of the Op-Amp IC.
4.	Give the input V1 and V2 to the non-inverting terminals of first & second op-amp respectively.
5.	By varying the value of RG, measure the output voltage for common mode and differential mode operation. Since RG is selected as constant value, provide different input value of V1 and V2.
6.	Check the theoretical value with the experimental value.
7.	The output voltage is obtained in the Multimeter and the input and output voltage waveforms are plotted in a graph sheet

---

## TABULATION (Instrumentation Amplifier)

<img width="738" height="1600" alt="image" src="https://github.com/user-attachments/assets/3d3697b1-b7f8-475b-9d62-80ba14a90757" />


---
## OUT PUT WAVEFORM AND DISCUSSION 
<img width="738" height="1600" alt="image" src="https://github.com/user-attachments/assets/9836d023-bdc2-4cf2-92b9-aca77e649efd" />



---
## RESULT
Thus, the **Inverting**, **Non-Inverting**, **Differential**, and **Instrumentation Amplifiers** were designed and their performance successfully tested using Op-Amp IC 741.

---
