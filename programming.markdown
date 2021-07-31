---
layout: page
title: Programming
permalink: /programming/

---
# Factorials

<https://github.com/dzjose/project/blob/main/Programming>
{% highlight ruby %} #Python code to compute factorials

number = eval(input("Enter a non-negative intiger to take the factorial of: "))

product = 1
for i in range(number):
	product = product * (i+1)
    
print ("The factorial is : ",end="")
print (product) {% endhighlight %} 

# Recursions

<https://github.com/dzjose/project/blob/main/Programming%20Simple%20Recursions>
{% highlight ruby %} def fun(k, n = 0, arr = []):
  
  	
    if n == k:
    	return
    
    else:
      	arr.append(n)
        fun(k, n+1, arr)
        
	return arr
#type function value for n
print(fun(26)) {% endhighlight %}







  
