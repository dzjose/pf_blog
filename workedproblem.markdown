---
layout: page
title: Worked Problems
permalink: /workedproblems/

---

`15) How many positive integers less than 975 are multiples
of 9, 5, or 2? Use the Principle of Inclusion/Exclusion.`

---

/A∪B∪C/=/A/+/B/+/C/−/A∩B/−/A∩C/−/B∩C/+/A∩B∩C/ This formula is used for finding the cardinality of the sets.
This method also accounts for any overcounting by subtracting the intersection of a pair of sets. By subtracting 
the intersection you also remove elements that appear in all three sets at once. This is then added back at the
end of the formula.


∪ = The symbol for a union of sets.
∩ = The symbol for the intersection of two sets, which can also be read as all elements which are elements of both A and B.


`15)` Firstly, you need to find how many numbers less than 975 are multiple of 9,5,and 2. You do this by dividing 975 by 9, 
which gives you 108. You can call this set A. Similarly, you divide 975 by 5 to find set B. You also divide 975 by 2 to
get set C.

Secondly, to find the combinations to be multiple of 9 and 5 you multiply the two to get 45. Then, you divide 975 by what you
get for the multiples of both sets. You follow the same rule for the remaining combinations of sets.

(/A/= 975/9 =`108`) (/B/= 975/5 =`195`) (/C/= 975/2 =`487`) (/A∩B/=975/45=`21`) (/A∩C/=975/18=`54`) (/B∩C/=975/10=`97`) 
(/A∩B∩C/=975/90=`10`)

Lastly, you use the formula for Principles of Inclusion/Exclusion that is above.

108 + 195 + 487 - 21 - 54 - 97 + 10 = `628`

`There are a total of 628 positive integers less than 975 that are multiple of 9,5,or 2.`










