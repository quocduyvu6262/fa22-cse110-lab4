# Answer: 

1. The program prints '3' to the console because variable *i* is used to iterate the *prices* array with length = 3. Hence, at the end of the *for loop*, *i* has the value of '3' and is also accessible outside of the for loop since it has a **function scope** when declared with *var* keyword.

2. The program prints '150' to the console. The *discountedPrice* is declared every iteration with the updated value, so that after the *for loop*, *discountedPrice* (300 * 0.5) is the discounted price of the last item in *prices* array. The *discountedPrice* is accessible outside of the for loop since it has a **function scope** when declared with *var* keyword.

3. The program prints '150' to the console. The *finalPrice* is is assigned with new value in every iteration, so that after the *for loop*, *finalPrice* (300 * 0.5) is the rounded discounted price of the last item in *prices* array. 

4. The function returns [50, 100, 150]. Each element in *prices* array is multiplied by (1-0.5) and rounded to the nearest value, then get pushed to *discounted*, which the function returned at the end.

5. Function causes an error because it tries to access *i*, which has a **block scope** when initialized with *let*, outside of its scope (*for loop*).

6. Function causes an error because it tries to access *discountedPrice*, which has a **block scope** when initialized with *let*, outside of its scope (*for loop*).

7. The program prints '150' to the console. *finalPrice* variable is accessible everywhere inside the function because it was declared using *let* in the **function block**.

8. The function returns [50, 100, 150]. It is because switching to using *let* in this example does not change the functionality of this function, hence the function acts the same as the previous one.

9. Function causes an error because it tries to access *i*, which has a **block scope** when initialized with *let*, outside of its scope (*for loop*).

10. The program prints '3' to the console because the *prices* array has length of 3.

11. The function returns [50, 100, 150]. Each element in *prices* array is multiplied by (1-0.5), then get pushed to *discounted*, which the function returned at the end.

12. 
    - A: student.name
    - B: student['Grad Year']
    - C: student.greeting()
    - D: student['Favorite Teacher'].name
    - E: student.courseLoad[0]

13. 
    - A: '32' because integer 2 is mapped to string representation
    - B: 1 because string '3' is converted to integer 3
    - C: 3 because *null* is converted to integer 0
    - D: '3null' because *null* is converted to string 'null'
    - E: 4 because *true* is converted to integer 1
    - F: 0 because *false* and *null* is converted to integer 0
    - G: '3undefined' because *undefined* is converted to 'undefined'
    - H: NaN because *undefined* is converted to NaN and 3 - NaN results in NaN.

14. 
    - A: true because string '2' is mapped to integer 2
    - B: false because '2' is greater than '12' in lexicographical order
    - C: true because string '2' is mapped to integer 2
    - D: false because 2 and '2' are of different types
    - E: false because *true* is converted to integer 1
    - F: true because Boolean(2) results in true

15. The '==' performs the type conversion before doing the comparision while '===' compares the values and the data types.

16. [Code](expose/javascript/part2-question16.js)

17. Result returned from the function is [2, 4, 6]. The original input array is [1, 2, 3] and each element is given to the callback function parameter and then get pushed to *newArr*. Since the function *doSomething* was passed in as the callback function, each element is multiplied by 2 before getting pushed to *newArr*. Hence the final *newArr* is [2, 4, 6].

18. [Code](expose/javascript/part2-question18.js)

19. The program prints 1 to the console, followed by 4 and 3. Then the program prints 2 to the console 1 second after that.