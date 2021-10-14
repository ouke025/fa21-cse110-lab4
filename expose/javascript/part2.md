1. Line 12 prints "3", which is the final value assigned to the counter i. Since i is defined as var, it can still be accessed outside the for loop, and it stores the value that was last assigned to it.
2. LIne 13 prints "150", which is the dicounted price for the last item. Since discountedPrice is defined as var, it can still be accessed outside the for loop, and it stores the value that was last assigned to it.
3. Line 14 prints "150", which is the rounded discounted price of the last item. Since finalPrice is defined at the same block as line 14, it can be accessed by the logging command, and it stores the value that was last assigned to it.
4. The function will return "[50, 100, 150]", which is the list containing the discounted price of each item. 
5. Line 12 prints "ReferenceError: i is not defined". This is because i is defined with the "let" keyword so that it can only be accessed within the for loop.
6. Line 13 prints "ReferenceError: discountedPrice is not defined". This is because discountedPrice is defined with the "let" keyword so that it can only be accessed within the for loop.
7. Line 14 prints "150", which is the rounded discounted price of the last item. Since finalPrice is defined at the same block as line 14, it can be accessed by the logging command, and it stores the value that was last assigned to it.
8. The function will return "[50, 100, 150]", which is the list containing the discounted price of each item. 
9. Line 11 prints "ReferenceError: i is not defined". This is because i is defined with the "let" keyword so that it can only be accessed within the for loop.
10. Line 12 prints "3", which is the length of the prices list. Since length is defined at the same block as line 12, it can be accessed by the logging command.
11. The function will return "[50, 100, 150]", which is the list containing the discounted price of each item. Although discounted is defined as a constant, we are not modifying it directly through the assignment ("=") operator, but rather calling its member function "push", so the modification is valid.
12. 
    A. student.name
    B. student["Grad Year"]
    C. student.greeting()
    D. student["Favorite Teacher"].name
    E. student.courseLoad[0]
13. 
    A. '3' + 2 = '32'                   // 2 is casted to string '2'
    B. '3' - 2 = 1                      // '3' is casted to int 3 since there is no string subtraction
    C. 3 + null                         // null is casted to int 0
    D. '3' + null = '3null'             // null is casted to string 'null'
    E. true + 3 = 4                     // true is casted to int 1
    F. false + null = 0                 // both false and null are casted to int 0
    G. '3' + undefined = '3undefined'   // undefined is casted to string 'undefined'
    H. '3' - undefined = NaN            // '3' is casted to int 3, undefined is casted to NaN.
14. 
    A. '2' > 1: true                    // '2' is casted to int 2
    B. '2' < '12': false                // '2' is casted to int 2, '12' is casted to int 12
    C. 2 == '2': true                   // '2' is casted to int 2
    D. 2 === '2': false                 // 2 and '2' are of different data types
    E. true == 2: false                 // true is casted to int 1, '2' is casted to int 2
    F. true === Boolean(2):true         // Boolean(2) is true; any integer greater than 0 is converted to true
15. When evaluating "a == b", JavaScript will convert both a and b to comparable data types if they are of different types; in contrast, "a === b" is more strict and will return false immediately if a and b are of different data types. For example, "0 == false" is true because the Boolean "false" is casted to integer 0. Meanwhile, "0 === false" is false because 0 is an integer while false is a Boolean.
16. As shown in part2-question16.js.
17. The result will be "[2, 4, 6]", as modifyArray applies doSomething on every element of the input array. 
18. As shown in part2-question18.js. 
19. The output is "1 4 3 2".