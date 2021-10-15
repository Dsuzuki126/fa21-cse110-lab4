1. Line 12 will print out the value of i which at the end of the for loop should be 2 since even though i is being accessed outside the for loop, it is of var type which can be accessed inside the function it is declared in.
2. Line 13 will print the value of discountedPrice which will be 150 after the for loop runs because since it is a var, its scope is the function is it is in which is discountPrices which is still ongoing
3. Line 14 will print finalPrice which after the for loop will be 150 since it is a var type so its scope will be the function discountPrices so it retains the same value until the console.log
4. The function will return an array with [50, 100, 150] since the discounted variable is a var type so its value persists outside the for loop 
5. Line 12 will return an error since it is outside the scope of "i" which is the for loop so "i" is inaccessible outside the for loop
6. Line 13 like line 12 will also return an error since the scope of discountedPrice is inside the for loop so it is inaccessible after that.
7. Line 14 will return 150 since the scope of finalPrice is the function discountPrices and the console.log(finalPrice) is inside the function
8. The function will return an array [50, 100, 150] since the scope of discounted is the function and the return statement is inside the function as well.
9. Line 11 will return an error since the scope of "i" is the for loop and the console.log is outside the for loop.
10. Line 12 will print the length of the prices array which is 3 which is ok since length isn't being changed and its scope is the function.
11. This function will return the value of discounted which is the array [50, 100, 150]
12. 
    1.  student.name
    2.  student['grad year']
    3.  student.greeting()
    4.  student['Favorite Teacher'].name
    5.  student.courseLoad[0]
13. 
    1.  '3' + 2 resulted in '32' since 2 was converted to a string type 
    2.  '3' - 2 resulted in 1 as '3' was converted to an integer data type 
    3.  3 + null resulted in 3 as null was converted to 0
    4.  '3' + null resulted in 3null as null was converted to a string
    5.  true + 3 resulted in 4 which means that true was converted to 1
    6.  false + null resulted in 0 which means false was converted to 0 and null converted to 0 as well
    7.  '3' + undefined resulted in '3undefined' as undefined was converted to a string type
    8.  '3' - undefined resulted in NaN since subtraction is a integer function but any operation using the undefined results in NaN
14. Comparison
    1.  '2' > 1 results in true; '2' was probably converted to the numeric integer 2
    2.  '2' < '12' results in false; since they're both strings, in ASCII the char 2 is greater than the char 1 so it would return false
    3.  2 == '2' resulted to true; '2' was converted to a numeric integer so 2 == 2 would result to true
    4.  2 === '2' resulted to false; since both sides are not the same type the strict equality operator would return false
    5.  true == 2 resulted to false; this would return false since true is converted to numeric 1 which is not the same as 2
    6.  true === Boolean(2) resulted to true; using the strict equality, since true and 2 are both boolean types it would return true
15. === is strict equality operator so if the two sides are not the same type it would immediately return false without going any further; == compares both sides and converts either one to a comparable type
16. Javascript file
17. Calling modifyArray([1,2,3], doSomething) will go through the for loop which will then call the callback function(in this case doSomething) which each iteration will multiply each element of the input array by 2. So the output array will be [2,4,6]
18. javascript file
19. The output will ouput on separate lines 1 4 3 2

