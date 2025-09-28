# 4-bit ALU (Arithmetic Logic Unit)

This project is a **4-bit ALU (Arithmetic Logic Unit)** designed in [Logisim](http://www.cburch.com/logisim/).  
The ALU supports multiple arithmetic and logical operations for 4-bit inputs.

---

## ✨ Features
- **4-bit inputs (A, B)**
- **Arithmetic Operations**
  - Addition (A + B)
  - Subtraction (A - B)
- **Logical Operations**
  - AND (A ∧ B)
  - OR (A ∨ B)
  - XOR (A ⊕ B)
  - NOT (¬A)
- **Comparison**
  - Zero detection (Z flag)
  - Carry/Overflow detection (C, V flags if implemented)

---

## ⚙️ Implementation Details
- Built using **Logisim**.
- Default design is **unsigned** (treats values from 0 to 15).  
  - If using two’s complement interpretation, it can also represent signed values (-8 to +7).  
- Modular structure for easy extension (more bits, more operations).

---

## 📂 File
- `4bitALu.circ` → Logisim circuit file (open in Logisim to simulate).

---

## 🚀 How to Use
1. Clone this repo:
   ```bash
   git clone https://github.com/notsomohit7/4-bit-alu.git
