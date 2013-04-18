480-Project
===========
>>> def fib(n):                    #write the fibonacci series to n
...     a, b = 0, 1                #first number "a" = 0 and second number "b" = 1
...     while b < n:      
...             print b,           #print b as long as it's less than n
...             a, b = b, a+b      #after 1 is printed, the next number is "b" and "a+b" follows
... 
>>> fib(10000)                     #call the function
1 1 2 3 5 8 13 21 34 55 89 144 233 377 610 987 1597 2584 4181 6765      #result
>>> 
