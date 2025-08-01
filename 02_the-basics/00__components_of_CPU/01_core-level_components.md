# **core compoents of a CPU**
- the CPU has various components which work on the the most lower level. All the binary calculations, execution of instruction etc. are done here.

## lets discuss each component in detail.

![ALU](https://raw.githubusercontent.com/trinetra-1337/DIY-CPU/main/images-dump/ALU.webp)
 
# 1. **Arithematic and logic unit (ALU)**

- ALU is a digital circuit in the cpu where arithematic operations like addition, subtraction, multiplicaton etc. and logical operations like AND, OR, XOR are done.
- this is the part of the execution units if the CPU. IT works alongside Control Unit(CU) and registers.
- thet CU tells the ALU which operations to perform, the ALU performs the oprtation and send the result back to the register or memory.

the work flow of the ALU is like this:-
Instruction ➝ CU decodes it ➝ ALU gets the operands ➝ ALU executes ➝ Result goes to destination

## what does the ALU actually do?

1. mathematical operations like:-
- Addition (A + B)

- Subtraction (A - B)

- Some ALUs support:
- 
- Multiplication

- Division

- Increment/Decrement

2. logical operations like:-
- OR

- NOT

- AND

- shift operations

3. comparison operations

- equal to 
- more than/ less than
- zero check

## how does the ALU work??
the ALU is a combinational circuit made from various component whcich are:-

- **Adders**: Full adders for arithmetic.

- **Multiplexers**: To select between operations.

- **Logic gates**: For bitwise operations.

- **Barrel shifters**: For fast shifting.

- **Status flag generators**: To set flags like Zero, Carry, Overflow, Negative.

## Flags/Status Registers (Important AF):
After an operation, the ALU updates status flags, which are essential for conditional jumps, loops, etc.

- ZF (Zero Flag): Result is zero?

- CF (Carry Flag): Carry out from MSB in unsigned ops?

- SF (Sign Flag): Result is negative?

- OF (Overflow Flag): Overflow in signed arithmetic?

## task which are not performed by a ALU

- It doesn't fetch instructions.

- It doesn’t access main memory directly.

- It doesn’t handle floating point math (that’s done by the FPU, Floating Point Unit).


