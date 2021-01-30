1. The number of elments in the "prices" array because the for loop stops when i == prices.length.
2. The discounted price of the last item will be printed. This is because the for loop assigns "prices[i] * (1 - discount)" to "discountedPrices", and when the loop is completed "discountedPrice" will have the discounted price of the last item.
3. The final price of the last discounted item will be printed. This is because the for loop assigns the discounted price of the item to the variable "finalPrice", and when the for loop is completed "finalPrice" will have the final price of the last item.
4. The function will return [50, 100, 150]. This is beacuse the for loop iterates through each item in the list of prices, and applies a discount of 0.5.
5. "Error, no such variable" beacuse "i" is only visible inside the for loop.
6. "Error, no such variable" because "discountedPrice" is only visible inside the for loop.
7. The final price of the last discounted item will be printed. This is because the for loop assigns the discounted price of the item to the variable "finalPrice", and when the for loop is completed "finalPrice" will have the final price of the last item.
8. The function will return [50, 100, 150]. This is beacuse the for loop iterates through each item in the list of prices, and applies a discount of 0.5.
9. "Error, no such variable" beacuse "i" is only visible inside the for loop.
10. "Error, no such variable" because "discountedPrice" is only visible inside the for loop.
11. 0 will be printed, because changing the value of "finalPrice" is not possible, so the value stays at 0.
12. The function will return [0, 0, 0]. This is because "finalPrice" is always 0, and the value 0 is added to the array in each iteration of the loop.
13. A) student.name

    B) student["Grad Year"]

    C) student.greeting()

    D) student["Favorite Teacher"].name

    E) student.courseLoad[0]

14. A) '32', because 2 is converted to the string '2' when addition is applied.
    
    B) 1, because '3' is converted to the number 3 when substraction is applied.

    C) 3, because null is converted to the number 0 when addition is applied.

    D) '3null', because null is converted to the string 'null' when addition is applied.

    E) 4, because true is converted to the number 1 when addition is applied.

    F) 0, beacuse false is converted to the number 0, and null is converted to the number 0, when addition is applied.

    G) 3undefied, because undefined is converted to the string 'undefined' when addition is applied.

    H) NaN, because "3" is converted to the number 3, and undefined is converted to the NaN when subtraction is applied.

15. A) true, because '2' is converted to the number 2, which is greater than 1.

    B) true, because '2' comes before '21' in lexicographic order.

    C) true, because '2' is converted to the number 2, which is equal to 2.

    D) false, because the types of 2 and '2' are different.

    E) false, beacuse true is converted to the number 1, which is not equal to 2.

    F) true, because 2 is not an "empty" value, so Boolean(2) is true, which is equal to true.

16. A strict equality operator === checks the equality without type conversion; a regular equality operator == checks the equality with type conversion.
17. 'How are you?' gets printed, because 2 is not equal to true, and 2 is not an "empty" value. So the statement in the 2nd block is called.
18. In "part1-question18.js"
19. modifyArray([1,2,3], doSomething) returns [6, 8, 10]. The for loop iterates through each element in [1, 2, 3]. For each element, doSomething is called, with the element and a function as a parameter. The function multiplies the parameter by 2, and doSomething adds 2 to the parameter before calling the function in the parameter. So for each element x, it is converted to (x + 2) * 2.
20. In "part1-question20.js"
21. 1

    4

    3

    2