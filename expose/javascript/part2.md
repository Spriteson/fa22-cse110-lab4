1. it prints i which is 3. i is a var, and can be access anywhere within the function. i was declare to be 0, and increase to 3 since the prices.length = 3.
2. it prints 150. discountedPrice is a var(can be access within the function), the last iteration in the for loop is when i = 2, fiscountedPrice was updated to  300*0.5 = 150. so when printing iscountedPrice, it will print out 150.
3. it prints 150. finalPrice is a var(can be access within the function), and the last it was updated when i = 2, and discountedPrice = 150. then finalPrice = round(150*100)/100 = 150. So when printing finalPrice, it will print out 150.
4. it will return [ 50, 100, 150 ]. the function discountPrices calculate the discounted price for each original price, wich is 50% off. in the for loop, it will calculate the discount price the in order, and push the discounted price into the list discounted in order. So when returning the list diescounted, it will return the dicounted price for the input list.
5. ERORR! i is a let and was define with in the for loop. the block scope is within the for loop. so it cannot be access outside of the for loop.
6. ERROR! discounted is a let and was define with in the for loop. the block scope is within the for loop. so it cannot be access outside of the for loop.
7. it prints 150. finalPrice is a let, the block scope is the function, which include ouside of the for loop. so fianlPrice can be access and print its value (the last iteration) which is 150.
8. [ 50, 100, 150 ]. As a saide before, the function calculate the discounted price. even though discounted is let, but its block scope is the function, so it can be access outside of the for loop. The for loop is consider within the block scope for discounted and finalPrice, so they also can be access within the for loop and be updated.
9. ERORR! i is a let(block scope), and cannot be outside of the block scope.
10. it prints 3. the length was define as a const with value of prices.length which is 3. accessing a const won't cause any problem.
11. it return [ 50, 100, 150 ]. discounted was declare as const which is a constant reference to an array. So we can change the elements of a constant array.
12. A. student.name
    B. student['Grad Year']
    C. student.greeting()
    D. student['Favorite Teacher'].name
    E. student.courseLoad[0]
13. Arithmetic
    A. '32'    2 was map to '2', and '3' + '2' = '32'
    B. 1     '3' converted to a number, and 3 - 2 = 1. 
    C. 3     null was converted to 0, 3+0 = 3
    D. '3null'  null was converted to 'null', ‘3’ + 'null' = ‘3null'
    E. 4      true was converted to 1. 1+3=4
    F. 0      false and null were converted to 0, 0+0=0
    G. '3undefined'    undefined was converted to 'undefined', '3' + 'undefined' = '3undefined'
    H. NaN    undefine was converted to NaN(not a number), '3' - NaN = NaN
14. Comparison
    A. true, string '2' becomes a number 2 and 2>1
    B. false two string were compared lexicographically. the first char of '12' is '1' and  '2' > '1', so '2' < '12' return false.
    C. ture, '2' becomes 2, 2 == 2 return true.
    D. false, === is strict equality comparison. 2 and '2' is not the same type.
    E. false, true becomes 1, and 1 != 2.
    F. true, boolean(2) return true. true === true return true, since they are the same type and same value.
15. == is used for loose equality comparison, variable can be converted to different type. === is used for strict equality comparison, which means that it does not perform type coercion and the operands must be of the same type and have the same value in order for the comparison to be true.
17. [ 2, 4, 6 ]. We pass in a array [1,2,3] and the function doSomething in modifyArray function. then when we started to push new element into the newArr in the forloop, we use callback(doSomthing function in this case), and pass in array[i] in the callback parameter, this means that we call doSomething by passing in array[i] and get the result is 2*array[i] back, and push it into the newArr, which is 2,4,6. since 1*2 = 2, 2*2=4, 3*2=6.
19. 1 4 3 2. once the program runs, it print 1 4 3 Immediately,  after 1 second, it then prints 2.
