# A full adder, what is it??

A **full adder** is a digital circuit which adds in total 3 bits — two significant input bits and a carry bit.  
Unlike a **half adder**, the full adder includes carry handling, making full binary addition possible.

---

## Forging of Full Adder

To build a _full adder_, you’ll need:

- ✅ 2× XOR gates  
- ✅ 2× AND gates  
- ✅ 1× OR gate

---

## Circuit Diagram

![sorry!](https://github.com/trinetra-1337/DIY-CPU/blob/main/images-dump/full-adder-circuit.png?raw=true)

---

## Circuit Flow of This Circuit

Let’s say your inputs are A, B, and the carry-in is Cin:

1. **First XOR**: A ⊕ B  
2. **Second XOR**: (A ⊕ B) ⊕ Cin → gives the **Sum**  
3. **First AND**: A ⋅ B  
4. **Second AND**: (A ⊕ B) ⋅ Cin  
5. **OR**: **Carry-out = (A ⋅ B) + ((A ⊕ B) ⋅ Cin)**

---

### Truth Table

| A | B | Cin | Sum | Cout |
|---|---|-----|-----|------|
| 0 | 0 |  0  |  0  |  0   |
| 0 | 0 |  1  |  1  |  0   |
| 0 | 1 |  0  |  1  |  0   |
| 0 | 1 |  1  |  0  |  1   |
| 1 | 0 |  0  |  1  |  0   |
| 1 | 0 |  1  |  0  |  1   |
| 1 | 1 |  0  |  0  |  1   |
| 1 | 1 |  1  |  1  |  1   |
