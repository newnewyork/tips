# Tips

### Tip 1: The ternary operator
https://stackoverflow.com/questions/6208067/operators-instead-of-ifelse

The expression
    
    a ? b : c
    
evaluates to b if a is true and evaluates to c if a is false.

The expression
    
    b ?? c
    
evaluates to b if b is not null and evaluates to c if b is null.

If you write
    
    return a ? b : c;
    
or
    
    return b ?? c;
    
they will always return something.

For [2], you can write a function that returns the right value that performs your "multiple operations", but that's probably worse than just using if/else.
