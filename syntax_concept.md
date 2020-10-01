

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
