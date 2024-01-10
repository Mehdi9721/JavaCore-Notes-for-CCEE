# JavaCore-Notes-for-CCEE
## DAY_1 
### Understanding every small aspects of java core programming     (Note- READ EVERY KEY POINTS THESE ARE IMP FOR CCEE)
#### Started with Operators. 
(We have many operators but here we are discussing only about small aspects of operators in java)<br>                         
<br>
----------------------------->Key 1 Operators <br>
In java we have shift operators like >> (right shift) and (<<) left shift. The right shift value can get by <br>
<br>
(actual_number)*(2^how many shifts) and for left shift <br>
<br>
[ (actual_number)\(2^how many shifts) ]. <br>
for example if we have 8 and wants to right shift by 6 bits = 8*2^6.<br>
for example if we have 8 and wants to Left shift by 6 bits = 8/2^6.<br>
<br>
----------------------------- Key 2 Operators->
<br>
Now we have conditionals operators like && and || but in case of && operator with the left side value is false it will not check the right side value and if we written post increament in right side it will not get execute and value will remain the same. Hence we also have Bitwise & on using '&' it will check both sides even if the left side is false <br>
<br>
Example : <br>
a=20; <br>
b=30; <br>
if(a>b&&a++<b){} // a will not get incremented becouse the left side is false <br>
But if we use if(a>b&&a++<b) // a will become 21 becouse right side will also checked <br>
<br>
----------------------------- Key 3 Operators->
<br>






