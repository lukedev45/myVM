# myVM  
*A simple virtual machine with a custom instruction set, designed for learning low-level computation, instruction dispatch, and systems architecture.*

## 📌 Overview  
`myVM` is a lightweight virtual machine built from scratch to understand how CPUs execute instructions at a low level.  
It includes:

- A custom **instruction set architecture (ISA)**  
- A defined **memory model**  
- A basic set of **registers**  
- An **instruction decoder + dispatcher**  
- Execution of simple **programs written in assembly-like syntax**  

This project is meant to bridge the gap between high-level programming and the underlying hardware concepts found in real architectures (like LC-3, RISC-V, or x86).

---

## 🎯 Motivation  
Modern programming abstracts away memory management, registers, and even low-level control flow.  
Building a VM from the ground up helps you understand:

- How instructions are encoded, decoded, and executed  
- How registers and memory interact  
- How branching, arithmetic, and I/O work at the machine level  
- How assemblers translate human-readable text into opcodes  

It is also fantastic preparation for:

- Systems programming  
- Computer architecture courses  
- Security challenges (like OverTheWire / pwn / CTFs)  
- Compilers and interpreters  
- Understanding how real CPUs *actually* work  

---

## 🧠 Features  
### ✔ Custom Instruction Set  
Includes (example) opcodes such as:

LOAD R1, 10
LOAD R2, 20
ADD R3, R1, R2
PRINT R3
HALT


---

## 🚀 Getting Started  

### 🔧 Requirements  
- Python 3.x  
(No external dependencies unless you add them.)

### 📥 Installation  
Clone the repository:

```bash
git clone https://github.com/lukedev45/myVM
cd myVM
