# Description:

We can pass values into a function with arguments. You can use a `return` statement to send a value back out of a function.

**Example**

```Js
function plusThree(num) {
  return num + 3;
}

const answer = plusThree(5);
```

`answer` has the value `8`.

`plusThree` takes an argument for `num` and returns a value equal to `num + 3`.

# Instructions:

Create a function `timesFive` that accepts one argument, multiplies it by `5`, and returns the new value.

# Solution:

```Js
function timesFive(argument) {
  var result = argument * 5;
  return result;
}
```
