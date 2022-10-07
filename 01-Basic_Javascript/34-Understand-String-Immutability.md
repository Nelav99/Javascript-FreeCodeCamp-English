# Description:

In JavaScript, `String` values are immutable, which means that they cannot be altered once created.

For example, the following code will produce an error because the letter `B` in the string `Bob` cannot be changed to the letter J:

```Js
let myStr = "Bob";
myStr[0] = "J";
```

Note that this does not mean that `myStr` could not be re-assigned. The only way to change `myStr` would be to assign it with a new value, like this:

```Js
let myStr = "Bob";
myStr = "Job";
```

# Instructions:

Correct the assignment to `myStr` so it contains the string value of `Hello World` using the approach shown in the example above.

# Code To Solve:

```Js
// Setup
let myStr = "Jello World";

// Only change code below this line
myStr[0] = "H"; // Change this line
// Only change code above this line
```

# Solution:

```Js
// Setup
let myStr = "Jello World";

// Only change code below this line
myStr = "Hello World"; // Change this line
// Only change code above this line
```
