Download Link: https://assignmentchef.com/product/solved-cs2100-tutorial-6-boolean-algebra-logic-gates-and-simplification
<br>
D1. (a) One common mistake is the following: A∙B + A’∙B’ = 1    (equation 1)  This seems to be erroneously “derived” from the following rule: X + X’ = 1  Explain why the rule is wrongly applied here.(b)  Is the following equation correct? Why?A∙B + (A∙B)’ = 1    (equation 2)

D2. Given the following two 3-variable Boolean functions:F(A,B,C) =  m(0, 2, 4, 6, 7)  G(A,B,C) =  m(1, 2, 3, 6)(a) Write the product-of-maxterms expressions in M notation for F and G.(b) If X = F + G, write the sum-of-minterms expressions in m notation for X.(c) If Y = F ∙ G, write the sum-of-minterms expressions in m notation for Y.(d) If Z = F  G, write the sum-of-minterms expressions in m notation for Z.Do you know how to generalise the above for any arbitrary Boolean functions F and G?[To make it easy for you to type in the LumiNUS forum, you may use Sum-m to meanm and Prod-M to mean M. Example: Sum-m(0, 2, 4, 6, 7), Prod-M(2, 3, 5).]

D3. How many prime implicants (PIs) and essential prime implicants (EPIs) are there in each of the K-maps? [ d(…) and D(…) denote don’t-cares. ](a)  F1(A,B,C,D) =   m(5, 8, 10, 12, 13, 14)    (b)  F2(W,X,Y,Z) =  M(0, 1, 2, 8, 9, 10)(c) F3(K,L,M,N) =   m(1, 7, 10, 13, 14) + d(0, 5, 8, 15)(d) F4(A,B,C,D) =   M(4, 8, 9, 11, 12)  D(2, 3, 6, 7, 10, 14)

D4. For each of the functions in D3 above, find the simplified POS expression. List out all alternative answers, if any.

You are encouraged to do the above discussion questions and discuss them on LumiNUS forum. These are fundamental concepts that you must know, before you attempt the tutorial questions below.Tutorial Questions:1. Name the essential theorems A, B, C and D used in the following derivation:F(j, k, m, p) =  k’  ( j’  p  (j’ + m’) )’ + ( p + k’ + j )’= k’  ( j + p’ + jm) + p’kj’ … [ A; involution ]= jk’ + k’p’ + jk’m + p’kj’ … [ distributive; commutative ]= jk’ + p’( k’ + kj’ ) + jk’m … [ associative; commutative;distributive ]= jk’ + k’p’ + j’p’ + jk’m … [ B; distributive; commutative ]= jk’ + k’p’ + j’p’ … [ associative; C ]= jk’ + j’p’ … [D ]Note: In writing out terms, you should write the literals in the order of significance, especially in your final answer. For instance, for the above Boolean function F(j, k, m, p), you should write the final answer as jk’ + j’p’ and not k’j + j’p’ or jk’ + p’j’.

2. Using Boolean algebra, simplify each of the following expressions into simplified sumof-products (SOP) expressions. Indicate the law/theorem used for each step.(a) F(x,y,z) = (x + y∙z’)∙(y’ + y)  + x’∙(y∙z’ + y)(b) G(p,q,r,s) =  M(5, 9, 13)Tip: For (b), it is simpler to start with the given expression and get done in 5 steps, rather than to expand it into sum-of-products/sum-of-minterms expression first.

m0

3. (a) The following K-map layout is used for a 4-variable Boolean function T(A,B,C,D). Fill in the minterm positions m1 to m15 into the respective cells. m0 has been filled for you.

(b) Given the following 4-variable Boolean function:T(A,B,C,D) = M(1,2,3,6,10,14)  X(5,8,11,13,15)where X’s are the don’t-care conditions, write out the m notation for T(A,B,C,D).(c) Draw the K-map for T using the layout above.(d) What is the simplified SOP expression for T? List out all alternative solutions.(e) What is the simplified POS expression for T? List out all alternative solutions.(f) Implement the simplified SOP expression for T using a 2-level AND-OR circuit or a 2level NAND only circuit, assuming that primed literals are not available.Note: Always assume that prime literals are not available unless otherwise stated.

4. A circuit takes in four inputs K,L,M,N and generates 3 outputs X,Y,Z as follow:X(K,L,M,N) = 1 if KL = MN, or 0 otherwise,where KL and MN are 2-bit unsigned integers.Y(K,L,M,N) = 1 if KL  MN, or 0 otherwise,where KL and MN are 2-bit unsigned integers.Z(K,L,M,N) = 1 if KLM &lt; LMN, or 0 otherwise,where KLM and LMN are 3-bit unsigned integers.Assume that the input 0000 will not occur.(a) Fill in the truth table for the circuit. Write ‘d’ for don’t cares.(b) Fill in the K-maps of X, Y and Z using the layout given below.

(c) Write out the simplified SOP expressions of X, Y and Z.(d) After designing the circuit according to the simplified SOP expressions in (c), if you feed the input 0000 into it, what will be the outputs?


