# ()

> function() { } defines a javascript function as is obvious. Surrounding it with () makes it an expression. Following it with () executes it.

> The grouping operator consists of a pair of parentheses around an expression or sub-expression to override the normal operator precedence so that expressions with lower precedence can be evaluated before an expression with higher priority. As it sounds, it groups what's inside of the parentheses.


# Expressions
> Expressions are Javascript code snippets that result in a single value. Expressions can be as long as you want them to be, but they would always result in a single value.


# Statement 
> statements perform actions, they do things. In javascript, statements can never be used where a value is expected. So they cannot be used as function arguments, right-hand side of assignments, operators operand, return values…


> one way to tell the Javascript engine to expect a value is via parentheses, (), without the parentheses, each expression will be treated as an argument



# IIFE 
> An anonymous function can be an expression, if we use it where Javascript is expecting a value, that means we if we can tell Javascript to expect a value with parentheses, we can pass an anonymous function as that value.


https://dev.to/promhize/javascript-in-depth-all-you-need-to-know-about-expressions-statements-and-expression-statements-5k2
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Grouping#using_the_grouping_operator
https://dev.to/ritik_dev_js/what-the-hack-is-closure-currying-and-iife-in-javascript-32m9
