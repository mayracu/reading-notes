# Operators and Loops

## Comparison Operators

A comparison operator compares its operands (which can be numerical, string, logical, or object values) and returns a logical value based on whether the comparison is true.

- Equal (==): Returns true if the operands are equal.
- Not equal (!=): Returns true if the operands are not equal.
- Strict equal (===): Returns true when operands are equal and of the same type.
- Greater than (>), greater than or equal (>=)
- Less than (<), less than or equal (<=)

## Arithmetic Operators

- Standard arithmetic operators: addition (+), subtraction (-), multiplication (*), and division (/).
- There are other operators, i.e. remainder, increment, etc.

## For and While Statements

### For statement

A for loop repeats until a specified condition evaluates to false.
    
    //For loop structure
    for (initialization; condition; expression) {
        //code block to be executed
    }
    
    //Example:
    for (let i = 0; i < 10; i++) {
    console.log(i);
    }

### While statement

A while statement executes its statements until a specified condition evaluates to true.

    //While statement structure:

    while (condition){
    }

    //Example:
    let a = 0;
    let b = 0;
    while (a < 9) {
      a++;
      b += a;
      console.log(a);
    }

## Things I want to know more about

- Creating functions and loops with JavaScript

*References*

[https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators#comparison_operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators#comparison_operators)

[https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration#while_statement](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration#while_statement)
