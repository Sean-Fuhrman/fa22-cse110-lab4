1. Line 12 will print 3, because that is what i is assigned to as the end of the for loop, right before the condition is checked, and i has block level scope
2. Line 13 will print 150, because that is the last value of discountedPrice when the 50% discount is added to 300.
3.  Line 14 will print 150, because that is the last value of finalPrice when the discountedPrice gets rounded.
4.  The function will return an array of [50, 100, 150], as that is the values pushed to discounted, after the 50% discount is applied to each price. 
5.  This errors because i is not defined outside of the for loop
6.  it errors becasue discountedPrice is only defined inside the for loop
7.  It prints 150 because that is what was last assigned to finalPrice in the for loop
8.  The function will return an array of [50, 100, 150], as that is the values pushed to discounted, after the 50% discount is applied to each price. 
9.  The code will error on line 11 because i is only defined in the for loop.
10. It will print 3, because that is the length of prices, which it is assigned to on line 4.
11. It will return [50, 100, 150] Bbecause that is what is pushed to discounted in the for loop. Discounted being a constant still lets you append/edit the array.
12. 
    A. student.name;
    B. student['Grad Year'];
    C. student.greeting();
    D. student['Favorite Teacher'].name;
    E. student.courseLoad[0];
13. 
    A. '32'
    B. 1
    C. 3 
    D. '3null'
    E. 4
    F. 0
    G. '3undefined'
    H. NaN
14.  
    A. true
    B. false
    C. true
    D. false
    E. false
    F. true === Boolean(2)
15. == tests equality by trying to convert both sides to a boolean first, then test equality. === tests for exact equality, so different types cannot be equal with ===. 
17. What will be returned from the function is [2,4,6] because it is taking the function doSomething, and then applying that to every element in the array. doSomething multiplies the num by 2, so it will double every value in the array. 
19. 
1
4
3
2
