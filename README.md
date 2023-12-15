Object oriented programming
1.a 
The concept inheritance is a fundamental aspect, which falls under object-oriented programming. In which each object in a Python program has properties and methods to represent different data types. For an instance when a parent has a biological child. The child inherits certain attributes from their parents, including genes, physical and other characteristics. In order to demonstrate inheritance creating a Python code for inheritance.  (Appendix 1.a)
 
Figure 1 Creating a parent and child class
Taking the previously mentioned example, inheritance in OOP involves the same principle, where the parent class properties and methods can be inherited by any child classes. The above Python code a parent class is created under ‘Vehicle’ and includes its own methods. Followed by a child class that is ‘Car’. With its own methods and some attributes that is inherited by the parent class (brand, model, fuel, doors). However, there is a possibility to replace the override the parent class methods with the ‘super()’ function. Finally, creating an object with instances.
1.b
Below figure demonstrate including two methods to include and clear data. (Appendix 1.b)
 
Figure 2 Python code to include data and clear data

1.c
(Appendix 1.c)
 
Figure 3 Python code to include data and generate 10 random numbers
 
1.d
 (Appendix 1.d)
 
Figure 4 Creating Thermometer object to store data
1.e 
(Appendix 1.e)
 
Figure 5 Creating new class
Based on the above figure the child class ‘TempreatureThermometer’ inherits from the parent class ‘Thermometer’. Through inheritance the child class ‘TempreatureThermometer’’ inherit all methods and attributes. Furthermore, the child class can have its own attributes, as per the above figure ‘show_type’ will automatically replace the parent class method. As per the explanation provided, ability to use methods and transform to many forms and methods in known as polymorphism. As per the example, given the ‘show_type’ method overrides the parent class, and display that it is a digital thermometer. 
1.f
 (Appendix 1.f)
The getter function in the below figure is used to get the value of the ‘version’. To execute a ‘@property’ decorator is used as a method to get the version. This function returns the version value at ‘1.0’. Therefore, it can be changed accordingly by using the setter method.
In relation to the setter function, the below figure has ‘version.setter’ which has a ‘@version.setter’. This function is used to change the value of the attribute. When the method is called the value of ‘__version’ is changed to ‘1.5. Which is under ‘detector.version = ‘1.5’. This is a useful method helps to set an appropriate value and not be manipulated. 



Figure 6 Python code setter and getter
1.g 
(Appendix 1.g)
Simple explanation of the concept Polymorphism is occurrence in many different forms. Polymorphism takes place where there are classes which related to each other by inheritance. Therefore, Polymorphism takes place through inheritance.
 
Figure 7 Python code for demonstrating polymorphism

The above figure demonstrates how Polymorphism takes place through inheritance and how the three child classes (Car, SUV and MotorBike) inherit from the Vehicle class and over how it overrides the ‘check_fuel_level’ method and returns its unique output. 
Therefore, each child class has its own ‘check_fuel_level’ method and each has its different output value. As a result of this although each child class has its own method that can override the parent class method. 
