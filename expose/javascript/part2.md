1. 3 will be outputted. The loop will go fully from 0 to 2 because there 3 items in the array. It will increment i one more time and then figure out that i is no longer less than the array size, so it will exit the loop and 3 will be outputted.
2. 150 will be outputted. This is because the last element in the array will be the last time the discountPrice was assigned, and it is assigned to 50% of that element's price, so 150.
3. 150 will be outputted because of the reason above, with the additional fact that assigning finalPrice rounds the number to the dollar, which is still 150 in this case.
4.  This will return the array that contains the discounts of each price. The for loop body pushed all the final prices to it.
5.  There would be an error because i would not be defined. The let keyword makes it so that i is not defined outside of the for loop.
6.  There would be an error because discountedPrice would not be defined. The let keyword makes it so that discountedPrice is not defined outside of the for loop.
7.  150 will be outputted. The let keyword is used outside of the for loop and inside the function so the variable is defined throughout the function.
8.  This will return the array that contains the discounts of each price; the let keyword is used outside of the for loop so discounted is defined throughout the function.
9.  There would be an error because i would not be defined, since the let keyword only allows it to be defined inside of the for loop.
10.  3 is outputted. Length was assigned to be prices.length, which is 3, and there weren't any attempts to reassign it after that.
11.  The array of discounted prices is outputted. This is because, although the array cannot be reassigned, elements can still be added if there is a const keyword.
12. 
  A. `student.name`
  B. `student['Grad Year']`
  C. `student.greeting()`
  D. `student['Favorite Teacher'].name`
  E. `student.courseLoad[0]`

13.
  A. '3' + 2 outputs the string '32'. This is because the + operator is used for concatenating strings, so the number 2 is made into a string and concatenated with the string '3'.
  
  B. '3' - 2 outputs the number 1. This is because the - operator is used for subtraction, so the string '3' is changed into the number 3 and subtracted with the number 2.
  
  C. 3 + null will output the number 3. This is because null is turned into the number 0 when used in a mathematical operation, so 3 + 0 is equal to 3.
  
  D. '3' + null will output the string '3null'. This is because null becomes the string 'null' when used in a string concatenation, so '3' + 'null' is equal to '3null'.
  
  E. true + 3 outputs the number 4. This is because true is changed into the number 1 when used in a mathematical operation, so 1 + 3 is equal to 4.
  
  F. false + null will output the number 0. This is because both false and null become the number 0 when used in a mathematical operation, so 0 + 0 is equal to 0.
 
  G. '3' + undefined will output the string '3undefined'. This is because undefined becomes the string 'undefined' when used in a string concatenation operation, so '3' + 'undefined' is equal to '3undefined'.
  
  H. '3' - undefined will output the special value NaN (Not a Number). This is because undefined is the special value NaN when used in a mathematical operation, and the result of any operation involving NaN is also NaN.

14.
A. '2' > 1 will output true. This is because the string '2' becomes the number 2, and 2 is greater than 1.

B. '2' < '12' will output true. This is because the two strings are compared lexicographically, and since the first character of '2' is less than the first character of '12', the comparison returns true.

C. 2 == '2' will output true. This is because the == operator performs type coercion, so the string '2' is coerced into the number 2, and 2 is equal to 2.

D. 2 === '2' will output false. This is because the === operator performs strict equality comparison, and the two operands are of different types (number and string), so the comparison returns false.

E. true == 2 will output false. This is because the == operator performs type coercion, so true is coerced into the number 1, and 1 is not equal to 2.

F. true === Boolean(2) will output true. This is because the === operator performs strict equality comparison, and the two operands are of the same type (boolean). Boolean(2) returns true, so the two operands are equal.


15. The == compares by making sure both sides are converted to a common type and then compares equality. === consideres their original types, so if both sides aren't the same type, they can't be equal even if they're "equal"

#17. The result is [2, 4, 6]. The array [1, 2, 3] is passed as the first parameter to the modifyArray function and the function doSomething is the second parameter. The modifyArray function creates an empty array newArray and a for loop iterates through each element in the original array, starting with array[0], then array[1], etc. Inside the loop, the callback function doSomething is called with the current element as its argument, so doSomething(1) is called first, then doSomething(2), and doSomething(3). The modified value that doSomething returns for each element is pushed onto the newArray. After all the elements have been iterated through, newArray is returned with the modified values [2, 4, 6].

18. 1 4 3 2
