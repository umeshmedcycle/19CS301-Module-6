# 19CS301-Module-6
EX: 6.1   POLYMORPHISM

### AIM: 

To create two classes: Lion and Giraffe, each defining a method named type() differently, and to demonstrate how objects from each class respond to the same method name with different behaviors.

### ALGORITHM:
Step 1: Create a class Lion.
      

Step 2: Create another class Giraffe.


Step 3: Define a generic function func(obj).
       

Step 4: Create objects of both Lion and Giraffe.


Step 5: Call the func() function for each object and observe the output.


Step 6: Terminate the program.

### PROGRAM:
```
class Lion:
    def type(self):
        print("carnivore")
class Giraffe:
   def type(self):
        print("herbivore")

obj_lion=Lion()
obj_giraffe=Giraffe()

obj_lion.type()
# returns carnivore
obj_giraffe.type()
```
### OUTPUT:
![image](https://github.com/user-attachments/assets/ddf413c5-6551-4965-8f6e-07262304de8d)



### RESULT: 

Thus, the program has been successfully executed.

EXP.No: 6.b OPERATOR OVERLOADING

### AIM: 

write a python program to overload less than operator
###ALGORITHM:
Step1 :create class A and def init	 

Step2: def it	with a condition if self.a < o.a 

Step 3: call the function and execute the program.
### PROGRAM:
```
class A :
     def     init (self,a):
             self.a=a
     def     lt (self,o):
              if self.a < o.a :
                   return "ob1 is less than ob2"
              else:
                   return "ob2 is less than ob1"
ob1 = A(2)
ob2 = A(3)
print(ob1<ob2)
```
###OUTPUT:
![image](https://github.com/user-attachments/assets/417f1463-1dc4-423e-a4db-82ceb9dadfd1)



###RESULT: 
    
    
Thus, the program has been successfully executed.



EX: 6.3 ABSTRACT CLASS METHOD

### AIM: 

To Create the abstract method calculate_area which is of the abstract class 'Shape'

### ALGORITHM:
Step1:Get input from the user

Step2:put class function to define the function using self

Step3:By using the function to find the area of the rectangle and circle 

Step4:Execute the program.

### PROGRAM:
```from abc import ABC
class Shape(ABC):
            def calculate_area(self):
                Pass
class Rectangle(Shape):
               length = 5
               breadth =3
               def calculate_area(self):
                   print("Area of a rectangle:",self.length * self.breadth)
class Circle(Shape):
             radius = 4
             def calculate_area(self):
                     print("Area of a circle:",3.14 * self.radius * self.radius)
a=Rectangle()
b=Circle()
a.calculate_area()
b.calculate_area()
```
### OUTPUT:
![image](https://github.com/user-attachments/assets/0cadc313-4f13-40b9-b3e0-6afa5e5f449b)



### RESULT: 

Thus, the program has been successfully executed.

EXP.No: 6.4     ENCAPSULATION
### AIM: 


To Implement Encapsulation using private members –of a class rectangle with private variables length,width.
###ALGORITHM: Step1: put class function to define the function using self Step2: By using the function to find the area of the rectangle Step3: Execute the program.
###PROGRAM:
```
class Rectangle:
 	length = 0
 	breadth = 0
  def	init	(self):
       self.	length = 5
       self.	breadth = 3
  print(self.	length)
  print(self.	breadth)
rect = Rectangle()
```
### OUTPUT:
![image](https://github.com/user-attachments/assets/3b4f3e8c-aa9c-4bbf-9c72-a149e7747c21)

 

### RESULT: 

Thus, the program has been successfully executed




