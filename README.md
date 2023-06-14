# My-python-projects
## Introduction
This is a compilation of all my Python solution during the course of my learning.


## Task 1 - A Python function to find the max of three numbers.

_1. To begin, one should be able to input the values for the given variables, which can be achieved with the following codes:_
  
   a = int(input ('Enter the first value: '));

   b = int(input ('Enter the second value: '));

   c = int(input ('Enter the third value: '));

_2. Afterwards, the function named maximum with the arguments comes in:_
   
   def maximum (a, b, c):

_3. Then, the conditional statements are used to get the largest value:_

       
    if (a >= b) and (a >= c):
       largest = a
 
    elif (b >= a) and (b >= c):
        largest = b
    else:
        largest = c
         
    return largest
    
   _4. Finally, the largest value is printed out:_
   
    print (maximum(a, b, c))
    
    
    
## Task 2 - A Python function to sum all numbers in a list.
    
_1. To begin, it is required that the function is defined which is defined as as sum and argument as numbers:_
  
  def sum (numbers):
   

_2. Furthermore, iteration is required which is first initialized to 0, making use of the FOR LOOP_
   
   total = 0
  
  for x in numbers:
  
  total +=x
    
_3. Then, value is returned_
   
   return total
    
_4. Output is printed out_
 
 print (sum(numbers))
    
  



![Here is the link to the script of the solutions](http://localhost:8888/notebooks/Untitled14.ipynb?kernel_name=python3#)
