# 4bit-ALU
4 BIT ARITHMETIC AND LOGICAL UNIT
Theory:-
                Arithmetic Logic Unit is a common operational unit with a number of storage registers connected to it, using which it performs microoperations. To perform a micro operation, of the common ALU. The ALU performs an operation and the result of the operation is then transferred to a destination register. The ALU is a combinational circuit  
so that the entire registers transfer operation from the source register through the ALU and the destination register can be performed during one clock pulse period.                  



Arithmetic Unit:-
                The arithmetic operations in the table can be implemented in one composite arithmetic circuit. The basic component of an arithmetic circuit is a fulladder. By controlling the data input to the adder it is possible to obtain different types of arithmetic operations. The diagram of the 4-bit arithmetic circuit is shown in figure. It has four full adder circuits that constitute the 4-bit adder and 4 multiplexers for choosing multiple operations. There are two 4bit inputs A and B and 4-bit output D.

Logic Unit:-
                 Logic micro operations specify binary operations for strings of bits stored in registers. These operations consider each bit of registers separately and treat them as       
binary variables. Figure-2 shows one stage of a circuit that generates the four basic logic micro-operations. It consists of 4 gates and a multiplexer each of the four logic operations is generated through a gate that performs the required logic. The outputs of the gates are applied to the data inputs of the multiplexer. The two selection inputs S1 and S2 choose one of the data inputs of the multiplexers and direct it values to the output. The figure shows one typical stage of the logical unit.
A and B are the 4 bit word inputs ALU A3, A2, A1, A0 and B3, B2, B1, B0 are the bits. A3 and B3 are the MSBs. S2, S1, S0 are the selection inputs. S2 selects the arithmetic operation for ‘0’ and logic operation for ‘1’. S1, S0 are used to select various operations in arithmetic and logic blocks. Cin is the input carried to the arithmetic circuit. f3,f2,f1,f0 are the output bits . Cout is the output carry.
