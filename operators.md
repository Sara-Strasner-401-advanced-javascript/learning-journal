# Operators

## Comparison Operators: Evaluating Conditions
You can evaluate a situation by comparing one value in the script to what you expect it might be. The result will be a Boolean: true or false. 

Common Comparison Operators
- `==` equal to
- `===` strictly equal to
- `!=` not equal to
- `!==` strictly not equal to
- `>` greater than
- `<` less than
- `>=` greater than or equal to
- `<=` less than or equal to


## Logical Operators
Comparison operators usually return a single value of true or false. Logical operators allow you to compare the results of two or more comparison operators. 

Commong Logical Operators
- `&&` **Logical And.** checks to see whether both expressions on either side of it return true. It only returns true if both expressions are true.  
- `||` **Logical Or.** It only returns false of both expressions are false.
- `!` **Logical Not.** It takes a single Boolean value and inverts it. 

```((5 < 2) && (2>=3))```
The above examle would return a value of false.

# Loops
Loops check a condition. If it returns true, a code block will run. Then the condition will be checked again and if it still returns true, the code block will run again. It repeats until the condition returns false. There are three common types of loops.
1. **For.** If you need to run a code a specific number of times, use a for loop. It is the most common loop.
1. **While.** If you do not know how many times the code should run, you can use a while loop. Here the condition can be something other than a counter, and the cone will contine to loop as long as the condition is true. 
1. **Do while.** This loop is very similar to the While loop, but it has one key difference: it will always run the statements inside the curly braces at least once, even if the condition evaluates to false. 