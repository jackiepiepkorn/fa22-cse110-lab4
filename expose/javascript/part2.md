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
12.  Name property: `student.name`, Grad Year: `student['Grad Year']`
