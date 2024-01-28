The file consists of a Program that simulates the overal process of a Digital circuit that Functions as a 1 bit processor;
the file contains Class of 2 models of 1 bit processor each having a slightly different instruction format than other;
The instruction format is given as : id/i/rw//ALD/Ai//Address(3)//ALUCtrl(3)[//for processor 1];: id/i/rw//ALD/Ai/AD//Address(3)//ALUCtrl(3)[//for processor 2];
id(input director),i(input value),rw(read write toggle),ALD(accumulator load toggle),Ai(accumultor input),AD(accumulator director),Address(memory address),ALUCtrl(ALU output selector)
the Processor contains 7 memory register and 1 accumulator; 
the instruction input design is not completely abstracted as we can see each bit is independent of other in most places ... this format can be further reduced to a 7 bit format. 
THis is an implimentation of a Circuit into C program.. But the Core Motive of this project is to develope an algorithm for this machine to perform a 2 bit addition and also Multiplication using only the given Space and binary Functions;
