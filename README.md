# EX-NO-4-EXPERIMENTAL-VERIFICATION-OF-OSCILLATOR
4. ##**EX.NO:* ## EXPERIMENTAL VERIFICATION OF RC Phase Shift and Wien Bridge oscillators 
	DATE:
 ##AIM:
To construct a RC phase shift and Wien bridge oscillator to generate sine wave using op-
amp.
---
 ##THEORY:
 ##RC PHASE SHIFT OSCILLATOR
RC phase shift oscillator produces 360° of phase shift in two parts. Firstly,each and every RC pair in the feedback network produces 60° phase shift and totally there were three pairs, thus producing 180° Phase shift and secondly, the feedback input is given to the inverting terminal of op-amp to produce another 180° phase shift and a total phase shift of 360°.
The frequency of oscillation is given by fo = 1 /  6 (2RC ).If an inverting amplifier is used, the gain must be atleast equal to 29 to ensure the oscillations with constant .
---

## APPARATUS REQUIRED

| S.No | Name of the Apparatus          | Range         | Quantity |
|------|---------------------------------|---------------|----------|
|1    | DSO                             | 30 MHz        | 1        |
|2   | Dual RPS                        | (0–30) V      | 1        |
| 3    | Op-amp                          | µA741         | 1        |
|4    | Bread Board                     | —             | 1        |
|5   | Resistors                       | 1K, 3.3K, 1.5K, 33K, 15K, 1MΩ | 2 |
|6    | Capacitor                       | 0.1 µF        | 3        |
| 6   | Connecting wires and probes     | As required   | —        |
| 



---
## CIRCUIT DIAGRAM
RC PHASE SHIFT OSCILLATOR

<img width="1600" height="936" alt="image" src="https://github.com/user-attachments/assets/c7a348ec-d623-4f8c-a1d0-f1dfcf6d1833" />




---

## MODEL GRAPH
<img width="1600" height="579" alt="image" src="https://github.com/user-attachments/assets/19a97b7b-9516-4b1f-aa6b-e3dd2b2d66f2" />

## DESIGN

<img width="1600" height="854" alt="image" src="https://github.com/user-attachments/assets/14308d87-6663-48ad-91b5-7ebc4c237acf" />

## RC PHASE SHIFT OSCILLATOR
fo = 1 /  6 (2RC) Rf  29 R1
C = 0.01F, fo = 200 Hz.
R = 1 /  6 (2  f C ) = 3.3 k
Therefore, Choose R = 3.3k
To prevent loading,
R1   10 R
R1 =10 R = 33 k. Rf = 29R1=1MΩ

---
## PROCEDURE
1.	Connect the circuit as shown in fig. With the design values.
2.	Observe the output waveforms using a DSO.For obtaining sine wave adjust Rf.
3.	Measure the output wave frequency and amplitude.
---
## TABULATION/OBSERVATION

<img width="1600" height="1175" alt="image" src="https://github.com/user-attachments/assets/ccbbb7c9-e4a8-449e-86b3-3908ff625a67" />

---
## OUT PUT WAVEFORM AND DISCUSSION 

![WhatsApp Image 2025-11-27 at 6 45 34 PM](https://github.com/user-attachments/assets/416109cd-921a-4e90-926d-a85f6f4c9ce9)

---
## THEORY
 ##WIEN BRIDGE
A bridge circuit with two components connected in series and parallel combination is used to archived the required of phase shift of 0o. When the bridge is balanced the phase shift of 0o is achieved and the feedback signal is connected to the positive terminal; of Op-amp. So the Op-amp is acting as a non-inverting amplifier and the feedback network do not provide any phase shift.
The frequency of oscillation is given by fo = 1/2πRC
## APPARATUS REQUIRED

| S.No | Name of the Apparatus          | Range         | Quantity |
|------|---------------------------------|---------------|----------|
|1    | DSO                             | 30 MHz        | 1        |
|2   | Dual RPS                        | (0–30) V      | 1        |
| 3    | Op-amp                          | µA741         | 1        |
|4    | Bread Board                     | —             | 1        |
|5   | Resistors                       | 1K, 3.3K, 1.5K, 33K, 15K, 1MΩ | 2 |
|6    | Capacitor                       | 0.1 µF        | 3        |
| 7 | Connecting wires and probes     | As required   | —        |

---

## CIRCUIT DIAGRAM
WIEN BRIDGE OSCILLATOR


<img width="1600" height="1210" alt="image" src="https://github.com/user-attachments/assets/31835e72-a744-43bc-a54a-28f3209d8d9a" />



---
## MODEL GRAPH

<img width="1600" height="579" alt="image" src="https://github.com/user-attachments/assets/c16320ae-a584-4ded-833f-cbedd0dd89f0" />



---

## DESIGN

<img width="1600" height="1336" alt="image" src="https://github.com/user-attachments/assets/94c0e1a5-f3f3-4d5a-bff6-566144724b83" />

## WIEN BRIDGE OSCILLATOR
Select frequency f0 = 1KHz
fo = 1/2πRC
A = 1+(Rf / R1) = 3.
To find R & Rf.
Therefore Rf = 2R1 & assume C = 0.1μf & find R from
R=1/2πfC
=1/2*3.14*1*103*0.1*10-6
= 1.59KΩ.
Assume R1 = 10R & find Rf from Rf = 2R1
Therefore R1 = 1.5K *10=15KΩ
Rf = 15K *2=30KΩ
---

## PROCEDURE

1.	Connections are given as per the circuit diagram
2. + Vcc and - Vcc supply is given to the power supply terminal of the Op-Amp IC.
3.	By adjusting the amplitude and frequency knobs of the function generator, appropriate input voltage is applied to the inverting input terminal of the Op- Amp.
4.	The output voltage is obtained in the CRO and the input and output voltage waveforms are plotted in a graph sheet.
---
## TABULATION/OBSERVATION

![WhatsApp Image 2025-11-27 at 6 39 58 PM](https://github.com/user-attachments/assets/e606abab-3036-4a09-925f-a2bfa24cf9d2)

---
## OUT PUT WAVEFORM AND DISCUSSION 


<img width="1600" height="1206" alt="image" src="https://github.com/user-attachments/assets/9c5986a2-056e-47e2-ad2f-67d4412540c2" />


---
## RESULT:

<img width="1600" height="641" alt="image" src="https://github.com/user-attachments/assets/62677f92-30fc-4e72-8335-6e847f357d61" />

Thus the RC Phase Shift and Wien Bridge oscillators are designed and tested using op-amp IC 741.
