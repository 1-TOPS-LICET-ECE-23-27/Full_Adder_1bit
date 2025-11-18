# Full_Adder_1bit

1 Bit Full Adder

## **Project Description**
Verilog project implementing a 1-bit full adder using Quartus Prime and ModelSim.

---

## ** Procedure for Quartus HDL Project**

### ** Create a New Project**
- Open Quartus Prime
- Go to **File → New Project Wizard**
- Choose the project directory
- Enter the project name
- Finish project setup

---

### ** Create Design File (HDL Source)**
- Go to **File → New → (Verilog/VHDL) File**
- Write your design code
- Save the file



---

### ** Create Testbench File (For Simulation)**
- Go to **File → New → (Verilog/VHDL) File**
- Write the testbench to test your design
- Save the file

---

### ** Add Required Files to the Project**
- Go to **Project → Add/Remove Files in Project**
- Add your design file(s)
- Add your testbench file (for simulation)

---

### **Compile the Project**
- Go to **Processing → Start Compilation**
- Wait for the compilation to finish without errors


---

##  **Simulation Procedure 
- Go to **Tools → Run Simulation Tool → RTL Simulation**
- Open your testbench
- Run simulation
- View waveforms to verify the logic



---

##  ** FPGA Pin Assignment**
Only required if the design is to be implemented on hardware.

- Go to **Assignments → Pin Planner**
- Map external signals (inputs/outputs) to physical FPGA pins
- Recompile
- Program the FPGA device



---

##  **Recommended Folder Structure**
```
 1 bit full adder
 ┣  full_adder.sv / v / vhd
 ┣  full_tb.sv / v / vhd
 ┣  output_files
 ┣  simulation
 ┗  README.md
```

---

