

**1) Lambda Function**. Lambda functions are anonymous functions, declared by using *lambda* keyword. Although syntactically this functions look different, but behave in the same way as regular functions that are declared using the *def* keyword.

*Properties of lambda function:*
* A lambda function can take any number of arguments, but they contain only a single expression.
* Lambda functions can be used to return function objects.
* Syntactically, lambda functions are restricted to only a single expression.

*Syntax to declare a lambda function*:`lambda argument(s): expression`

**Example**
```python
# Adding two number using lambda function
add_num = lambda num1, num2: num1 + num2

add_num(10, 20)
```

<br/>

**2) Map Function**. The *map()* function is a built-in function, it calls the specified function for each item of an iterable (such as string, list, tuple or dictionary) and returns a list of results.

*Syntax of map function*: `map(function, iterable [, iterable2, iterable3,...iterableN])`

**Example**
```python
# Check the numbers in the list is even or odd
num_list = [2,3,4,5,6,7,8,9,0]   # Instead of iterating the list using for loop, we can use map functions

def check_EvenOdd(num):
    if num%2==0:
        return "The number {} is even ".format(num)
    else:
        return "The Number {} is odd ".format(num)

list(map(check_EvenOdd, num_list))
#            OR
# We can also use lambda functions to shorten the lines of code
list(filter(lambda num: num%2==0, num_list))
```

<br/>
