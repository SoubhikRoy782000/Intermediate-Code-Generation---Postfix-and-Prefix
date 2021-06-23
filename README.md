# Intermediate-Code-Generation---Postfix-and-Prefix

Aim - 

To implement Intermediate code generation – Postfix and Prefix

Algorithm –

Step 1 – Declare set of operators. 
Step 2 – Initialize an empty stack. 
Step 3 – To convert INFIX to POSTFIX follow the following steps 
Step 4 – Scan the infix expression from left to right. 
Step 5 – If the scanned character is an operand, output it. 
Step 6 – Else, If the precedence of the scanned operator is greater than the precedence of the 
operator in the stack (or the stack is empty or the stack contains a ‘(‘ ), push it.
Step 7 – Else, Pop all the operators from the stack which are greater than or equal to in precedence than that of the scanned operator. After doing that Push the scanned operator to the 
stack. 
Step 8 – If the scanned character is an ‘(‘, push it to the stack. 
Step 9 – If the scanned character is an ‘)’, pop the stack and output it until a ‘(‘ is encountered, and discard both the parenthesis. 
Step 10 – Pop and output from the stack until it is not empty. 
Step 11 – To convert INFIX to PREFIX follow the following steps 
Step 12 – First, reverse the infix expression given in the problem. 
Step 13 – Scan the expression from left to right. 
Step 14 – Whenever the operands arrive, print them. 
Step 15 – If the operator arrives and the stack is found to be empty, then simply push the operator into the stack. 
Step 16 – Repeat steps 6 to 9 until the stack is empty.
