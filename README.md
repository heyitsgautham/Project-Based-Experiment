### Project-Based-Experiment

**AIM:**

To design and simulate the traffic light controller.

**SOFTWATE USED:**

Quartus II

**THEORY:**
	
     	Consider a controller for traffic at the intersection of three main roads.  

  ![image](https://github.com/naavaneetha/Project-Based-Experiment/assets/154305477/e3af03dd-a4de-4b21-af0a-a5a332a3e4b6)


 The traffic signal for all the three main roads have equal priority and they remain red by default.

 In state 00,the traffic signals remains red for first five counts and yellow of road1 turns on for the next four counts.

 In state 01, the green of road1 turns on for first five counts and yellow of road1 and road2 turns on for next four4 counts of this state.
 
 In state 10, the traffic signal of road1 comes back to the red and that of road2 goes to green for tee first five counts.For the next four counts the traffic signal of road2 and road3 remains yellow.


 In state 11, the traffic signal of road2 comes back to the red and that of road3 goes to green for the first five counts.For the next four counts the traffic signal of road3 turns to yellow

 At the end of four states,the traffic signal of all the three roads come back to red.

**Task Assigned**

From the HDL code given formulate the correct code  to divert the traffic to path 1 direction and disable the control in other directions (Assume user is at MR3 spot)

**Procedure**

1.	Type the program in Quartus software.
2.	Compile and run the program.
3.	Generate the RTL schematic and save the logic diagram.
4.	Create nodes for inputs and outputs to generate the timing diagram.
5.	For different input combinations generate the timing diagram
   
**Program:**

/* 
Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
Developed by: GAUTHAM KRISHNA S
RegisterNumber: 212223240036
*/

**RTL Schematic**

![331851446-b4c4498d-0fef-48d5-9b15-240ddf5ed7ff](https://github.com/gauthamkrishna7/Project-Based-Experiment/assets/141175025/be23cd85-5d2c-4750-865d-580c6b96587a)


**Output Timing Waveform**

![331851457-592b042a-6bd9-45f8-8f0a-1aa98d11c6e8](https://github.com/gauthamkrishna7/Project-Based-Experiment/assets/141175025/17e85618-edf1-4f46-bcde-05bc91718c39)


**Result:**

Thus the design and simulate the traffic light controller are successfullt executed.




