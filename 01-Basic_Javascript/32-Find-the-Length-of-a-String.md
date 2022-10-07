# Description:

You can find the length of a `String` value by writing `.length` after the string variable or string literal.

```Js
console.log("Alan Peter".length);
```

The value `10` would be displayed in the console. Note that the space character between "Alan" and "Peter" is also counted.

For example, if we created a variable `const firstName = "Ada"`, we could find out how long the string `Ada` is by using the `firstName.length` property.

# Instructions:

Use the `.length` property to set `lastNameLength` to the number of characters in `lastName`.

# Code To Solve:

```Js
// Setup
let lastNameLength = 0;
const lastName = "Lovelace";

// Only change code below this line
lastNameLength = lastName;
```

# Solution:

```Js
// Setup
let lastNameLength = 0;
const lastName = "Lovelace";

// Only change code below this line
lastNameLength = lastName.length;
```
