### NAME: SRIYALINE R
### REG NO: 24006194
# EXPERIMENT 5: IMPLEMENTATION OF JK FLIPFLOP

# AIM

To implement  JK flipflop using verilog and validating their functionality using their functional tables

# SOFTWARE REQUIRED

Quartus prime

# THEORY

# JK Flip-Flop

JK flip-flop is the modified version of SR flip-flop. It operates with only positive clock transitions or negative clock transitions. The circuit diagram of JK flip-flop is shown in the following figure.

![image](https://github.com/naavaneetha/JKFLIPFLOP-USING-IF-ELSE/assets/154305477/a649c30b-232b-4558-b188-fd6c09845180)


This circuit has two inputs J & K and two outputs Qtt & Qtt’. The operation of JK flip-flop is similar to SR flip-flop. Here, we considered the inputs of SR flip-flop as S = J Qtt’ and R = KQtt in order to utilize the modified SR flip-flop for 4 combinations of inputs. The following table shows the state table of JK flip-flop.

![image](https://github.com/naavaneetha/JKFLIPFLOP-USING-IF-ELSE/assets/154305477/c4360742-e8a8-4937-b089-c46c0433f9a3)

 
Here, Qtt & Qt+1t+1 are present state & next state respectively. So, JK flip-flop can be used for one of these four functions such as Hold, Reset, Set & Complement of present state based on the input conditions, when positive transition of clock signal is applied. The following table shows the characteristic table of JK flip-flop. Present Inputs Present State Next State
 
![image](https://github.com/naavaneetha/JKFLIPFLOP-USING-IF-ELSE/assets/154305477/6c275261-a6d5-4c37-a3a7-1e88ca11c4cd)

By using three variable K-Map, we can get the simplified expression for next state, Qt+1t+1. Three variable K-Map for next state, Qt+1t+1 is shown in the following figure.
 
![image](https://github.com/naavaneetha/JKFLIPFLOP-USING-IF-ELSE/assets/154305477/5174f41b-0ce0-4329-a372-6d1943ea6673)

The maximum possible groupings of adjacent ones are already shown in the figure. Therefore, the simplified expression for next state 

Qt+1t+1 is Q(t+1)=JQ(t)′+K′Q(t)

Q(t+1)=JQ(t)′+K′Q(t)

# PROCEDURE
1.  Launch Quartus on your computer and create a new project:

Go to File → New Project Wizard.

Specify the project name, directory, and top-level entity name (e.g., JK_FlipFlop).

2. Create the JK Flip-Flop Circuit and implement the JK Flip-Flop by writing VHDL/Verilog code.

Go to File → New → Select Verilog File.

3.  Compile the Project

Click on Processing → Start Compilation.

Fix any syntax or schematic errors if present.

4.  Simulate the Circuit:

Go to Tools → University Program VWF.

Define the inputs for J, K, and CLK in the waveform editor.

Run the simulation and observe the waveforms.

5.  Verify the Results.
  
Compare the simulated results with the truth table for a JK Flip-Flop.

# PROGRAM
![Screenshot 2024-12-09 102722](https://github.com/user-attachments/assets/9104da49-f5f4-4ca3-96f2-40de03aa9292)

# RTL
![Screenshot 2024-12-09 102739](https://github.com/user-attachments/assets/53c2bf0d-3ff3-4e34-bf22-87a107b17e27)

# TIMING DIAGRAM
![Screenshot 2024-12-09 110631](https://github.com/user-attachments/assets/2602bcd5-6a8b-4bc5-9a95-f94e2cae231e)

# RESULT
Implementation of JK flipflop using verilog and validating their functionality using their functional tables is verified.
