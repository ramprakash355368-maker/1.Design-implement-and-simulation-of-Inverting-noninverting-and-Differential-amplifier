# 1.Design-implement-and-simulation-of-Inverting-noninverting-and-Differential-amplifier

**AIM:**
To design , implement and simulate  an inverting, non- inverting and differential amplifiers

**APPARATUS  and SOFTWARE REQUIRED:**
S.No	Name of the Apparatus	Range	Quantity
1.	Function Generator	3 MHz	1
2.	DSO	30 MHz	1
3.	Dual RPS	(0 – 30) V	1
4.	Op-Amp	µA741	1
5.	Bread Board		1
6.	Resistors	1K,10K	2
7.	Connecting wires and probes	As required	
8.  LT SPICE software

**THEORY:**
Op-amp in open-loop configuration has a very few application because of its enormous open-loop gain. Controlled gain can be can be achieved by taking a part of output signal to the input with the help of feedback. This is called as Closed- Loop Configuration. The three basic types of closed-loop amplifier configuration are:
1.	Inverting amplifier.
2.	Non-inverting amplifier.
3.	Differential amplifier.
The entire configuration can be operated with either AC or DC input.

**INVERTING AMPLIFIER:**
This is the most widely used op-amp. Here, the output voltage Vo is feedback to the inverting input terminal through the Rf – R1 network. The negative sign in gain indicates the phase shift of 180ο.
The circuit closed-loop voltage gain is Avcl= -RF / R1

**NON - INVERTING AMPLIFIER:**
If signal is applied to the non-inverting input terminal of op-amp without inverting the input signal such a circuit is called non-inverting amplifier. Here the output is feedback to the inverting input terminal. The phase shift of input signal does not occur in non-inverting terminal.
The circuit closed-loop voltage gain is ACL = 1 + ( RF / R1)

**DIFFERENTIAL AMPLIFIER**
A circuit that amplifies that amplifies the difference between two input signals is called as differential amplifier. It is useful in instrumentation amplifier. If the two input signals are the same, the output should be zero. Differential amplifier with a single op-amp has the exact gain of an inverting amplifier and it is given as
𝐴	= 	𝑉𝑜/(V2-V1) = −𝑅𝑓/R1

**DESIGN:**

**Inverting amplifier:**
    Gain is     A = -Rf/R1
        Take  A = 10
        Rf =10 R1
        Choose R1 = 1kΩ, Rf=10kΩ
        
**Non inverting amplifier:**
    Gain is    A = 1+ Rf/R1
      Take A = 2
      Rf = R1
      Choose Rf = 10kΩ, R1=10kΩ
      
**Differential amplifier**
  Gain is 𝐴=	𝑉𝑜/(𝑉1− V2)= − 𝑅𝑓/𝑅1
Take  A = 10
 Rf =10 R1
Choose R1 = 1kΩ, Rf=10kΩ

**PROCEDURE:**
**Inverting and Non-inverting amplifier:**
1.	Select R1 as a constant value and choose a value of Rf.
2.	Connect the circuit as per as the circuit diagram.
3.	Apply the constant amplitude input voltage to the circuit.
4.	Measure the output voltage amplitude for different value of V1 from DSO.
5.	Calculate the practical Voltage for different value of V1& compare it with theoretical output.
6.	Practical gain & theoretical voltage should be approximately equal.
7.	Plot the graph of the input wave versus output wave for any one practical case.
   
**Differential amplifier:**
1.	Select the value of R1, R2, R3 & Rf such that R1=R2 and R3=Rf.
2.	Connect the circuit as per as the circuit diagram.
3.	Provide constant input voltage Vin1 to Non-inverting terminal of op-amp through R1 & constant input voltage Vin2 to inverting terminal of op-amp through R2.
4.	Measure the output voltage using DSO.
5.	Calculate the theoretical Vo and compare it with practical Vo.
6.	Practical output & theoretical calculation should be approximately equal.
7.	Plot the graph of the input wave versus output wave for any one practical case.
 
**PIN DIAGRAM:**
<img width="1600" height="535" alt="WhatsApp Image 2026-09-13 at 7 46 45 PM" src="https://github.com/user-attachments/assets/c6efb541-1cf2-419e-b891-2f3932a21999" />



**INVERTING AMPLIFIER:**
  **CIRCUIT DIAGRAM**
<img width="1422" height="701" alt="WhatsApp Image 2026-09-13 at 7 47 46 PM" src="https://github.com/user-attachments/assets/691528c2-42c1-4c5a-98b1-8aff8ff2d4fa" />


  **MODEL GRAPH:**
<img width="1406" height="946" alt="WhatsApp Image 2026-09-13 at 7 48 42 PM" src="https://github.com/user-attachments/assets/4eee4ad0-b908-40cc-925f-b47fbbe7570d" />


  **TABULATION:**
 <img width="1306" height="784" alt="WhatsApp Image 2026-09-13 at 7 49 44 PM" src="https://github.com/user-attachments/assets/80d30a58-a376-40d0-8be1-2692373a9dde" />
**CALCULATION:**
<img width="1600" height="683" alt="WhatsApp Image 2026-09-13 at 7 53 11 PM" src="https://github.com/user-attachments/assets/74eec40e-0c3c-40e4-8b6b-104b328f1775" />

**GRAPH:**
<img width="1600" height="1033" alt="WhatsApp Image 2026-09-13 at 8 04 37 PM" src="https://github.com/user-attachments/assets/13de6067-e91a-47ad-8a87-425fca4083ac" />



**NON INVERTING AMPLIFIER:**
  **CIRCUIT DIAGRAM**
<img width="1600" height="994" alt="WhatsApp Image 2026-09-13 at 7 50 52 PM" src="https://github.com/user-attachments/assets/8922fe8e-925b-4cc7-9d68-5bf9b0d13801" />


  **MODEL GRAPH:**
<img width="1600" height="984" alt="WhatsApp Image 2026-09-13 at 7 51 48 PM" src="https://github.com/user-attachments/assets/b02e8b0a-d0cc-4906-909f-92430dbab576" />


  **TABULATION:**
<img width="1600" height="928" alt="WhatsApp Image 2026-09-13 at 7 52 19 PM" src="https://github.com/user-attachments/assets/b789523b-7d2b-43e5-b1b6-440fb28ea86b" />

**CALCULATION:**
<img width="1600" height="573" alt="WhatsApp Image 2026-09-13 at 7 55 21 PM" src="https://github.com/user-attachments/assets/5d50b781-85ca-495e-8ffc-38c45c2a6463" />

**GRAPH:**
<img width="1600" height="892" alt="WhatsApp Image 2026-09-13 at 8 05 06 PM" src="https://github.com/user-attachments/assets/905788a1-f573-427e-93f5-e13e8116ead2" />

  **DIFFERENTIAL AMPLIFIER:**
  **CIRCUIT DIAGRAM**
  <img width="1600" height="867" alt="WhatsApp Image 2026-09-13 at 7 56 03 PM" src="https://github.com/user-attachments/assets/c96eedd9-257f-4490-b828-021ee505a7af" />



  **MODEL GRAPH:**
<img width="1323" height="826" alt="WhatsApp Image 2026-09-13 at 7 56 28 PM" src="https://github.com/user-attachments/assets/6c21f5ac-7eab-40a0-97ca-92c02735096e" />


  **TABULATION:**
<img width="1600" height="951" alt="WhatsApp Image 2026-09-13 at 7 56 52 PM" src="https://github.com/user-attachments/assets/79514332-02f5-4b67-a080-ef543c98e264" />

**CALCULATION:**
<img width="1600" height="632" alt="WhatsApp Image 2026-09-13 at 7 57 19 PM" src="https://github.com/user-attachments/assets/5a0d2bb9-7c3a-4cca-bed4-c92f9f1a77e3" />

**GRAPH:**
<img width="1600" height="1526" alt="WhatsApp Image 2026-09-13 at 8 05 41 PM" src="https://github.com/user-attachments/assets/d0ace1c6-a867-48c6-8fc6-f28d8e2706cc" />

**LT-SPICE Tool:**
**PROCEDURE:**
•	Double click on LT-Spice icon.
•	New schematic window open.
•	Pick and paste the required component from the library and draw the circuit diagram .
•	Complete the connection.
•	Save the file by giving file name.
•	Click on the run option ->click advanced open ->select Ac analysis->enter the amplitude time delay stop time value.
•	Click on the run option ->simulation window opens->place the probe ->output graph is obtained.
 
  **LT SPICE**
  **CIRCUIT and Waveform**
  **INVERTING AMPLIFIER:**
  <img width="1600" height="900" alt="WhatsApp Image 2026-09-13 at 7 39 53 PM" src="https://github.com/user-attachments/assets/ffdf0bc6-7fbb-48a9-8f56-c59bf8afe2ae" />

**NON INVERTING AMPLIFIER:**
<img width="1600" height="900" alt="WhatsApp Image 2026-09-13 at 7 39 53 PM (1)" src="https://github.com/user-attachments/assets/735d8669-5c91-4573-a379-5abe7bf5c858" />

**DIFFERENTIAL AMPLIFIER:**
  <img width="821" height="413" alt="WhatsApp Image 2026-09-13 at 8 11 07 PM" src="https://github.com/user-attachments/assets/de7e9556-e3e0-484d-ac27-8a5c58b34a78" />

  

**RESULT:**
Thus the Inverting, Non-Inverting and Differential Amplifiers are designed and simulated performance was successfully tested using op-amp IC 741 and LT SPICE.
 






