# Assignment-2
assignment 2
What are the Boolean data type's two values? How do you go about writing them? Answer:-- The Boolean type has only two values: true and false the value are represented by 1 and 0 respectively. Integers and floating-point numbers can be converted to the Boolean data type using Python's bool() function.
What are the three different types of Boolean operators?
Answer:-- The three different Boolean operators are AND, OR and NOT

Make a list of each Boolean operator's truth tables (i.e. every possible combination of Boolean values for the operator and what it evaluate ).
Answer:-- X Y NOT X( ~ X ) X AND Y( X && Y ) X OR Y( X || Y ) false false 1 0 0 false true 1 0 1 true false 0 0 1 true true 0 1 1

What are the values of the following expressions?
(5 > 4) and (3 == 5) not (5 > 4) (5 > 4) or (3 == 5) not ((5 > 4) or (3 == 5)) (True and True) and (True == False) (not False) or (not True)

Answer:: (5 >4) and (3 == 5) false not (5 >4) false (5 >4) or (3 == 5) true not ((5 >4) or (3 == 5)) false (True and True) and (True == False) false (not False) or (not True) true

What are the six different types of reference operators? • == • != • < • > • <= • >=
How do you tell the difference between the equal to and assignment operators?

Answer: The assignment operator(=) just assigns the value in expression to variable . in equal operator (==)it checks the condition if it’s true or false.

Describe a condition and when you would use one.
The condition like if , else , switch statements are conditional statement when we have to compare more than one value for a argument.

Recognize the following three blocks in this code:
spam = 0 if spam == 10: print('eggs') if spam > 5: print('bacon') else: print('ham') print('spam') print('spam')

Answer:- hamspamspam

Create a programme that prints. If 1 is stored in spam, prints Hello; if 2 is stored in spam, prints Howdy; and if 3 is stored in spam, prints Salutations! if there's something else in spam.
                              if(spam==1)
                                   print(“Hello”)
                               elif(spam==2)
                                   print(“prints Howdy”)
                                elif(spam==3)
                                   print(“Salutations!”)
10.If your programme is stuck in an endless loop, what keys can you press? Answer:- Ctrl+C
How can you tell the difference between break and continue? Break statement mainly used to terminate the enclosing loop such as while, do-while, for or switch statement wherever break is declared. Continue statement mainly skip the rest of loop wherever continue is declared and execute the next iteration.
In a for loop, what is the difference between range(10), range(0, 10), and range(0, 10, 1)? The difference between all 3 is that in first the end is specified only , in second func only start and end is specified ,in third start end and the steps is specified

Using a for loop, write a short programme that prints the numbers 1 to 10 Then, using a while loop, create an identical programme that prints the numbers 1 to 10.

for(i=1;i<=10;++i)
    print(i)
while(i<=10)

    print(i)
         ++i
If you had a bacon() function within a spam module, what would you call it after importing spam?

import spam spam.bacon()
