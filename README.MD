const PI = 3.14

1. var is function scoped (can be accessed in the entire function even when nested in a code block), let is block scoped (can be accessed in the entire code block, but if nested in a code block inside of a function cant acces outside that block)
var can be redeclared, let cannot be reddeclared

2. var is function scoped, const is block scoped just like let / var can be reassigned and redeclared, const can be neither

3. let can be reassigned, const cannot be 

4. hoisting is when you declare a variable with var the function expression (var =) is viewed at the top of the page - so if you try to access a variable declared with var before it is written you will get undefined and not an error of cant access variable before its declared like you would with a let or const declared variable
