# math208-assignment-5-evaluation-of-arithmetic-expression-solved
**TO GET THIS SOLUTION VISIT:** [MATH208 Assignment 5-Evaluation of Arithmetic Expression Solved](https://mantutor.com/product/math208-programming-assignment-v-solved/)


---

**For Custom/Order Solutions:** **Email:** mantutorcodes@gmail.com  

*We deliver quick, professional, and affordable assignment help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;116045&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;MATH208  Assignment 5-Evaluation of Arithmetic Expression Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (3 votes)    </div>
    </div>
Evaluation of Arithmetic Expression

1 Description of Assignment

Design and implement efficient data structure and algorithm for the evaluation of arithmetic expressions and assignment statement.

2 Input

For the first part (arithmetic expressions) the input data includes many arithmetic expressions (E), such as “1+2∗3”, “(1+2)∗3”, etc. These expressions are defined by the grammar G = (V,T,P,E), where V = {E,T,F}, T = {a}, and P is the following rules:

1. E→E + T

2. E→E−T

3. E→T

4. T→T∗F

5. T→T/F

6. T→F

7. F→a

8. F→ (E)

In the above grammar, “a” means a constant, such as 3.14, 12, etc. Assume that all data are double in C, C++ and Java.

For the second part, in addition to the arithmetic expressions E defined above, your program should be able to handle assignment statement, such as a = (x+3)∗c. The grammar for assignment statement is ), where V ′ = {A,E,T,F}

ad P ′ is the rules defined above, plus

0. A→v = E.

Note that the variable F now includes variables. Rule 7 is replaced by the following 2 rules:

F→a

F→v

For simplicity, a variable v can only be one of the 26 lower case letters a,b,…,z. The value of a valuable in an expression comes from assignment statement. For example, if a = 3.1415926 and x = a + 2, then x = 5.1415926.

Your program needs to parse the input data in infix format. For example, if the input is a = 3.1415926, your program should first divide the input into 3 parts: “a”, “=”, and “3.1415926”, and then recognize that the input is the assignment a = 3.1415926. Any parsing method can be used. However, a simple and efficient algorithm, such as Dijkstra’s shunting yard algorithm, is preferred for this programming assignment.

For the constants, for simplicity, you can assume that they are all positive numbers.

3 Output

For each input line which contains one arithmetic expression, print out the value of the expression. For example, on input

(1 + 2) * (3 – 4) / 5

print out

-0.6 in a line. If the input is an assignment, for example,

a = 1 + 2 * 3 b = 4 * a + 5

print out

a = 7 b = 33

If a variable is used but not defined in the previous assignment, print out an error message.

Notes

The format of the report of the assignment does not need to be very formal, but it should be close to the format of a research technical report.

1. Title and author.

Include assignment number, your name, student number and email address on the first page of your report.

2. Statement of the problem.

A “formal” description of the problem in this assignment. In addition to the basic requirements specified in the assignment, emphasize the functions or features you implemented.

3. Main results.

This section should include at least the following items.

(a) Description of the design of your program and the data structures used in your program.

(b) List of your program with comments. If your program is very long, list only the main parts of the program here and the entire program in an appendix. Additional comments can be added manually to explain the design of the program.

(c) Outputs of the compilation and the executions of your program.

4. Conclusions

Give a brief summary of what you did, and interesting thing you learned from this assignment.

Additional notes:

2. The output of the program execution should indicate the correctness of your program. In other words, a set of comprehensive (but not necessarily exhaustive) annotated test data for the problem should be provided to show that your program is indeed correct. This can be done by carefully selecting a set of test data.

3. Print or write the report on A4 papers. Bind them together in the upper left corner.
