# A full adder, what is it??
  A **full adder** is a digital circuit which adds intotal 3-bits, which are two significant bits from  inputs and a 
  carry bit. Unlike **half adder** the full adder also includes the carry making a complete addition with carries possible.

  ## forging of full adder
  for creating a _full adder_ we will need the following components
     ✅2X XOR gates
     ✅2X AMD gates
     ✅1X OR gate

## circuit diagram 
 ![sorry!]()
  ## circuit flow of this circuit
   Let’s say your inputs are A, B, and the carry is Cin
        
      1>  First XOR: A ⊕ B

      2>   Second XOR: (A ⊕ B) ⊕ Cin → gives you the Sum

      3>  First AND: A ⋅ B

      4>  Second AND: (A ⊕ B) ⋅ Cin

        OR: Carry-out = (A ⋅ B) + ((A ⊕ B) ⋅ Cin)