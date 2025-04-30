1. ``values added: 20`` is what is printed by line 9.
2. ``final result: 20`` is what is printed by line 13.
3. You should not use var because declaring a variable with var allows that variable to be accessed anywhere within the same function that it was defined in which can cause confliction with other variables and their definitions. 
4. ``values added: 20`` is printed by line 9.
5. A "result is not defined" ReferenceError is thrown by line 13 becuase result was declared within the if-statement scope with ``let`` and is trying to be accessed outside of that scope which it cannot be accessed like it was with var previously.
6. A "TypeError: Assignment to constant variable" error is thrown by line 7 because we are trying to update/change the value of a variable of type constant which cannot be done. Therefore, line 9 does not run. 
7. Since there is an error before we run line 13, there is no output for this line but in line 13 we are trying to access the result variable which was declared in a different scope so line 13 would throw an error if it did run.