# JavaCore-Notes-for-CCEE
## DAY_1 
### Understanding every small aspects of java core programming     (Note- READ EVERY KEY POINTS THESE ARE IMP FOR CCEE)
## Operators. 
(We have many operators but here we are discussing only about small aspects of operators in java)<br>                         
<br>
***Key 1 (Operators) ->*** 

In java we have shift operators like >> (right shift) and (<<) left shift. The right shift value can get by <br>
<br>
(actual_number)*(2^how many shifts) and for left shift <br>
<br>
[ (actual_number)\(2^how many shifts) ]. <br>
for example if we have 8 and wants to right shift by 6 bits = 8*2^6.<br>
for example if we have 8 and wants to Left shift by 6 bits = 8/2^6.<br>
<br>
***Key 2 (Operators) ->*** 
<br>
Now we have conditionals operators like && and || but in case of && operator with the left side value is false it will not check the right side value and if we written post increament in right side it will not get execute and value will remain the same. Hence we also have Bitwise & on using '&' it will check both sides even if the left side is false <br>
<br>
Example : <br>
a=20; <br>
b=30; <br>
_if(a>b && a++<b){}_ // a will not get incremented becouse the left side is false <br>
But if we use _if((a>b) & (a++<b))_ // a will become 21 becouse right side will also checked <br>
<br>
***Key 3 (Operators) ->*** 
<br>
Now Similar to '&&' and '&' operators The '||' and '|' operators performs same, As Logical'||' or will not check the second condition if the first is true but the Bitwise '|' will check the both side. <br>
Example : <br>
a=20; <br>
b=30; <br>
_if(a<b || a++<b){}_ // a will not get incremented becouse the left side is false <br>
But if we use _if(a<b | a++<b)_ // a will become 21 becouse right side will also checked <br>
<br>
***Key 4 (Operators) ->*** 
<br>
If we talk about the assignment operators like a+=b or a*=b etc, they will not do implicit type casting of operators <br>
<br>
For Example if we have 
<br>
short a=20; <br>
short b=20; <br>
a+=b //will not give compiler error and will add values of b into a <br>
But if i do a=a+b; // compiler will give error of loosy conversion from int to short as it converted a and b int to short 'a' due to '+' operator <br>

## Class in JAVA
***Key 1 (class) ->*** 
Java class has static/class related and non-static/instance related variables and methods and by default there values are 0. <br>
Java class can be abstract and final, final class can not get inherited and We are not able to create object of abstract class. <br>
---> Abstract class. <br>
Abstract class  can contain abstract methods (abstract void x();) and class which inherits abstract class it is necessory for them to implement abstract methods of Parent class. <br>
## Interfaces
Need of interfaces arises for achiving multiple inheritanse and providing more detailed polymorphism to classes. <br>
Interface can have (default void x(){}) default method with body and (void x();) method with no body. (Public, static and final) <br>
#### Functional Interface
Functional Interface in java this interface has only 1 abstarct method but can contain default or static method also, Functional Interface was introduced in java8 and Lamda expression is used for making easy  use of functional interface. <br>
The ***Anonymus class** gets created when we create reference of Interface type, this class contains implimentaion of abstract method of interface and this anonymus class implimentation can get more simplified by using lamda expression. <br>



