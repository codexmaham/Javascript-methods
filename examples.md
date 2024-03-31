
### Array Methods:
#### Manipulation:
- **push():**
  ```javascript
  let arr = [1, 2, 3];
  arr.push(4);
  console.log(arr); // Output: [1, 2, 3, 4]
  ```

- **pop():**
  ```javascript
  let arr = [1, 2, 3];
  let popped = arr.pop();
  console.log(popped); // Output: 3
  ```

- **shift():**
  ```javascript
  let arr = [1, 2, 3];
  let shifted = arr.shift();
  console.log(shifted); // Output: 1
  ```

- **unshift():**
  ```javascript
  let arr = [1, 2, 3];
  arr.unshift(0);
  console.log(arr); // Output: [0, 1, 2, 3]
  ```

- **splice():**
  ```javascript
  let arr = [1, 2, 3, 4];
  arr.splice(1, 2, 'a', 'b');
  console.log(arr); // Output: [1, 'a', 'b', 4]
  ```

- **concat():**
  ```javascript
  let arr1 = [1, 2];
  let arr2 = [3, 4];
  let newArr = arr1.concat(arr2);
  console.log(newArr); // Output: [1, 2, 3, 4]
  ```

- **slice():**
  ```javascript
  let arr = [1, 2, 3, 4, 5];
  let sliced = arr.slice(1, 4);
  console.log(sliced); // Output: [2, 3, 4]
  ```

#### Iteration:
- **forEach():**
  ```javascript
  let arr = [1, 2, 3];
  arr.forEach(element => console.log(element));
  // Output:
  // 1
  // 2
  // 3
  ```

- **map():**
  ```javascript
  let arr = [1, 2, 3];
  let mapped = arr.map(element => element * 2);
  console.log(mapped); // Output: [2, 4, 6]
  ```

- **filter():**
  ```javascript
  let arr = [1, 2, 3, 4, 5];
  let filtered = arr.filter(element => element % 2 === 0);
  console.log(filtered); // Output: [2, 4]
  ```

- **reduce():**
  ```javascript
  let arr = [1, 2, 3, 4];
  let reduced = arr.reduce((acc, cur) => acc + cur, 0);
  console.log(reduced); // Output: 10
  ```

- **some():**
  ```javascript
  let arr = [1, 2, 3, 4, 5];
  let hasEven = arr.some(element => element % 2 === 0);
  console.log(hasEven); // Output: true
  ```

- **every():**
  ```javascript
  let arr = [2, 4, 6, 8];
  let allEven = arr.every(element => element % 2 === 0);
  console.log(allEven); // Output: true
  ```

- **find():**
  ```javascript
  let arr = [1, 2, 3, 4, 5];
  let found = arr.find(element => element > 3);
  console.log(found); // Output: 4
  ```

- **findIndex():**
  ```javascript
  let arr = [1, 2, 3, 4, 5];
  let foundIndex = arr.findIndex(element => element > 3);
  console.log(foundIndex); // Output: 3
  ```

#### Searching and Sorting:
- **indexOf():**
  ```javascript
  let arr = [1, 2, 3, 4, 5];
  let index = arr.indexOf(3);
  console.log(index); // Output: 2
  ```

- **lastIndexOf():**
  ```javascript
  let arr = [1, 2, 3, 4, 3];
  let lastIndex = arr.lastIndexOf(3);
  console.log(lastIndex); // Output: 4
  ```

- **includes():**
  ```javascript
  let arr = [1, 2, 3, 4, 5];
  let includes = arr.includes(3);
  console.log(includes); // Output: true
  ```

- **sort():**
  ```javascript
  let arr = [3, 1, 4, 1, 5, 9];
  arr.sort();
  console.log(arr); // Output: [1, 1, 3, 4, 5, 9]
  ```

#### Conversion:
- **toString():**
  ```javascript
  let arr = [1, 2, 3];
  let str = arr.toString();
  console.log(str); // Output: '1,2,3'
  ```

- **join():**
  ```javascript
  let arr = [1, 2, 3];
  let joined = arr.join('-');
  console.log(joined); // Output: '1-2-3'
  ```

- **valueOf():**
  ```javascript
  let arr = [1, 2, 3];
  let value = arr.valueOf();
  console.log(value); // Output: [1, 2, 3]
  ```

#### Other:
- **flat():**
  ```javascript
  let arr = [1, [2, 3], [4, [5]]];
  let flat = arr.flat(2);
  console.log(flat); // Output: [1, 2, 3, 4, 5]
  ```

- **flatMap():**
  ```javascript
  let arr = [1, 2, 3];
  let flatMapped = arr.flatMap(x => [x * 2]);
  console.log(flatMapped); // Output: [2, 4, 6]
  ```

### String Methods:
#### Manipulation:
- **charAt():**
  ```javascript
  let str = 'Hello';
  let char = str.charAt(0);
  console.log(char); // Output: 'H'
  ```

- **charCodeAt():**
  ```javascript
  let str = 'Hello';
  let charCode = str.charCodeAt(0);
  console.log(charCode); // Output: 72
  ```

- **concat():**
  ```javascript
  let str1 = 'Hello';
  let str2 = ' World!';
  let concatenated = str1.concat(str2);
  console.log(concatenated); // Output: 'Hello World!'
  ```

- **slice():**
  ```javascript
  let str = 'Hello World!';
  let sliced = str.slice(6, 11);
  console.log(sliced);

 // Output: 'World'
  ```

- **substring():**
  ```javascript
  let str = 'Hello World!';
  let sub = str.substring(6, 11);
  console.log(sub); // Output: 'World'
  ```

- **substr():**
  ```javascript
  let str = 'Hello World!';
  let substr = str.substr(6, 5);
  console.log(substr); // Output: 'World'
  ```

- **replace():**
  ```javascript
  let str = 'Hello World!';
  let replaced = str.replace('World', 'Universe');
  console.log(replaced); // Output: 'Hello Universe!'
  ```

- **padStart():**
  ```javascript
  let str = '7';
  let padded = str.padStart(3, '0');
  console.log(padded); // Output: '007'
  ```

- **padEnd():**
  ```javascript
  let str = '7';
  let padded = str.padEnd(3, '0');
  console.log(padded); // Output: '700'
  ```

#### Searching and Matching:
- **indexOf():**
  ```javascript
  let str = 'Hello World!';
  let index = str.indexOf('World');
  console.log(index); // Output: 6
  ```

- **lastIndexOf():**
  ```javascript
  let str = 'Hello World!';
  let lastIndex = str.lastIndexOf('o');
  console.log(lastIndex); // Output: 7
  ```

- **includes():**
  ```javascript
  let str = 'Hello World!';
  let includes = str.includes('World');
  console.log(includes); // Output: true
  ```

- **startsWith():**
  ```javascript
  let str = 'Hello World!';
  let startsWith = str.startsWith('Hello');
  console.log(startsWith); // Output: true
  ```

- **endsWith():**
  ```javascript
  let str = 'Hello World!';
  let endsWith = str.endsWith('World!');
  console.log(endsWith); // Output: true
  ```

- **match():**
  ```javascript
  let str = 'Hello World!';
  let matched = str.match(/\w+/g);
  console.log(matched); // Output: ['Hello', 'World']
  ```

- **search():**
  ```javascript
  let str = 'Hello World!';
  let position = str.search('World');
  console.log(position); // Output: 6
  ```

#### Conversion:
- **toUpperCase():**
  ```javascript
  let str = 'hello world';
  let upperCase = str.toUpperCase();
  console.log(upperCase); // Output: 'HELLO WORLD'
  ```

- **toLowerCase():**
  ```javascript
  let str = 'HELLO WORLD';
  let lowerCase = str.toLowerCase();
  console.log(lowerCase); // Output: 'hello world'
  ```

- **trim():**
  ```javascript
  let str = '   Hello World!   ';
  let trimmed = str.trim();
  console.log(trimmed); // Output: 'Hello World!'
  ```

- **split():**
  ```javascript
  let str = 'Hello,World';
  let splitted = str.split(',');
  console.log(splitted); // Output: ['Hello', 'World']
  ```

#### Other:
- **localeCompare():**
  ```javascript
  let str1 = 'apple';
  let str2 = 'banana';
  let result = str1.localeCompare(str2);
  console.log(result); // Output: -1 (indicating 'apple' comes before 'banana' in alphabetical order)
  ```

- **normalize():**
  ```javascript
  let str = '\u1E9B\u0323'; // Latin Small Letter Long S With Dot Above and Dot Below
  let normalized = str.normalize();
  console.log(normalized); // Output: 'ṩ̣' (normalized form)
  ```

- **repeat():**
  ```javascript
  let str = 'Hello';
  let repeated = str.repeat(3);
  console.log(repeated); // Output: 'HelloHelloHello'
  ```

### Object Methods:
#### Property Management:
- **Object.keys():**
  ```javascript
  let obj = { a: 1, b: 2, c: 3 };
  let keys = Object.keys(obj);
  console.log(keys); // Output: ['a', 'b', 'c']
  ```

- **Object.values():**
  ```javascript
  let obj = { a: 1, b: 2, c: 3 };
  let values = Object.values(obj);
  console.log(values); // Output: [1, 2, 3]
  ```

- **Object.entries():**
  ```javascript
  let obj = { a: 1, b: 2, c: 3 };
  let entries = Object.entries(obj);
  console.log(entries); // Output: [['a', 1], ['b', 2], ['c', 3]]
  ```

- **Object.getOwnPropertyNames():**
  ```javascript
  let obj = { a: 1, b: 2, c: 3 };
  let properties = Object.getOwnPropertyNames(obj);
  console.log(properties); // Output: ['a', 'b', 'c']
  ```

#### Prototype and Inheritance:
- **Object.getPrototypeOf():**
  ```javascript
  let obj = {};
  let proto = Object.getPrototypeOf(obj);
  console.log(proto === Object.prototype); // Output: true
  ```

- **Object.setPrototypeOf():**
  ```javascript
  let obj = {};
  let proto = {};
  Object.setPrototypeOf(obj, proto);
  console.log(Object.getPrototypeOf(obj) === proto); // Output: true
  ```

#### Miscellaneous:
- **Object.hasOwnProperty():**
  ```javascript
  let obj = { a: 1, b: 2 };
  console.log(obj.hasOwnProperty('a')); // Output: true
  console.log(obj.hasOwnProperty('toString')); // Output: false
  ```

- **Object.is():**
  ```javascript
  console.log(Object.is(1, 1)); // Output: true
  console.log(Object.is({}, {})); // Output: false (different objects)
  ```

- **Object.isExtensible():**
  ```javascript
  let obj = {};
  console.log(Object.isExtensible(obj)); // Output: true
  Object.preventExtensions(obj);
  console.log(Object.isExtensible(obj)); // Output: false
  ```

- **Object.isSealed():**
  ```javascript
  let obj = {};
  console.log(Object.isSealed(obj)); // Output: false
  Object.seal(obj);
  console.log(Object.isSealed(obj)); // Output: true
  ```

- **Object.isFrozen():**
  ```javascript
  let obj = {};
  console.log(Object.isFrozen(obj)); // Output: false
  Object.freeze(obj);
  console.log(Object.isFrozen(obj)); // Output: true
  ```

### Function Methods:
#### Execution Control:
- **Function.prototype.call():**
  ```javascript
  function greet() {
    return `Hello, ${this.name}!`;
  }
  let person = { name: 'Alice' };
  console.log(greet.call(person

)); // Output: 'Hello, Alice!'
  ```

- **Function.prototype.apply():**
  ```javascript
  function greet() {
    return `Hello, ${this.name}!`;
  }
  let person = { name: 'Alice' };
  console.log(greet.apply(person)); // Output: 'Hello, Alice!'
  ```

- **Function.prototype.bind():**
  ```javascript
  function greet() {
    return `Hello, ${this.name}!`;
  }
  let person = { name: 'Alice' };
  let boundGreet = greet.bind(person);
  console.log(boundGreet()); // Output: 'Hello, Alice!'
  ```

#### Miscellaneous:
- **Function.prototype.toString():**
  ```javascript
  function add(a, b) {
    return a + b;
  }
  console.log(add.toString()); // Output: 'function add(a, b) { return a + b; }'
  ```

- **Function.prototype.length:**
  ```javascript
  function add(a, b) {
    return a + b;
  }
  console.log(add.length); // Output: 2 (number of formal parameters)
  ```

### Number Methods:
#### Conversion:
- **Number.parseFloat():**
  ```javascript
  let numStr = '3.14';
  let num = Number.parseFloat(numStr);
  console.log(num); // Output: 3.14
  ```

- **Number.parseInt():**
  ```javascript
  let numStr = '42';
  let num = Number.parseInt(numStr);
  console.log(num); // Output: 42
  ```

#### Formatting:
- **Number.prototype.toFixed():**
  ```javascript
  let num = 3.14159;
  let formatted = num.toFixed(2);
  console.log(formatted); // Output: '3.14'
  ```

- **Number.prototype.toPrecision():**
  ```javascript
  let num = 1234.56789;
  let formatted = num.toPrecision(4);
  console.log(formatted); // Output: '1235'
  ```

- **Number.prototype.toExponential():**
  ```javascript
  let num = 12345;
  let formatted = num.toExponential(2);
  console.log(formatted); // Output: '1.23e+4'
  ```

#### Validation:
- **Number.isNaN():**
  ```javascript
  console.log(Number.isNaN(NaN)); // Output: true
  ```

- **Number.isFinite():**
  ```javascript
  console.log(Number.isFinite(42)); // Output: true
  console.log(Number.isFinite(Infinity)); // Output: false
  ```

- **Number.isInteger():**
  ```javascript
  console.log(Number.isInteger(42)); // Output: true
  console.log(Number.isInteger(42.5)); // Output: false
  ```

### Math Methods:
#### Basic Operations:
- **Math.abs():**
  ```javascript
  console.log(Math.abs(-42)); // Output: 42
  ```

- **Math.max():**
  ```javascript
  console.log(Math.max(1, 2, 3)); // Output: 3
  ```

- **Math.min():**
  ```javascript
  console.log(Math.min(1, 2, 3)); // Output: 1
  ```

- **Math.pow():**
  ```javascript
  console.log(Math.pow(2, 3)); // Output: 8
  ```

- **Math.sqrt():**
  ```javascript
  console.log(Math.sqrt(9)); // Output: 3
  ```

- **Math.round():**
  ```javascript
  console.log(Math.round(3.14)); // Output: 3
  ```

- **Math.floor():**
  ```javascript
  console.log(Math.floor(3.9)); // Output: 3
  ```

- **Math.ceil():**
  ```javascript
  console.log(Math.ceil(3.1)); // Output: 4
  ```

#### Trigonometry:
- **Math.sin():**
  ```javascript
  console.log(Math.sin(Math.PI / 2)); // Output: 1
  ```

- **Math.cos():**
  ```javascript
  console.log(Math.cos(0)); // Output: 1
  ```

- **Math.tan():**
  ```javascript
  console.log(Math.tan(Math.PI / 4)); // Output: 1
  ```

- **Math.acos():**
  ```javascript
  console.log(Math.acos(0)); // Output: 1.5707963267948966 (approximately π/2)
  ```

- **Math.asin():**
  ```javascript
  console.log(Math.asin(1)); // Output: 1.5707963267948966 (approximately π/2)
  ```

- **Math.atan():**
  ```javascript
  console.log(Math.atan(1)); // Output: 0.7853981633974483 (approximately π/4)
  ```

#### Logarithms:
- **Math.log():**
  ```javascript
  console.log(Math.log(Math.E)); // Output: 1
  ```

- **Math.log10():**
  ```javascript
  console.log(Math.log10(100)); // Output: 2
  ```

- **Math.log2():**
  ```javascript
  console.log(Math.log2(8)); // Output: 3
  ```

#### Randomness:
- **Math.random():**
  ```javascript
  console.log(Math.random()); // Output: (random number between 0 and 1)
  ```

#### Others:
- **Math.sign():**
  ```javascript
  console.log(Math.sign(-42)); // Output: -1 (negative)
  console.log(Math.sign(0)); // Output: 0 (zero)
  console.log(Math.sign(42)); // Output: 1 (positive)
  ```

- **Math.trunc():**
  ```javascript
  console.log(Math.trunc(42.5)); // Output: 42
  ```

- **Math.PI:**
  ```javascript
  console.log(Math.PI); // Output: 3.141592653589793
  ```

- **Math.E:**
  ```javascript
  console.log(Math.E); // Output: 2.718281828459045
  ```

### Date Methods:
#### Construction and Access:
- **Date.now():**
  ```javascript
  console.log(Date.now()); // Output: (current timestamp in milliseconds)
  ```

- **new Date():**
  ```javascript
  console.log(new Date()); // Output: (current date and time)
  ```

- **Date.parse():**
  ```javascript
  console.log(Date.parse('2023-12-31')); // Output: (timestamp of the specified date)
  ```

#### Conversion:
- **Date.prototype.toString():**
  ```javascript
  let date = new Date();
  console.log(date.toString()); // Output: (string representation of the date)
  ```

- **Date.prototype.toDateString():**
  ```javascript
  let date = new Date();
  console.log(date.toDateString()); // Output: (date portion as a human-readable string)
  ```

- **Date.prototype.toISOString

():**
  ```javascript
  let date = new Date();
  console.log(date.toISOString()); // Output: (date as a string in ISO format)
  ```

#### Comparison:
- **Date.prototype.getTime():**
  ```javascript
  let date = new Date();
  console.log(date.getTime()); // Output: (timestamp in milliseconds)
  ```

- **Date.prototype.getTimezoneOffset():**
  ```javascript
  let date = new Date();
  console.log(date.getTimezoneOffset()); // Output: (time-zone offset in minutes)
  ```

### RegExp Methods:
#### Matching:
- **RegExp.prototype.test():**
  ```javascript
  let regex = /\d+/;
  console.log(regex.test('123')); // Output: true
  ```

- **RegExp.prototype.exec():**
  ```javascript
  let regex = /(\d+)/g;
  let result = regex.exec('123 456');
  console.log(result); // Output: ['123', '123']
  ```

### Promise Methods:
#### Creation and Composition:
- **Promise.resolve():**
  ```javascript
  let resolvedPromise = Promise.resolve(42);
  resolvedPromise.then(value => console.log(value)); // Output: 42
  ```

- **Promise.reject():**
  ```javascript
  let rejectedPromise = Promise.reject('Error');
  rejectedPromise.catch(error => console.error(error)); // Output: 'Error'
  ```

- **Promise.all():**
  ```javascript
  let promises = [Promise.resolve(1), Promise.resolve(2)];
  Promise.all(promises).then(values => console.log(values)); // Output: [1, 2]
  ```

- **Promise.race():**
  ```javascript
  let promises = [Promise.resolve(1), Promise.reject('Error')];
  Promise.race(promises).then(value => console.log(value)); // Output: 1
  ```

- **Promise.allSettled():**
  ```javascript
  let promises = [Promise.resolve(1), Promise.reject('Error')];
  Promise.allSettled(promises).then(results => console.log(results));
  // Output: [{ status: 'fulfilled', value: 1 }, { status: 'rejected', reason: 'Error' }]
  ```

#### Execution and Handling:
- **Promise.prototype.then():**
  ```javascript
  let promise = new Promise((resolve, reject) => {
    setTimeout(() => resolve('Done!'), 1000);
  });
  promise.then(value => console.log(value)); // Output: 'Done!' (after 1 second)
  ```

- **Promise.prototype.catch():**
  ```javascript
  let promise = new Promise((resolve, reject) => {
    setTimeout(() => reject('Error!'), 1000);
  });
  promise.catch(error => console.error(error)); // Output: 'Error!' (after 1 second)
  ```

- **Promise.prototype.finally():**
  ```javascript
  let promise = new Promise((resolve, reject) => {
    setTimeout(() => resolve('Done!'), 1000);
  });
  promise.finally(() => console.log('Finished')); // Output: 'Finished' (after 1 second)
  ```

### Set Methods:
#### Manipulation and Iteration:
- **Set.prototype.add():**
  ```javascript
  let set = new Set();
  set.add(1).add(2).add(3);
  console.log(set); // Output: Set { 1, 2, 3 }
  ```

- **Set.prototype.delete():**
  ```javascript
  let set = new Set([1, 2, 3]);
  set.delete(2);
  console.log(set); // Output: Set { 1, 3 }
  ```

- **Set.prototype.clear():**
  ```javascript
  let set = new Set([1, 2, 3]);
  set.clear();
  console.log(set); // Output: Set {}
  ```

- **Set.prototype.has():**
  ```javascript
  let set = new Set([1, 2, 3]);
  console.log(set.has(2)); // Output: true
  ```

- **Set.prototype.entries():**
  ```javascript
  let set = new Set([1, 2, 3]);
  let iterator = set.entries();
  console.log(iterator.next().value); // Output: [1, 1]
  ```

- **Set.prototype.values():**
  ```javascript
  let set = new Set([1, 2, 3]);
  let iterator = set.values();
  console.log(iterator.next().value); // Output: 1
  ```

- **Set.prototype.forEach():**
  ```javascript
  let set = new Set([1, 2, 3]);
  set.forEach(value => console.log(value));
  // Output:
  // 1
  // 2
  // 3
  ```

### Map Methods:
#### Manipulation and Iteration:
- **Map.prototype.set():**
  ```javascript
  let map = new Map();
  map.set('a', 1).set('b', 2).set('c', 3);
  console.log(map); // Output: Map { 'a' => 1, 'b' => 2, 'c' => 3 }
  ```

- **Map.prototype.get():**
  ```javascript
  let map = new Map([['a', 1], ['b', 2], ['c', 3]]);
  console.log(map.get('b')); // Output: 2
  ```

- **Map.prototype.delete():**
  ```javascript
  let map = new Map([['a', 1], ['b', 2], ['c', 3]]);
  map.delete('b');
  console.log(map); // Output: Map { 'a' => 1, 'c' => 3 }
  ```

- **Map.prototype.clear():**
  ```javascript
  let map = new Map([['a', 1], ['b', 2], ['c', 3]]);
  map.clear();
  console.log(map); // Output: Map {}
  ```

- **Map.prototype.has():**
  ```javascript
  let map = new Map([['a', 1], ['b', 2], ['c', 3]]);
  console.log(map.has('b')); // Output

: true
  ```

- **Map.prototype.entries():**
  ```javascript
  let map = new Map([['a', 1], ['b', 2], ['c', 3]]);
  let iterator = map.entries();
  console.log(iterator.next().value); // Output: ['a', 1]
  ```

- **Map.prototype.keys():**
  ```javascript
  let map = new Map([['a', 1], ['b', 2], ['c', 3]]);
  let iterator = map.keys();
  console.log(iterator.next().value); // Output: 'a'
  ```

- **Map.prototype.values():**
  ```javascript
  let map = new Map([['a', 1], ['b', 2], ['c', 3]]);
  let iterator = map.values();
  console.log(iterator.next().value); // Output: 1
  ```

- **Map.prototype.forEach():**
  ```javascript
  let map = new Map([['a', 1], ['b', 2], ['c', 3]]);
  map.forEach((value, key) => console.log(key, value));
  // Output:
  // 'a' 1
  // 'b' 2
  // 'c' 3
  ```

### Error Methods:
#### Access and Control:
- **Error.prototype.toString():**
  ```javascript
  let error = new Error('Custom Error');
  console.log(error.toString()); // Output: 'Error: Custom Error'
  ```

- **Error.prototype.stack:**
  ```javascript
  let error = new Error('Custom Error');
  console.log(error.stack);
  // Output:
  // Error: Custom Error
  //     at <anonymous>:1:13
  ```

#### Creation:
- **Error.captureStackTrace():**
  ```javascript
  let error = {};
  Error.captureStackTrace(error);
  console.log(error.stack);
  // Output:
  // Error
  //     at <anonymous>:1:13
  ```

