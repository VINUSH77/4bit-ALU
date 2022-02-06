# 4bit-ALU
Title:- **4 BIT ARITHMETIC AND LOGICAL UNIT**

**This Repository Present the Design of a 4-bit ALU**

1.[Abstract]()

2.[Circuit Details]()

3.[Circuit Design]()

4.[Waveforms]()

5.[References](https://github.com/VINUSH77/4bit-ALU)




**Theory:-**

   Arithmetic Logic Unit is a common operational unit with a number of storage registers connected to it, using which it performs microoperations. To perform a micro operation, of the common ALU. The ALU performs an operation and the result of the operation is then transferred to a destination register. The ALU is a combinational circuit  
so that the entire registers transfer operation from the source register through the ALU and the destination register can be performed during one clock pulse period.                  
![theory](https://user-images.githubusercontent.com/90974601/152669938-27eb9778-3b1f-4a01-9e27-ec930e90d271.jpeg)



**Arithmetic Unit:-**

   The arithmetic operations in the table can be implemented in one composite arithmetic circuit. The basic component of an arithmetic circuit is a fulladder. By controlling the data input to the adder it is possible to obtain different types of arithmetic operations. The diagram of the 4-bit arithmetic circuit is shown in figure. It has four full adder circuits that constitute the 4-bit adder and 4 multiplexers for choosing multiple operations. There are two 4bit inputs A and B and 4-bit output D.


![arithmetic](https://user-images.githubusercontent.com/90974601/152670019-457c8667-3b29-42bf-8c20-ba23f7c5de26.jpeg)

              
**Logic Unit:-**

   Logic micro operations specify binary operations for strings of bits stored in registers. These operations consider each bit of registers separately and treat them as
binary variables. Figure-2 shows one stage of a circuit that generates the four basic logic micro-operations. It consists of 4 gates and a multiplexer each of the four logic operations is generated through a gate that performs the required logic. The outputs of the gates are applied to the data inputs of the multiplexer. The two selection inputs S1 and S2 choose one of the data inputs of the multiplexers and direct it values to the output. The figure shows one typical stage of the logical unit.A and B are the 4 bit word inputs ALU A3, A2, A1, A0 and B3, B2, B1, B0 are the bits. A3 and B3 are the MSBs. S2, S1, S0 are the selection inputs. S2 selects the arithmetic operation for ‘0’ and logic operation for ‘1’. S1, S0 are used to select various operations in arithmetic and logic blocks. Cin is the input carried to the arithmetic circuit. f3,f2,f1,f0 are the output bits . Cout is the output carry.


![logic](https://user-images.githubusercontent.com/90974601/152670041-31c5f78a-14c4-4ab8-9791-666fe4c5e2fc.jpeg)


**Circuit diagram:-**


![cd1](https://user-images.githubusercontent.com/90974601/152670176-32f4745b-ed5e-456c-98e9-94a9b76236c9.jpeg)


![cd2](https://user-images.githubusercontent.com/90974601/152670187-cf4451e5-903b-4093-b23a-c269bd3b3e6e.jpeg)


![cd3](https://user-images.githubusercontent.com/90974601/152670198-153df4f2-4555-4a5f-98a3-f44c7a53adec.jpeg)


![cd4](https://user-images.githubusercontent.com/90974601/152670203-406f3268-54cc-4534-a535-c0e5d94ce008.jpeg)


![cd5](https://user-images.githubusercontent.com/90974601/152670210-e89ad1cc-ba3b-4efd-a935-43794f712975.jpeg)



**Simulation Results:**


![sr](https://user-images.githubusercontent.com/90974601/152670319-050d6020-ff4c-43f8-afbd-43f1c4eee4b5.jpeg)



**NGSPICE PLOTS:**



![ng](https://user-images.githubusercontent.com/90974601/152670340-608a2021-6d5e-4075-b344-0056ec1178f2.jpeg)


![ng2](https://user-images.githubusercontent.com/90974601/152670352-7ee6caf4-1bd6-472a-afe5-f4b738d9fec4.jpeg)




**PYTHON PLOTS:**


![python](https://user-images.githubusercontent.com/90974601/152670357-ad59a8c3-5521-48ec-bb36-ccf8d6972235.jpeg)


![python2](https://user-images.githubusercontent.com/90974601/152670366-e4254d18-d578-4735-9abf-804a682996a6.jpeg)


**OUTPUT:**

when S2 = ‘ 0 ‘ -- v9 = 0v

     S1 = ‘ 1 ‘ -- v10 = 5 v 
           
     S0 = ‘ 0 ‘ -- v11 = 0v 
           
     Cin = ‘ 1 ‘ -- v12 = 5 v
           
operation performed is SUB

F= A-B

F[ 3 : 0] – 1 1 1 1 Cout = ‘ 0 ‘



**Result:-**

![result](https://user-images.githubusercontent.com/90974601/152670570-38385f96-3544-4136-ba98-c5eb62755027.jpeg)


#References
**References:-**

International Journal of Engineering Research & Technology
(IJERT)ISSN: 2278-0181 IJERTV9IS070238
(This work is licensed under a Creative Commons Attribution
4.0 International License.)

