---
layout: page
title: Worked Problem 2
permalink: /workedproblem2/

---

`8) Find the solution to the recurrence relation a_n= −2a_n−1 + 8a_n−2 
with initial terms a_0=9 and a_1=12.`

---

The underscore _ symbol is a symbol for a subscript.
For starters, given a recurrence relation, you want to make it equal 0. For example a_n + αa_n−1 + βa_n−2 = 0.
You then turn the recursive relation into a polynomial x^2+αx+β α=a constant, β=b constant.

Recursive relation: a_n + 2a_n-1 - 8a_n-2 = 0
With the characteristic equation, our polynomial will look like (x^2 + 2x + -8)= 0 by solving for x, you end up with x = -4,2 
With this, we now have our characteristic roots. We therefore know that the solution to the recurrence 
relation will have the form of a_n = a(-4)^n + b(2)^n To find  a  and  b,  plug in  n=0  and  n=1 to get 
a system of two equations with two unknowns: 9 = a-4^0 + b2^0 = a+b      
                                             12 = a-4^1 + b2^1 = -4a+2b
By solving the systems of equation we then find that a=1 and by plugging a into the first unknow equation
we can find b=8. Lastly, by the Characteristic Root Technique for Repeated Roots a_n=ar^n + bnr^n we get
`a_n = -4^n + 8(2)^n`
