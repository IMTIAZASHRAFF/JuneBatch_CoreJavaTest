1)  Create a package called “ javaleads.lesson1”
2)  Create a class called "Vehicle" under the package created in question#1. The class should have private member variables type,capacity of appropriate data types. This class should have member method "printVehicalDetails" and another method "runVehiclel"
3)  Create a package called “javaleads.lesson2”
4)  Create an abstract class called “Vehicle” under the package “javaleads.lesson2”. The abstract class should have private member variables “type” and “capacity” of appropriate data types. This abstract class should have an abstract method”runVehical” and a proper method call “printVehicleDetails”
5)   Create a child class “Car” and extend the abstract class “Vehicle”.
Add new private member variable “engineCount”.Override the method “printVehicleDetails” in the child class and make a call to parent method using keyword ”super”.Implement the method “runVehicle”
6)  Create a child class “Boat” and extend the abstract class “Vehiclel”.
Add new private member variable “engineCount”.
Override the method “printVehicleDetails” in the child class and make a call to parent method using keyword ”super”.
Implement the method “runVehicle”
7) Create an interface called “product”. This interface should have following
A  method named  addStock that returns total stock statistics . The method accepts two parameters productname and quantity     

8) What is a Class and what is an Object?
9) What is a constructor and what are their types ?
10) Write the code for a public default constructor for a class called " Office "
11) What does the implements keyword do?
12) What three places is the final keyword used in?
13) Name the 4 concepts of object-oriented Programming
14) What is the first thing that runs when a class is instantiated?
15) a) when a method is overloaded ,is it in the same class,or a different class?
   b) can it have the same Parameters
16) What is the different between Interface & Abstract ?
17) what does the void keyword mean? Where is it used??
18) What is overloading? How is it done?
19) How do you override a static method in java?
20) Write a for each loop(also called Enhanced for loop)Which iterates over a collection called “allVehicles” which contains objects of type “Vehicle”.
21) a)What are access modifiers in Java?
    b)What is the difference between a local variable and an instance variable?
22)  a) Differentiate between the constructors and methods in Java?
     b)What is the difference between this() and super() in Java?
23) What is method overloading and method overriding?With Example Program  

24) Encapsulation : Create a package called “com.exam.encapsulation”.

Create a class called student with following properties/fields with
getter setters.

Student Name
Student Age
Department

  Create a StudentDetails class with main method. Create a new
student object and assign name , age and department. Print out these
details with System.out.println().


25) Create a interface called fruit with 2 methods isSweet and
isPoisonous. Create 2 classes called Apple and PoisonBerry which
implement this interface and override the methods.
Create a Main Method to create objects for apple & PoisonBerry to get the result


26) Create a class called Department. It should have 3 constructors.  it
will have 3 properties/fields deptName, id, location.

1st constructor does not take any arguments.
2nd constructor takes dept name and id as parameters.
3rd constructor takes leapt name , id and location as parameters 
Pass the Parameters Values and Print the result

27) FizzBuzz Program
  given number n .. print the values from 1 to n 
  if the number is multiple of 3 print fizz
  if the number is multiple of 5 print buzz
  if the number is multiple of both 3 and 5 print fizzbuzz
  otherwise print the number itself
  ##21. Create package called “com.exam.exceptions”.

28) Create 3 custom exceptions  classes called NumberTooLargeException and
NumberTooSmallException and ZeroNumberException
write a class called ExceptionExample with main method. Accept a
number from user and print “Allocated Memory” if the number is less than or equal to 10000. Or
throw NumberTooSmallException if number is negative and
NumberTooLargeException if number is bigger than 10000. and ZeroNumberException if number is zero

29) creating a custom exception class with name AgeDoesnotMatchException.Another class Student contains two private variables name, age and, a parameterized constructor which initializes the instance variables.
Form the main method we are accepting name and age values from user and initializing Student class by passing the accepted values.
In the constructor of the Student class we have created an object of the exception AgeDoesnotMatchException and raised the exception (using throws) if the age value is between 17 and 24.  Output : On executing this program, you need to pass name and age values from keyboard. If the given age value id not between 17 and 24 then exception occurs

30) An Interface named Company has the following methods

- Void assignSalaries(int[] salaries);
- Void averageSalary();
- Void maxSalary();
- Void minSalary();

Create 2 classes EngineerFirm and AccountantFirm that implement the Company Interface. The details of these classes follow

a). Class EngineerFirm should have variable type int[] income it should implement the following methods.
    1. EngineerFirm(int n)
        1. Initialize that empty array income of length n where n is the number of engineers.
    2. Void assignSalaries(int[] salaries) Assigns the salaries in array salaries to income array.
        1. If the number of elements differ then throw exception that the salaries do not match employees.
    3. Void maxSalary() : this function will calculate the max salary in that firm. 
    4. Void minSalary(): this function will calculate the min salary in that firm.

b). Class AccountantFirm should have variable type int[] income it should implement the following methods.
    1. AccountantFirm(int n)
        1. Initialize that empty array income of length n where n is the number of Accountants.
    2. Void assignSalaries(int[] salaries) Assigns the salaries in array salaries to income array.
        1. If the number of elements differ then throw exception that the salaries do not match employees.
    3. Void maxSalary() : this function will calculate the max salary in that firm. 
    4. Void minSalary(): this function will calculate the min salary in that firm.



