# -Operator-and-Loops

1. What are the Conditional Operators in Java?
Ans: They aJe used when a condition compJises more than one boolean expression. For instance/ if we want to
print a number only if it is greater than 2 and less than 5/ then we will use conditional operators to combine the
2 expressions. We have 3 types of conditional operators - logical-and/ logical-or and ternary operator.
Logical-and operator (&&)
It is used when we want the condition to be tJue iff both the expressions are true.

Syntax
if(condition - 1 && condition - 2) {
statement;
}

Logical-or operator (||)
This operator is used when we are satisfied as long as any one of the boolean expressions is evaluated as true.
Syntax
if(condition - 1 || condition - 2) {
statement;
}

Ternary operator (?:)
It is a smalleJ veJsion foJ the if-else statement. If the condition is tJue then the statement - 1 is executed else the
statement - 2 is executed.
Syntax
condition ? statement - 1  statement - 2;

2. What are the types of operators based on the number of operands?
Ans: TheJe aJe thJee types of opeJatoJs in java based on the numbeJ of opeJands. They aJe
. Unary operator
. Binary operator
. Ternary operator
.
3. What is the use of Switch case in Java programming?
Ans: Switch statement
The switch case in java is used to select one of many code blocks for execution.
Break keyword: As java reaches a break keywoJd/ the control breaks out of the switch block. The execution of
code stops on encountering this keywoJd/ and the case testing inside the block ends as the match is found. A
lot of execution time can be saved because it ignores the rest of the code's execution when there is a break.
Default keyword The keyword is used to specify the code executed when the expression does not match any
test case.
The switch case in Java works like an if-else laddeJ/ i.e./ multiple conditions can be checked at once. Switch is
provided with an expression that can be a constant oJ literal expression that can be evaluated. The value of the
expression is matched with each test case till a match is found. If theJe is no match/ the default keyword/ if
specified- the associated code executes. Otherwise/ the code specified for the matched test case is executed.

4. What are the priority levels of arithmetic operation in java ?
Multiplication, division and remainder operations are applied first. If an expression contains several such operations,
they're applied from left to right. Multiplication, division and remainder operators have the same level of precedence.

5. What are the conditional Statements and use of conditional statements in java ?
Conditional statements in Java are used to make decisions based on certain conditions. 
The most common conditional statements in Java are the If-Else statement, the Switch statement, and the Ternary Operator.
These statements allow the program to execute different blocks of code based on specific conditions.

6. what is the syntax of if else statement in java ?
Syntax of If else...if statement in Java
if (condition) { //Statements set 1 } else if (condition 2) { //Statements set 2 } . . . else { //Statements to be executed if no condition is satisfied. }

7. What are the 3 types of iterative statements in java?
   The various iteration statements in Java are
   for statements,
   while statements,
   do-while statements.
8. Difference between for loop and do while loop  ?
 For loop is use when we know the number of iterations means where the loop will terminate. While loop is use when we don't know the number of iterations means where the loop will terminate. Do while loop is use when we don't know the number of iterations means where the loop will terminate   
   
