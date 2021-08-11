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

# Permutations

{% highlight ruby %} def perm1(lst):
	if len(lst) == 0:
		return []
	elif len(lst) == 1:
		return [lst]
	else:
		l = []
		for i in range(len(lst)):
			x = lst[i]
			xs = lst[:i] + lst[i+1:]
			for p in perm1(xs):
				l.append([x] + p)
		return l
data = list('abc')
print ('perm1')
for p in perm1(data):
    print (p) {% endhighlight %}







  
