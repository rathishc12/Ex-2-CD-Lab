# Ex-2-GENERATION OF LEXICAL TOKENS LEX FLEX TOOL
# AIM
## To write a lex program to implement lexical analyzer to recognize a few patterns.
# ALGORITHM

1.	Start the program.

2.	Lex program consists of three parts.

     a.	Declaration %%

     b.	Translation rules %%

     c.	Auxilary procedure.

3.	The declaration section includes declaration of variables, maintest, constants and regular definitions.
4.	Translation rule of lex program are statements of the form

    a.	P1 {action}

    b.	P2 {action}

    c.	…

    d.	…

    e.	Pn {action}

5.	Write a program in the vi editor and save it with .l extension.

6.	Compile the lex program with lex compiler to produce output file as lex.yy.c. eg $ lex filename.l $ cc lex.yy.c
7.	Compile that file with C compiler and verify the output.

# INPUT
```
if(a<b){
```
INPUT IMAGE :

![image](https://github.com/user-attachments/assets/0bd9d958-327c-443c-b454-81561c42a471)

# OUTPUT
FUNCTION
```
	if(
 a is an IDENTIFIER
	< is a RELATIONAL OPERATOR
 b is an IDENTIFIER
	)

 BLOCK BEGINS
```
OUTPUT IMAGE :

![image](https://github.com/user-attachments/assets/d4530b74-6a7f-4904-8a8c-eec540e13a14)


# RESULT
## The lexical analyzer is implemented using lex and the output is verified.
