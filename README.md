# EXP-1
## EXPT NO: 1	VERIFICATION OF KIRCHHOFF’S LAWS
## AIM
a.   To verify Kirchhoff’s Voltage Law (KVL) for the given circuit.<br>
b.   To verify Kirchhoff’s Current Law (KCL) for the given circuits.

## APPARATUS REQUIRED:
S.No.	Components	Range	Quantity<br>
1	Resistor	1kΩ	3<br>
2	Voltmeter (DC)	0-30V	3<br>
3	Ammeter (DC)	(0-200)mA	3<br>
4	Bread Board		1<br>
5	Regulated Power Supply	(0-30)V	1<br>
6	Connecting wires		As required<br>

## THEORY:
KVL: <br>
Kirchhoff's voltage law states that the sum of the voltage differences around any closed loop in a circuit must be zero. A loop in a circuit is any path that ends at the same point at which it starts.<br>
KCL:<br>
Kirchhoff's Current Law (KCL) Kirchhoff's Current Law states that the algebraic sum of the currents entering and leaving a node is equal to zero. By convention, currents entering the node are positive, and those leaving a node are negative<br>


## PROCEDURE:
a.   KVL:<br>
1.   Connect as per the circuit diagram.<br>
2.   Check if the RPS voltage is set to zero voltage.<br>
3.   Check all the meters for null position.<br>
4.   Switch on the RPS.<br>
5.   Set the input voltage to a value between 0V to 30V.<br>
6.   Record the voltage values shown in the voltmeter connected across each resistor.<br>
7.   Take readings for different values of input voltage and tabulate them.<br>


b.  KCL:<br>
1.   Connect as per the circuit diagram.<br>
2.   Check if the RPS voltage is set to zero voltage.<br>
3.   Check all the meters for null position.<br>
4.   Switch on the RPS.<br>
5.   Set the input voltage to a value between 0V to 30V.<br>
6.   Record the voltage values shown in the ammeter connected to each resistor.<br>
7.   Take readings for different values of input voltage and tabulate them. <br>

## CIRCUIT DIAGRAM:


a.   KVL:

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/9eaf4f74-8061-4f0a-b362-468d0b63537a" />




b.  KCL:

<img width="1920" height="1080" alt="Screenshot 2025-11-16 234046" src="https://github.com/user-attachments/assets/d5d0ec16-46c0-4ca9-bc5c-e1de977c55f3" />


## Calculation:

## a.   KVL:


$R_{eq} = R_1 + R_2 + R_3 = 270 + 330 + 560 = 1160\ \Omega$

---

#### For $V = 10\ \text{V}$

$I = \dfrac{10}{1160} = 0.00862\ \text{A}$

$V_1 = 270 \times 0.00862 = 2.33\ \text{V}$  
$V_2 = 330 \times 0.00862 = 2.84\ \text{V}$  
$V_3 = 560 \times 0.00862 = 4.83\ \text{V}$  

Check:  
$2.33 + 2.84 + 4.83 = 10$

---

#### For $V = 100\ \text{V}$

$I = \dfrac{100}{1160} = 0.0862\ \text{A}$

$V_1 = 270 \times 0.0862 = 23.33\ \text{V}$  
$V_2 = 330 \times 0.0862 = 28.41\ \text{V}$  
$V_3 = 560 \times 0.0862 = 48.30\ \text{V}$  

Check:  
$23.33 + 28.41 + 48.30 = 100$



## b.  KCL:

$R_{eq} = R_1 + \dfrac{R_2 R_3}{R_2 + R_3}
        = 270 + \dfrac{184000}{890}
        = 270 + 208
        = 478\ \Omega$

---

#### For $V = 10\ \text{V}$

$I_1 = \dfrac{10}{478} = 0.02\ \text{A}$

$I_2 = 0.02 \times \dfrac{330}{890} = 0.01\ \text{A}$

$I_3 = 0.02 \times \dfrac{560}{890} \approx 0.01\ \text{A}$

Check:  
$I_1 = I_2 + I_3 = 0.01 + 0.01$

---

#### For $V = 100\ \text{V}$

$I_1 = \dfrac{100}{478} = 0.21\ \text{A}$

$I_2 = 0.21 \times \dfrac{330}{890} = 0.08\ \text{A}$

$I_3 = 0.21 \times \dfrac{560}{890} = 0.13\ \text{A}$

Check:  
$I_1 = I_2 + I_3 = 0.08 + 0.13$




## Tabulation:

### a.   KVL:


| S.No | Supply Voltage V (volts) | Req (Ω) | Current I (A) | V1 (volts) | V2 (volts) | V3 (volts) | Check: V1 + V2 + V3 |
|------|---------------------------|---------|----------------|------------|------------|------------|----------------------|
| 1    | 10                        | 1160    | 0.00862        | 2.33       | 2.84       | 4.83       | ≈ 10                 |
| 2    | 100                       | 1160    | 0.0862         | 23.33      | 28.41      | 48.30      | ≈ 100                |



### b.  KCL:


| S.No | Supply Voltage V (volts) | Req (Ω) | I₁ (mA) | I₂ (mA) | I₃ (mA) | Check: I₁ = I₂ + I₃ |
|------|---------------------------|---------|---------|---------|---------|-----------------------|
| 1    | 10                        | 478     | 0.02    | 0.01    | 0.01    | 0.02 = 0.01 + 0.01    |
| 2    | 100                       | 478     | 0.21    | 0.08    | 0.13    | 0.21 = 0.08 + 0.13    |



## RESULT:

**_Thus, for the given circuit, Kirchhoff’s Laws, (a) KVL and (b) KCL are proved._**
