# Description:

If you'll recall from our discussion about <a href="https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/storing-values-with-the-assignment-operator">Storing Values with the Assignment Operator</a>, everything to the right of the equal sign is resolved before the value is assigned. This means we can take the return value of a function and assign it to a variable.

Assume we have pre-defined a function `sum` which adds two numbers together, then:


```Js
ourSum = sum(5, 12);
```

will call the `sum` function, which returns a value of `17` and assigns it to the `ourSum` variable.

# Instructions:

Call the `processArg` function with an argument of `7` and assign its return value to the variable `processed`.

# Code To Solve:

```Js
// Setup
let processed = 0;

function processArg(num) {
  return (num + 3) / 5;
}

// Only change code below this line

```

# Solution:

```Js
// Setup
let processed = 0;

function processArg(num) {
  return (num + 3) / 5;
}

// Only change code below this line
processed = processArg(7);
```
