# Study Questions for Logarithmic and Exponential Complexity
## Quick Recap

A logarithmic function is the opposite of an exponential function. When you say something grows exponentially, it’s being 
multiplied. When something grows logarithmically, it is being divided. Same thing happens in the functions.

## Q1
What is the time-complexity of these code segments?

__Example 1:__
```
i = 1
N= 10000
while i<N:
  i = i*3
```
__Your answer:__ ...


__Example 2:__
```
x = n 
while x > 0: 
  y = x 
  while y > 0:
      y = y / 2 
   
  x = x / 2 
```
__Your answer:__ ...


__Example 3:__

```
x = n 
while x > 0: 
  y = x 
  while y > 0:
      y = y - 1
  x = x / 2 
```
__Your answer:__ ...


__Example 4:__ 

```
# Python program to display the Fibonacci sequence

def recur_fibo(n):
   if n <= 1:
       return n
   else:
       return(recur_fibo(n-1) + recur_fibo(n-2))

nterms = 10

# check if the number of terms is valid
if nterms <= 0:
   print("Plese enter a positive integer")
else:
   print("Fibonacci sequence:")
   for i in range(nterms):
       print(recur_fibo(i))
```
__Your answer:__
