### Question 1
Ans: 3. The value of i: 0->1->2->3. When i=3, i is not less than prices.length(which is 3) so loop ends.
### Question 2
Ans: 150.discountedPrice will be updated in every loop. In the last loop, we have 300*(1-50%) = 150.
### Question 3
Ans: 150. discountedPrice integer, this line will not change its value. Therefore, finalPrice is 150.
### Question 4
Ans: It is an array that record the finalPrices, which is 100 * 50%=50,200* 50%=100,300* 50%=150.
### Question 5
ReferenceError: i is not defined.
### Question 6
ReferenceError: discountedPrice is not defined
### Question 7
Ans: 150. discountedPrice integer, this line will not change its value. Therefore, finalPrice is 150. Because we use discountedPrice in the block scope, this will not cause any errors.
### Question 8
Ans: It is an array that record the finalPrices, which is 100 * 50%=50,200* 50%=100,300* 50%=150. Because we use discountedPrice in the block scope, this will not cause any errors.
### Question 9
ReferenceError: i is not defined.
### Question 10
Ans: 3. const length is 3, this will not change.
### Question 11
Ans: It is an array that record the finalPrices, which is 100 * 50%=50,200* 50%=100,300* 50%=150. 
### Question 12
A. student.name  
B. student["Grad Year"]  
C. student.greeting()  
D. student["Favorite Teacher"].name  
E. student.courseLoad[0]  
### Question 13
A. '32' 2 will append to '3' and get 32.  
B. 1 3 subtracts 2 is 1.  
C. 3 number 3 + null which is 0 will get 3.  
D. '3null'  null append to 3 is 3null  
E. 4 true's value is 1, 1+3=4  
F. 0 false's value is 0, 0+0=0  
G. '3undefined' undefined will append to '3' which is 3undefined.
H. NaN  we cannot do subtract, it will get NaN which means not a number.  
### Question 14
A. True; 2 is greater than 1.  
B. True; 2 is not greater than 12.  
C. True; 2 is same as '2'.
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
