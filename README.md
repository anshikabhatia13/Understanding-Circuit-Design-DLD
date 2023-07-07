# Understanding-Circuit-Design-DLD

#PART 1 Basic CKTS
Functions:
F1=F(w, x, y, z) = m(0, 2, 4, 5, 6, 7, 8, 10, 13, 15) <br />  
F2=F(a,b,c,d) = M(4,7,8,11).D(1,2,13,14)<br /> 
F3=A’BC’ + ABC’ + AB’C’ + A’B’C + AB’C + ABC<br /> 
F4=(A+B)(A+C)(A+B’+C)(A+B+C) <br /> 
F5=(a’+b’c’+b’c+d’)((a’b+c’d)+ab’+c’d’)ab’+(d+ac(bd’+ bd))<br /> 


1. Realize the above functions (F1-F5) using gates. You need to check with the different test-cases in the circuit-verse.
(Hint: For SOP: AND-OR, POS: OR-AND, MIX: neither.) <br /> 
2. Realize the question-1 circuits using only NAND gates i.e, F1, F3, F5 . You need to check with the different test-cases in the circuit-verse.	 <br /> 						
3. Realize the question-1 circuits using only NOR gates i.e, F2, F4, F5. You need to check with the different test-cases in the circuit-verse.			<br /> 			
4. Realize the circuits from question-2 and 3 using only 2-input gates for (F1-F5). You need to check with the different test-cases in the circuit-verse.	<br /> 			
5. Realize the circuits from question-1 (F1-F5). You need to check with the different test-cases in the circuit-verse.<br /> 

For each of the above expressions, what is the minimum FAN-IN for realizing a 2 level circuit.<br /> 
For each of the above expressions, what is the minimum number of levels required, when using the utmost 3 FAN-IN gates?<br /> 

#PART 2 MuX DeMuX
<br /> 
1. Design the following multiplexers using only NAND gates.<br /> 
Design a 2x1 mux <br /> 
Design a 4x1 mux<br /> 
Design a 8x1 mux<br /> 
2. Design a 32x1 mux using the hierarchical approach by using the below mux models. Use the base mux as a 2x1 model. <br /> 
Use only 4x1 mux (2 points)<br /> 
Use only 8x1 mux (2 points)<br /> 
						
3. Realize the given two boolean expressions using a multiplexer <br /> 
BE1: F(U, V, W, X) = (UV’ + U’V)W’<br /> 
BE2: F(U, V, W, X, Y) = m(0, 2, 4, 7, 8, 10, 12, 14, 16, 18, 20, 23, 24, 25, 26, 27, 28) <br /> 
a. Straight-forward approach ( based on the number of input variables)<br /> 
b. Limitations on type of mux. Use a mux with the number of select lines that is at least one less than the number of variables in the expression. <br /> 

4. Realize the below two boolean expressions using a de-multiplexer.  <br /> 
BE1: F(U, V, W, X) = (UV’ + U’V)W’<br /> 
BE2: F(U, V, W, X, Y) = m(0, 2, 4, 7, 8, 10, 12, 14, 16, 18, 20, 23, 24, 25, 26, 27, 28) <br /> 
a. Straight-forward approach ( based on the number of input variables)<br /> 
b. Limitations on type of mux. Use a demux with the number of select lines that is at least one less than the number of variables in the expression. <br /> 

