### study-of-basic-gates

**AIM:** 

To study and verify the truth table of logic gates in Quartus II using Verilog programming.

**Equipments Required:**

Software – Quartus prime 

**Theory**

Introduction Logic gates are the basic building blocks of any digital system. Logic gates are electronic circuits having one or more than one input and only one output. The relationship between the input and the output is based on a certain logic. Based on this, logic gates are named as

AND gate OR gate NOT gate NAND gate NOR gate Ex-OR gate Ex-NOR gate

**AND gate**

The AND gate is an electronic circuit that gives a high output (1) only if all its inputs are high. A dot (.) is used to show the AND operation i.e. A.B or can be written as AB
Y= A.B

**OR gate** 

The OR gate is an electronic circuit that gives a high output (1) if one or more of its inputs are high. A plus (+) is used to show the OR operation.
Y= A+B

**NOT gate**

The NOT gate is an electronic circuit that produces an inverted version of the input at its output. It is also known as an inverter. If the input variable is A, the inverted output is known as NOT A. This is also shown as A' or A with a bar over the top, as shown at the outputs.
Y= A'

**NAND gate**

This is a NOT-AND gate which is equal to an AND gate followed by a NOT gate. The outputs of all NAND gates are high if any of the inputs are low. The symbol is an AND gate with a small circle on the output. The small circle represents inversion.
Y= (AB)’

**NOR gate**

This is a NOT-OR gate which is equal to an OR gate followed by a NOT gate. The outputs of all NOR gates are low if any of the inputs are high. The symbol is an OR gate with a small circle on the output. The small circle represents inversion.
Y= (A+B)’

**Ex-OR gate**

The 'Exclusive-OR' gate is a circuit which will give a high output if either, but not both of its two inputs are high. An encircled plus sign (⊕) is used to show the Ex-OR operation.
Y= A⊕B

**Ex-NOR gate**

The 'Exclusive-NOR' gate circuit does the opposite to the EX-OR gate. It will give a low output if either, but not both of its two inputs are high. The symbol is an EX-OR gate with a small circle on the output. The small circle represents inversion.
Y= A⊕B

**Procedure** 

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


Program for logic gates and verify its truth table in quartus using Verilog programming

 ## Developed by:VISVANTH.V
 ## RegisterNumber:212223050061
 
 **AND GATE**
 
 **PROGRAM**
 
 ![Screenshot 2024-03-20 132854](https://github.com/naavaneetha/study-of-basic-gates/assets/162658262/d764b4bb-3b25-4ccb-9c03-31a2ab6ce902)

**Logic symbol**

![Screenshot 2024-03-20 133248](https://github.com/naavaneetha/study-of-basic-gates/assets/162658262/4d4a676d-0792-409e-92b5-3bd66081f4f0)

**RTL realization Output:**

![Screenshot 2024-03-13 141252](https://github.com/naavaneetha/study-of-basic-gates/assets/162658262/4d9e2df8-140e-4984-8e1e-2383989cd60a)

**Result:**
SUCCESSFULLY EXECUTED

**OR GATE**
 
 **PROGRAM**

![Screenshot 2024-03-20 134857](https://github.com/karuniya2005/study-of-basic-gates/assets/161425769/19aa4eb5-6304-4593-8445-60419b91e60c)

**Logic symbol**

![Screenshot 2024-03-20 135711](https://github.com/karuniya2005/study-of-basic-gates/assets/161425769/d0bc0b9a-baad-492a-8b49-1233e3a6e548)


**RTL realization Output:**

![Screenshot 2024-03-20 135553](https://github.com/karuniya2005/study-of-basic-gates/assets/161425769/630faa2d-b191-4696-99aa-1a5f93785712)

**Result:**
SUCCESSFULLY EXECUTED

**NOT GATE**
 
 **PROGRAM**

![Screenshot 2024-03-20 141508](https://github.com/karuniya2005/study-of-basic-gates/assets/161425769/2618d33b-d7dc-4ef2-a24b-e9c7a8747b52)

**Logic symbol**

![Screenshot 2024-03-20 140750](https://github.com/karuniya2005/study-of-basic-gates/assets/161425769/5a58aa29-ba6d-4090-8ef1-ba3c3de3f0da)

**RTL realization Output:**

![Screenshot 2024-03-20 141122](https://github.com/karuniya2005/study-of-basic-gates/assets/161425769/e848eb63-03b6-4d78-95c7-47013243353d)

**Result:**
SUCCESSFULLY EXECUTED

**NAND GATE**
 
 **PROGRAM**

![Screenshot 2024-03-20 142736](https://github.com/karuniya2005/study-of-basic-gates/assets/161425769/1ec3698b-44ae-4af2-9dee-ce011546f5d2)


**Logic symbol**

![Screenshot 2024-03-20 142746](https://github.com/karuniya2005/study-of-basic-gates/assets/161425769/1fbbfe23-249d-4b02-9ecb-adb9f3bfcadd)


**RTL realization Output:**


![Screenshot 2024-03-20 142918](https://github.com/karuniya2005/study-of-basic-gates/assets/161425769/9317ed9e-de81-4f17-b8f1-465e3b8620cf)

**Result:**
SUCCESSFULLY EXECUTED

**NOR GATE**
 
 **PROGRAM**
 
![Screenshot 2024-03-20 143504](https://github.com/karuniya2005/study-of-basic-gates/assets/161425769/c40761e8-44f0-485c-a5b2-0f4c46860a3f)

**Logic symbol**

![Screenshot 2024-03-20 143445](https://github.com/karuniya2005/study-of-basic-gates/assets/161425769/2ad3a83c-f8f9-4e58-ab9b-96ff3584f3eb)

**RTL realization Output:**

![Screenshot 2024-03-20 143709](https://github.com/karuniya2005/study-of-basic-gates/assets/161425769/4ee516c2-64e3-465c-ada8-5918d2d63485)

**Result:**
SUCCESSFULLY EXECUTED

**XNOR GATE**
 
 **PROGRAM**

![Screenshot 2024-03-21 152202](https://github.com/karuniya2005/study-of-basic-gates/assets/161425769/d32f2a6c-9da0-41cd-8f63-11b611bddd5e)


**Logic symbol**

![Screenshot 2024-03-21 152213](https://github.com/karuniya2005/study-of-basic-gates/assets/161425769/8b90ad0a-b71f-4bff-9a9d-49e575202be5)

**RTL realization Output:**

![Screenshot 2024-03-21 153531](https://github.com/karuniya2005/study-of-basic-gates/assets/161425769/7d9217ff-c6db-4ff6-b5ac-a6c97ef63ca0)


**Result:**
SUCCESSFULLY EXECUTED


**XOR GATE**
 
 **PROGRAM**

![Screenshot 2024-03-21 151352](https://github.com/karuniya2005/study-of-basic-gates/assets/161425769/39b84519-e8aa-42dd-8691-66400d391556)


**Logic symbol**

![Screenshot 2024-03-21 151335](https://github.com/karuniya2005/study-of-basic-gates/assets/161425769/a45a815c-7f70-4ccd-a56f-7a117ecac277)



**RTL realization Output:**

![Screenshot 2024-03-21 151532](https://github.com/karuniya2005/study-of-basic-gates/assets/161425769/4638b5a4-3e1b-483f-82fd-1e01f35df260)

**Result:**
SUCCESSFULLY EXECUTED




