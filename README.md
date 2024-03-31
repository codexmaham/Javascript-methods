# Javascript Methods: A comprehensive list
### Array Methods:

#### Manipulation:
- `push()`: Adds one or more elements to the end of an array.
- `pop()`: Removes the last element from an array and returns it.
- `shift()`: Removes the first element from an array and returns it.
- `unshift()`: Adds one or more elements to the beginning of an array.
- `splice()`: Adds or removes elements from an array.
- `concat()`: Returns a new array by combining existing arrays.
- `slice()`: Extracts a section of an array and returns a new array.

#### Iteration:
- `forEach()`: Executes a provided function once for each array element.
- `map()`: Creates a new array with the results of calling a provided function on every element.
- `filter()`: Creates a new array with elements that pass a test.
- `reduce()`: Applies a function against an accumulator and each element, reducing it to a single value.
- `some()`: Checks if at least one element in the array passes the test.
- `every()`: Checks if all elements in the array pass the test.
- `find()`: Returns the first element in the array that satisfies a provided function.
- `findIndex()`: Returns the index of the first element in the array that satisfies a provided function.

#### Searching and Sorting:
- `indexOf()`: Returns the first index at which a given element can be found.
- `lastIndexOf()`: Returns the last index at which a given element can be found.
- `includes()`: Determines whether an array contains a certain value.
- `sort()`: Sorts the elements of an array in place.

#### Conversion:
- `toString()`: Converts an array to a string.
- `join()`: Joins all elements of an array into a string.
- `valueOf()`: Returns the primitive value of an array.

#### Other:
- `flat()`: Flattens nested arrays.
- `flatMap()`: Maps each element using a mapping function, then flattens the result.

### String Methods:

#### Manipulation:
- `charAt()`: Returns the character at a specified index.
- `charCodeAt()`: Returns the Unicode value of the character at a specified index.
- `concat()`: Combines strings.
- `slice()`: Extracts a section of a string and returns it.
- `substring()`: Returns the characters between two indexes.
- `substr()`: Returns the characters in a string beginning at the specified location through the specified number of characters.
- `replace()`: Replaces text in a string.
- `padStart()`: Pads the current string with another string until the resulting string reaches the given length.
- `padEnd()`: Pads the current string with another string until the resulting string reaches the given length.

#### Searching and Matching:
- `indexOf()`: Returns the index of the first occurrence of a specified value.
- `lastIndexOf()`: Returns the index of the last occurrence of a specified value.
- `includes()`: Checks if a string contains a specified substring.
- `startsWith()`: Checks if a string starts with the specified substring.
- `endsWith()`: Checks if a string ends with the specified substring.
- `match()`: Searches a string for a match against a regular expression.
- `search()`: Searches a string for a specified value or regular expression.

#### Conversion:
- `toUpperCase()`: Converts a string to uppercase.
- `toLowerCase()`: Converts a string to lowercase.
- `trim()`: Removes whitespace from both ends of a string.
- `split()`: Splits a string into an array of substrings.
- `toString()`: Returns the value of a string.

#### Other:
- `localeCompare()`: Compares two strings.
- `normalize()`: Returns the Unicode Normalization Form of a string.
- `repeat()`: Constructs and returns a new string which contains the specified number of copies of the string on which it was called.

### Object Methods:

#### Property Management:
- `Object.keys()`: Returns an array of a given object's own enumerable property names.
- `Object.values()`: Returns an array of a given object's own enumerable property values.
- `Object.entries()`: Returns an array of a given object's own enumerable property key-value pairs.
- `Object.getOwnPropertyNames()`: Returns an array of all properties found directly upon a given object.

#### Prototype and Inheritance:
- `Object.getPrototypeOf()`: Returns the prototype of an object.
- `Object.setPrototypeOf()`: Sets the prototype of an object.

#### Miscellaneous:
- `Object.hasOwnProperty()`: Checks if a property is a direct property of the specified object.
- `Object.is()`: Compares two values for equality.
- `Object.isExtensible()`: Determines if an object is extensible.
- `Object.isSealed()`: Determines if an object is sealed.
- `Object.isFrozen()`: Determines if an object is frozen.

### Function Methods:

#### Execution Control:
- `Function.prototype.call()`: Calls a function with a given this value and arguments provided individually.
- `Function.prototype.apply()`: Calls a function with a given this value and arguments provided as an array.
- `Function.prototype.bind()`: Creates a new function with a specified this value and initial arguments.

#### Miscellaneous:
- `Function.prototype.toString()`: Returns a string representing the source code of the function.
- `Function.prototype.length`: Returns the number of formal parameters of the function.

### Number Methods:

#### Conversion:
- `Number.parseFloat()`: Parses a string argument and returns a floating-point number.
- `Number.parseInt()`: Parses a string argument and returns an integer.

#### Formatting:
- `Number.prototype.toFixed()`: Formats a number using fixed-point notation.
- `Number.prototype.toPrecision()`: Returns a string representing the number to a specified precision in fixed-point or exponential notation.
- `Number.prototype.toExponential()`: Returns a string representing the number in exponential notation.

#### Validation:
- `Number.isNaN()`: Determines whether a value is NaN.
- `Number.isFinite()`: Determines whether a value is a finite number.
- `Number.isInteger()`: Determines whether a value is an integer.

### Math Methods:

#### Basic Operations:
- `Math.abs()`: Returns the absolute value of a number.
- `Math.max()`: Returns the largest of zero or more numbers.
- `Math.min()`: Returns the smallest of zero or more numbers.
- `Math.pow()`: Returns the base to the exponent power.
- `Math.sqrt()`: Returns the square root of a number.
- `Math.round()`: Returns the value of a number rounded to the nearest integer.
- `Math.floor()`: Returns the largest integer less than or equal to a given number.
- `Math.ceil()`: Returns the smallest integer greater than or equal to a given number.

#### Trigonometry:
- `Math.sin()`: Returns the sine of a number.
- `Math.cos()`: Returns the cosine of a number.
- `Math.tan()`: Returns the tangent of a number.
- `Math.acos()`: Returns the arccosine of a number.
- `Math.asin()`: Returns the arcsine of a number.
- `Math.atan()`: Returns the arctangent of a number.

#### Logarithms:
- `Math.log()`: Returns the natural logarithm (base e)



 of a number.
- `Math.log10()`: Returns the base 10 logarithm of a number.
- `Math.log2()`: Returns the base 2 logarithm of a number.

#### Randomness:
- `Math.random()`: Returns a pseudo-random number between 0 and 1.

#### Others:
- `Math.sign()`: Returns the sign of a number, indicating whether the number is positive, negative, or zero.
- `Math.trunc()`: Returns the integer part of a number by removing any fractional digits.
- `Math.PI`: Represents the ratio of the circumference of a circle to its diameter, approximately 3.14159.
- `Math.E`: Represents the base of the natural logarithm, approximately 2.718.

### Date Methods:

#### Construction and Access:
- `Date.now()`: Returns the number of milliseconds elapsed since January 1, 1970 00:00:00 UTC.
- `new Date()`: Creates a new Date object with the current date and time.
- `Date.parse()`: Parses a string representation of a date and returns the number of milliseconds since January 1, 1970, 00:00:00 UTC.

#### Conversion:
- `Date.prototype.toString()`: Converts a Date object to a string.
- `Date.prototype.toDateString()`: Returns the date portion of a Date object as a human-readable string.
- `Date.prototype.toISOString()`: Returns the date as a string using the ISO standard format.

#### Comparison:
- `Date.prototype.getTime()`: Returns the numeric value of the specified date as the number of milliseconds since January 1, 1970, 00:00:00 UTC.
- `Date.prototype.getTimezoneOffset()`: Returns the time-zone offset in minutes for the current locale.

### RegExp Methods:

#### Matching:
- `RegExp.prototype.test()`: Tests for a match in a string.
- `RegExp.prototype.exec()`: Executes a search for a match in a specified string.

### Promise Methods:

#### Creation and Composition:
- `Promise.resolve()`: Returns a Promise object that is resolved with a given value.
- `Promise.reject()`: Returns a Promise object that is rejected with a given reason.
- `Promise.all()`: Returns a single Promise that resolves when all of the promises in the iterable argument have resolved.
- `Promise.race()`: Returns a promise that resolves or rejects as soon as one of the promises in the iterable resolves or rejects.
- `Promise.allSettled()`: Returns a promise that resolves after all of the given promises have settled.

#### Execution and Handling:
- `Promise.prototype.then()`: Appends fulfillment and rejection handlers to the promise.
- `Promise.prototype.catch()`: Appends a rejection handler callback to the promise.
- `Promise.prototype.finally()`: Appends a handler to the promise.

### Set Methods:

#### Manipulation and Iteration:
- `Set.prototype.add()`: Adds a new element to the set.
- `Set.prototype.delete()`: Removes a specified element from the set.
- `Set.prototype.clear()`: Removes all elements from the set.
- `Set.prototype.has()`: Returns a boolean indicating whether an element exists in the set.
- `Set.prototype.entries()`: Returns a new iterator object that contains an array of [value, value] for each element in the Set object, in insertion order.
- `Set.prototype.values()`: Returns a new iterator object that contains the values for each element in the Set object in insertion order.
- `Set.prototype.forEach()`: Calls a provided function once for each value in the Set object, in insertion order.

### Map Methods:

#### Manipulation and Iteration:
- `Map.prototype.set()`: Sets the value for the key in the Map object.
- `Map.prototype.get()`: Returns the value associated with the specified key.
- `Map.prototype.delete()`: Removes any value associated with the specified key.
- `Map.prototype.clear()`: Removes all key/value pairs from the Map object.
- `Map.prototype.has()`: Returns a boolean indicating whether a value has been associated with the specified key.
- `Map.prototype.entries()`: Returns a new iterator object that contains an array of [key, value] for each element in the Map object in insertion order.
- `Map.prototype.keys()`: Returns a new iterator object that contains the keys for each element in the Map object in insertion order.
- `Map.prototype.values()`: Returns a new iterator object that contains the values for each element in the Map object in insertion order.
- `Map.prototype.forEach()`: Calls a provided function once for each key-value pair in the Map object, in insertion order.

### Error Methods:

#### Access and Control:
- `Error.prototype.toString()`: Returns a string representing the specified Error object.
- `Error.prototype.stack`: Returns a string representing the points in the code where the Error object was created and where it was thrown.

#### Creation:
- `Error.captureStackTrace()`: Captures the stack trace and saves it to the specified Error object.
