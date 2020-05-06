## Comparison Operators:

### Evaluating Conditions

* You can evaluate a situation by comparing
one value in the script to what
you expect it might be. The  result will
be Boolean: true or false



  ###   ==        is equal to


* compares 2 values (numbers or strings or Booleans) to see if they are the same

        'hello' == 'goodbye' returns false
         because they are NOT the same string

        'hello' == 'hello" returns true
        because they ARE the same string

### != is NOT equal to


* compares 2 values (numbers or strings or Boolean)
to see if they are NOT the same

        'hello' != 'goodbye' returns true because
        they are not the same string

        'hello' != 'hello' returns false because
        they are the same string

### === strict equal to

* compares 1 values to check that both the data type and value are the same

        '3' === 3 returns false
        because they are NOT the same DATA TYPE or VALUE

        3' === '3' returns true because
        they ARE the same DATA TYPE and VALUE

### !== strict not equal to

* compares 2 values to check that they
both the data type and value are not the same


        '3' !== 3 returns true because they are NOT the same DATA TYPE  or VALUE

        '3' !== '3' returns false because
        they ARE the same DATA TYPE and VALUE

its usally preferable to use the Strict Method

evaluating the condition - testing or checking of a condition

- Every value can be treated as true or false
even if it is not a Boolean true or false value

### '>' -  Greater than

checks if the number on the left is greater than 
the number on the right

        4 > 3 returns true
        3 > 4 returns false

### < -  Less than 

checks if the number on the left is less
than the number on the right

        4 < 3 returns false
        3 < 4 returns true

### '>=' Greater than or equal to

checks if the number on the left is Greater than or equal to the number on the right

        4 >= 3 returns true
        3 >= 4 returns false
        3 >= 3 returns true

### <=   Less than or equal to

checks if the number on the left is Less than or equal tothe number on the right

        4 <= 3 returns false
        3 <= 4 returns true
        3 <= 3 returns true 

## Logical Operators

Comparison operators usually return
single values of true or false

Logical operators allow you to compare the 
results of more than one comparison operator

### && Logical And

tests more than one condition

 true && true returns true
 true && false returns false
false && true returns false
false && false returns false

### || Logical Or

tests at least one condition

        true || true returns true
        true || false returns true
        false || true returns true
        false || false returns false

### ! Not
Takes a single Boolean value and inverts it

        !true returns false
        !false returns true

Logical expressions are evaluated left to right

if the first condition can provide enough
info to get the answer than there is no need
to evaluate the second condition

## Loops

* For - used to run a code a specific number 
of times. the condition is usually a counter
which is used to tell how many times the loop should
run.

* While the code continues to loop for as long as the 
condition is true

* Do While - always run the statements inside the 
curly braces at least once even if the condition 
evaluates to false






































https://deannaj401.github.io/learning-journal/