# What is the Context:

## This 

* always dynamic
* indicates the object in the context of which it is called
* related with element to the left of the point 

## Bind

* let object borrow a method from another object
* move context to current object
* return the function without calling it

## Call

* the same as **[bind](#bind)**
* **BUT** call directly

## Apply 
* the same as **call**
* **BUT** with only 2 parametres

# CASE

Create a function that returns multiplication of each element of the object by the number N.

1. Refer to the parent element - Array 
2. Use .prototype to create a function
3. Use keyword This and method Map - this.map
