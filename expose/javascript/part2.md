### Question 1
Ans: 3. The value of i: 0->1->2->3. When i=3, i is not less than prices.length(which is 3) so loop ends.
### Question 2
Ans: 150.discountedPrice will be updated in every loop. In the last loop, we have 300*(1-50%) = 150.
### Question 3
Ans: 150. discountedPrice integer, this line will not change its value. Therefore, finalPrice is 150.
### Question 4
Ans: It is an array that record the finalPrices, which is 100 * 50%=50,200* 50%=100,300* 50%=150.
### Question 5
ReferenceError: i is not defined. i is defined as key "let" in loop, we cannot use i's value outside the loop.
### Question 6
ReferenceError: discountedPrice is not defined. discountedPrice is defined as key "let" in loop, we cannot use discountedPrice's value outside the loop.
### Question 7
Ans: 150. discountedPrice integer, this line will not change its value. Therefore, finalPrice is 150. Because we use discountedPrice in the block scope, this will not cause any errors.
### Question 8
Ans: It is an array that record the finalPrices, which is 100 * 50%=50,200* 50%=100,300* 50%=150. Because we use discountedPrice in the block scope, this will not cause any errors.
### Question 9
ReferenceError: i is not defined.i is defined as key "let" in loop, we cannot use i's value outside the loop.
### Question 10
Ans: 3. const length is 3, this will not change.
### Question 11
Ans: It is an array that record the finalPrices, which is 100 * 50%=50,200* 50%=100,300* 50%=150. 
### Question 12
A. student.name;  
B. student['Grad Year'];  
C. student.greeting();  
D. student['Favorite Teacher'].name;  
E. student.courseLoad[0];  
### Question 13
A. '32' 2 will append to '3' and get 32.  
B. 1 3 subtracts 2 is 1.  
C. 3 number 3 + null which is 0 will get 3.  
D. '3null'  null append to 3 is 3null  
E. 4 true's value is 1, 1+3=4  
F. 0 false's value is 0, 0+0=0  
G. '3undefined' undefined will append to '3' which is 3undefined.  
H. NaN  undefined will convert to NaN, 3- NaN will also get NaN which means not a number.  
### Question 14
A. True; 2 is greater than 1.  
B. False; '2' and '12' are strings. We compare string by characters, '2' is greater than '1'(first char in '12'). Therefore, it is false.  
C. True; 2 is same as '2'. == will convert both types to the same type.
D. False; 2 and '2' is not same because their types are different.  
E. False; true means 1 and not equal to 2.
F. True; Boolean(2) will return true, which is equal to true.  
### Question 15
== will transform the operands having same type before comparison.  
=== will directly compare. If the type is not same, it will return false.  
### Question 17
modifyArray([1,2,3],doSomething) will return [2,4,6].
In the loop, each number will go to doSomething first and then push back to arr.
doSomething just 2 * the original numbers. Therefore, we get [2,4,6]  
### Question 19  
1 4 3 2
When running PrintNums, the console.log(1) and console.log(4) will be done first, therefore we have 1 and 4 at first.   
Other than that, when this function end, setTimeout(function() { console.log(3); } , 0); will be done because this line means run console.log(3) at 0 second after this function end.   
After 1 second, setTimeout(function() { console.log(2); } , 1000); will be done because this line means run console.log(2) at 1 second after this function end.   
