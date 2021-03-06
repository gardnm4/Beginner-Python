# The Basics

With any subject in the world, there is special vocabulary that describes the topic in that field of study. A collection of these basic vocabulary words will be kept here:

* Syntax
 * Syntax is to programming languages, as grammar is to languages.
* keyword
 * A keyword is a special word in the language's syntax that does a special action. Here is a [list](/Users/michaelgardner/MEGA/Programming/teaching/keywords.md) of keyboards, such as print and def.
* Variable
 * To say variables in Computer Science are like variables in algebra is saying a wolf is a dog. You are correct, but there is more to it. Variables in Python can be reassigned unlike variables in mathematics because in math it is implied that once you assign a value to a variable it never changes.
* Semantic
 * Semantic is usually said in a type of error such as a "syntax error" or a "semantic error". A syntax error is like a grammar error. Semantic error is a logic error. It's like if you subtract a number instead of adding a number; your logic is wrong so you have an error. Python won't tell you it is an error but you will notice that your program is giving you weird results.
* Parameter v. argument
 * Let's define a function.

``` python
def add3(x):
  answer = x + 3
  return answer

print add3(5)
```

 x is called a parameter because is a variable that is used as an input. The variable `answer` and the value `5` are known as arguments because values are assigned to them inside the function. Most programmers will not talk about `answer` being an argument, but that `x` is a parameter and, in our case, `5` is a argument.
