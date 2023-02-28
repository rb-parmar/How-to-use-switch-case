## How-to-use-switch-case

Learning to use 'switch case'

The `switch case` statement is used to evaluate an expression once where the value of the expression is comapred with the values of each `case`. If there is a match, the associated block of code is executed. If there is no match, the default code block is executed (the code in the last `case`). 
This method is preferred over using multiple `if...else` statements because it is more neat and easier to read.  

#### Consider the eample below:

In this example, we are giving a comment to various grades.

First, you are required to declare a `variable` using either `var` or `let` such as `let grade = 'B';`.
Then use the `switch case` and enter the `variable name` (expression) in the parenthesis.
We use the `break;` statement to control flow of output which would otherwise be infinite times.

### Example:

```javascript
let grade = 'B';

switch(grade) {
  case 'A':
    return 'Excellent';
    break;
  case 'B':
    return 'Good';
    break;
  case 'C':
    return 'Fair';
    break;
  case 'D':
    return 'You can do better';
    break;
  default:
    return 'Work hard!';
}
```
