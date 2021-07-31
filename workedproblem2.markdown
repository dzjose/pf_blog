---
layout: page
title: Worked Problem 2
permalink: /workedproblem2/

---

`8) Find the solution to the recurrence relation a_n= −2a_n−1 + 8a_n−2 
with initial terms a_0=9 and a_1=12.`

---

`The underscore _ symbol is a symbol for a subscript.`
For starters, given a recurrence relation, you want to make it equal to 0. For example a_n + αa_n−1 + βa_n−2 = 0.
You then turn the recursive relation into a polynomial with the characteristic equation `x^2+ax+b`.

Recursive relation: a_n + 2a_n-1 - 8a_n-2 = 0
With the characteristic equation, we get a polynomial of (x^2 + 2x + -8)= 0 then solve for x to end up with x = -4,2 
With this, we now have our characteristic roots. We therefore know that the solution to the recurrence 
relation will have the form of `a_n = a(-4)^n + b(2)^n`. To find a and b, plug in  n=0  and  n=1 to get 
a system of two equations with two unknowns: 9 = a-4^0 + b2^0 = a+b      
                                             12 = a-4^1 + b2^1 = -4a+2b
By solving the systems of equation we then find that a=1 and by plugging a=1 into the first unknow equation (9=a+b)
we can find b=8. Lastly, by the Characteristic Root Technique for Repeated Roots a_n=ar^n + bnr^n we get
`a_n = -4^n + 8(2)^n`
