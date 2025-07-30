# 🧠 Half Adder

A _**Half Adder**_ is a digital circuit that performs the addition of two single-bit binary numbers. It produces two outputs:

- **Sum (S):** The result of the bit-wise addition  
- **Carry (C):** The carry-out bit, passed on to the next higher bit in multi-bit addition

---

## 🔧 Logic Behind It

**Inputs:** A, B  
**Outputs:**
- **Sum (S) = A ⊕ B** (XOR of inputs)  
- **Carry (C) = A · B** (AND of inputs)

---

## 🛠️ How to Make a Half Adder

The process of making a half adder involves connecting basic logic gates in such a way that they add two binary bits and produce two outputs:

- **XOR gate →** for the **Sum** output  
- **AND gate →** for the **Carry** output

---

### 🧪 Truth Table

| A | B | Sum (A ⊕ B) | Carry (A ∧ B) |
|---|---|-------------|---------------|
| 0 | 0 | 0           | 0             |
| 0 | 1 | 1           | 0             |
| 1 | 0 | 1           | 0             |
| 1 | 1 | 0           | 1             |
