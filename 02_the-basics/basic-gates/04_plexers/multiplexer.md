# what the heck is multiplexers🤔?
  
 **defination** :- "a multiplexer is a digital circuit that has 2^n inputs and has only one output."
           **explaination**:- when he questoin arrives for the multiplexer, the answer is that it is a digital circuit made  up of basic logic gates. Its main function is to to selectone input from multiple inputs and forward a single input based on the select lines.

           think of a digital switch board which manages multiple inputs and forwards single from them as per need.

---
### select lines
   as the name suggests:-
  'Select lines (or selection inputs) in a multiplexer are control inputs that determine which one of the multiple data inputs is connected to the output.'

    think these like the operator of the digital switchbaord which controlls the input which is going to be forwarded.

---

## types of multiplexers **
  
  The multiplexers are classified on the follwoing basis:-
    
 - on the basis of number of inputs.

 - on the basis of configuration/use case

 - Hierarchical / Cascaded MUXes

 ---


 **now lets study each of them in detail**

 1. **types of mux on the basis of number of input** 
        
        a multiplexer(mux) will always have number of inputs which are exponential to 2 or are multiples of 2.
        for example:-
             2=2^1
             <br>
             4=2^2
             <br>
        and so on ......
         
         based on the numbers of the inputs the mux are known as the following
  
| MUX Type     | Number of Inputs | Number of Select Lines | Output Lines |
|--------------|------------------|-------------------------|--------------|
| 2-to-1 MUX   | 2                | 1                       | 1            |
| 3-to-1 MUX   | 3                | 2                       | 1            |
| 4-to-1 MUX   | 4                | 2                       | 1            |
| 5-to-1 MUX   | 5                | 3                       | 1            |

---

## what are the select lines and how to calculate them for the mux?

  the select lines are the set of inputs that decides that which one of input should be forwarded. they
  are like a digital operator which controlls the digital switch board present.

  #### the question now arises
  **how to calculate the number of  select lines??**
    it is simple as af to calculate these select lines, the number whcich is exponential to the base 2 for the
    type of mux is the number of select lines.

    lets take an example of a 8x1 mux.
     the 4x1 mux can also be written as 2^3x1 mux do the 3 which is the exponenet for the base 2 is the  number of select lines.

     
### in this way now we know all the basics of multiplexers👏, 

