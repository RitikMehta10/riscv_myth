
[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)

# RISCV-Based-Myth_Program

![image alt](https://github.com/RitikMehta10/riscv_myth/blob/3b4daf4675abc2c22540f61e924c69cecde43bad/image.png)


A repository containing all details of the RISC-V MYTH workshop, which focuses on building a RISC-V core from scratch using TL-Verilog. It includes lecture materials, hands-on exercises, and reference designs.

# MAKERCHIP PLATFORM

## 🎛️ 🎶 Understanding the Multiplexer (MUX)

## 🔍 What is a Multiplexer?

A **Multiplexer** (or **MUX**) is a **combinational circuit** that selects one of several inputs and sends it to the output.  
Think of it like a **digital switch** controlled by select lines.

---

## 🛠️ 2-to-1 Multiplexer (Basic Example)

### 🔌 Inputs:
- `x1`, `x2`: Two input signals (1-bit each)  
- `s`: Select signal (1 bit)

### 📤 Output:
- `f`: The selected output, based on `s`

### 🧮 Boolean Expression:
If `s = 0`, then `f = x2`  
If `s = 1`, then `f = x1`

[trying to make a relative link](main/image.png)
