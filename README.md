# JKFLIPFLOP-USING-IF-ELSE
NAME  : B.BARKAVI

REFERNCE NO : 24901000

**EXPERIMENT NO : 7  IMPLEMENTATION OF JKFLIPFLOP USING IF ELSE**


**AIM:** 

To implement  JK flipflop using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**


A JK flip-flop is a versatile and widely used sequential logic circuit that combines the functionalities of SR (Set-Reset) flip-flops while resolving their invalid states. It has two inputs, labeled J and K, along with a clock input, a current state output (Q), and its complement output (Q'). The next state of the JK flip-flop is determined by the values of J and K inputs, the clock signal, and the current state.

Clock Dependency
The JK flip-flop transitions between states only on the active edge of the clock signal (rising or falling edge). This ensures synchronization and sequential operation in digital circuits.

Applications

Counters: Used to implement binary and frequency counters.

Memory Storage: Forms the basic building block of memory and shift registers.

Frequency Division: Divides input clock frequencies by toggling states.

By utilizing the above logic with an if-else structure, the JK flip-flop's functionality can be easily implemented in both theoretical and practical digital design scenarios.









**JK Flip-Flop**

JK flip-flop is the modified version of SR flip-flop. It operates with only positive clock transitions or negative clock transitions. The circuit diagram of JK flip-flop is shown in the following figure.

![image](https://github.com/naavaneetha/JKFLIPFLOP-USING-IF-ELSE/assets/154305477/a649c30b-232b-4558-b188-fd6c09845180)


This circuit has two inputs J & K and two outputs Qtt & Qtt’. The operation of JK flip-flop is similar to SR flip-flop. Here, we considered the inputs of SR flip-flop as S = J Qtt’ and R = KQtt in order to utilize the modified SR flip-flop for 4 combinations of inputs. The following table shows the state table of JK flip-flop.

![image](https://github.com/naavaneetha/JKFLIPFLOP-USING-IF-ELSE/assets/154305477/c4360742-e8a8-4937-b089-c46c0433f9a3)

 
Here, Qtt & Qt+1t+1 are present state & next state respectively. So, JK flip-flop can be used for one of these four functions such as Hold, Reset, Set & Complement of present state based on the input conditions, when positive transition of clock signal is applied. The following table shows the characteristic table of JK flip-flop. Present Inputs Present State Next State
 
![image](https://github.com/naavaneetha/JKFLIPFLOP-USING-IF-ELSE/assets/154305477/6c275261-a6d5-4c37-a3a7-1e88ca11c4cd)

By using three variable K-Map, we can get the simplified expression for next state, Qt+1t+1. Three variable K-Map for next state, Qt+1t+1 is shown in the following figure.
 
![image](https://github.com/naavaneetha/JKFLIPFLOP-USING-IF-ELSE/assets/154305477/5174f41b-0ce0-4329-a372-6d1943ea6673)

The maximum possible groupings of adjacent ones are already shown in the figure. Therefore, the simplified expression for next state Qt+1t+1 is Q(t+1)=JQ(t)′+K′Q(t)Q(t+1)=JQ(t)′+K′Q(t)

**truth table**



![truthtable](https://github.com/user-attachments/assets/495236c2-a7ea-42b3-90f1-2c9c5a1118d2)

**Procedure**

 write all the steps invloved 

 1. Set Inputs: Configure switches for J and K inputs.
 2. Run Simulation: Simulate circuit to see output on LEDs.
 3. Check Truth Table: Verify output with JK Flip Flop truth table.
 4. Analyze Results: Analyze results, take screenshots, and generate report.

**PROGRAM**

Program for flipflops and verify its truth table in quartus using Verilog programming.

![Screenshot (83)](https://github.com/user-attachments/assets/72f2c490-b683-4ea6-81b1-f2b03fb0048d)


**RTL LOGIC FOR FLIPFLOPS**

![Screenshot (164)](https://github.com/user-attachments/assets/8555e94f-ab50-4f6e-a709-f105a51317fd)

**TIMING DIGRAMS FOR FLIP FLOPS**


![timing](https://github.com/user-attachments/assets/cd1bdd87-9910-4605-b3af-07fdcfb33f85)


**RESULTS**

The JK Flip-Flop implemented in Verilog successfully validates its functionalityaccording to its truth table.
