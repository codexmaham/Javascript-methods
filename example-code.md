
### Array Methods:

#### Manipulation:
- `push()`:
  ```javascript
  let arr = [1, 2, 3];
  arr.push(4);
  console.log(arr); // Output: [1, 2, 3, 4]
  ```

- `pop()`:
  ```javascript
  let arr = [1, 2, 3];
  let removedElement = arr.pop();
  console.log(removedElement); // Output: 3
  console.log(arr); // Output: [1, 2]
  ```

- `shift()`:
  ```javascript
  let arr = [1, 2, 3];
  let removedElement = arr.shift();
  console.log(removedElement); // Output: 1
  console.log(arr); // Output: [2, 3]
  ```

- `unshift()`:
  ```javascript
  let arr = [2, 3];
  arr.unshift(1);
  console.log(arr); // Output: [1, 2, 3]
  ```

- `splice()`:
  ```javascript
  let arr = [1, 2, 3, 4];
  arr.splice(1, 2, 'a', 'b');
  console.log(arr); // Output: [1, 'a', 'b', 4]
  ```

- `concat()`:
  ```javascript
  let arr1 = [1, 2];
  let arr2 = [3, 4];
  let newArr = arr1.concat(arr2);
  console.log(newArr); // Output: [1, 2, 3, 4]
  ```

- `slice()`:
  ```javascript
  let arr = [1, 2, 3, 4];
  let newArr = arr.slice(1, 3);
  console.log(newArr); // Output: [2, 3]
  ```

#### Iteration:
- `forEach()`:
  ```javascript
  let arr = [1, 2, 3];
  arr.forEach(element => console.log(element));
  // Output:
  // 1
  // 2
  // 3
  ```

- `map()`:
  ```javascript
  let arr = [1, 2, 3];
  let newArr = arr.map(element => element * 2);
  console.log(newArr); // Output: [2, 4, 6]
  ```

- `filter()`:
  ```javascript
  let arr = [1, 2, 3, 4];
  let newArr = arr.filter(element => element % 2 === 0);
  console.log(newArr); // Output: [2, 4]
  ```

- `reduce()`:
  ```javascript
  let arr = [1, 2, 3, 4];
  let sum = arr.reduce((acc, curr) => acc + curr, 0);
  console.log(sum); // Output: 10
  ```

- `some()`:
  ```javascript
  let arr = [1, 2, 3, 4];
  let hasEven = arr.some(element => element % 2 === 0);
  console.log(hasEven); // Output: true
  ```

- `every()`:
  ```javascript
  let arr = [1, 2, 3, 4];
  let allEven = arr.every(element => element % 2 === 0);
  console.log(allEven); // Output: false
  ```

- `find()`:
  ```javascript
  let arr = [1, 2, 3, 4];
  let found = arr.find(element => element > 2);
  console.log(found); // Output: 3
  ```

- `findIndex()`:
  ```javascript
  let arr = [1, 2, 3, 4];
  let foundIndex = arr.findIndex(element => element > 2);
  console.log(foundIndex); // Output: 2 (index of 3)
  ```

#### Searching and Sorting:
- `indexOf()`:
  ```javascript
  let arr = [1, 2, 3, 4, 1];
  let index = arr.indexOf(1);
  console.log(index); // Output: 0 (first occurrence)
  ```

- `lastIndexOf()`:
  ```javascript
  let arr = [1, 2, 3, 4, 1];
  let lastIndex = arr.lastIndexOf(1);
  console.log(lastIndex); // Output: 4 (last occurrence)
  ```

- `includes()`:
  ```javascript
  let arr = [1, 2, 3, 4];
  let includesThree = arr.includes(3);
  console.log(includesThree); // Output: true
  ```

- `sort()`:
  ```javascript
  let arr = [3, 1, 4, 1, 5];
  arr.sort();
  console.log(arr); // Output: [1, 1, 3, 4, 5]
  ```

#### Conversion:
- `toString()`:
  ```javascript
  let arr = [1, 2, 3];
  let str = arr.toString();
  console.log(str); // Output: "1,2,3"
  ```

- `join()`:
  ```javascript
  let arr = [1, 2, 3];
  let joinedStr = arr.join('-');
  console.log(joinedStr); // Output: "1-2-3"
  ```

- `valueOf()`:
  ```javascript
  let arr = [1, 2, 3];
  let value = arr.valueOf();
  console.log(value); // Output: [1, 2, 3]
  ```

#### Other:
- `flat()`:
  ```javascript


  let arr = [1, [2, 3], [4, [5]]];
  let flatArr = arr.flat(2);
  console.log(flatArr); // Output: [1, 2, 3, 4, 5]
  ```

- `flatMap()`:
  ```javascript
  let arr = [1, 2, 3];
  let mappedArr = arr.flatMap(x => [x * 2]);
  console.log(mappedArr); // Output: [2, 4, 6]
  ```

### String Methods:

#### Manipulation:
- `charAt()`:
  ```javascript
  let str = 'Hello';
  console.log(str.charAt(1)); // Output: 'e'
  ```

- `charCodeAt()`:
  ```javascript
  let str = 'Hello';
  console.log(str.charCodeAt(1)); // Output: 101 (Unicode value of 'e')
  ```

- `concat()`:
  ```javascript
  let str1 = 'Hello';
  let str2 = 'World';
  let concatStr = str1.concat(' ', str2);
  console.log(concatStr); // Output: 'Hello World'
  ```

- `slice()`:
  ```javascript
  let str = 'Hello World';
  let slicedStr = str.slice(6);
  console.log(slicedStr); // Output: 'World'
  ```

- `substring()`:
  ```javascript
  let str = 'Hello World';
  let subStr = str.substring(6, 11);
  console.log(subStr); // Output: 'World'
  ```

- `substr()`:
  ```javascript
  let str = 'Hello World';
  let subStr = str.substr(6, 5);
  console.log(subStr); // Output: 'World'
  ```

- `replace()`:
  ```javascript
  let str = 'Hello World';
  let replacedStr = str.replace('World', 'JavaScript');
  console.log(replacedStr); // Output: 'Hello JavaScript'
  ```

- `padStart()`:
  ```javascript
  let str = '5';
  console.log(str.padStart(2, '0')); // Output: '05'
  ```

- `padEnd()`:
  ```javascript
  let str = '5';
  console.log(str.padEnd(2, '0')); // Output: '50'
  ```

#### Searching and Matching:
- `indexOf()`:
  ```javascript
  let str = 'Hello World';
  let index = str.indexOf('World');
  console.log(index); // Output: 6
  ```

- `lastIndexOf()`:
  ```javascript
  let str = 'Hello World Hello';
  let lastIndex = str.lastIndexOf('Hello');
  console.log(lastIndex); // Output: 12
  ```

- `includes()`:
  ```javascript
  let str = 'Hello World';
  let includesWorld = str.includes('World');
  console.log(includesWorld); // Output: true
  ```

- `startsWith()`:
  ```javascript
  let str = 'Hello World';
  let startsWithHello = str.startsWith('Hello');
  console.log(startsWithHello); // Output: true
  ```

- `endsWith()`:
  ```javascript
  let str = 'Hello World';
  let endsWithWorld = str.endsWith('World');
  console.log(endsWithWorld); // Output: true
  ```

- `match()`:
  ```javascript
  let str = 'Hello World';
  let matched = str.match(/Hello/g);
  console.log(matched); // Output: ['Hello']
  ```

- `search()`:
  ```javascript
  let str = 'Hello World';
  let position = str.search('World');
  console.log(position); // Output: 6
  ```

#### Conversion:
- `toUpperCase()`:
  ```javascript
  let str = 'hello';
  let upperCaseStr = str.toUpperCase();
  console.log(upperCaseStr); // Output: 'HELLO'
  ```

- `toLowerCase()`:
  ```javascript
  let str = 'HELLO';
  let lowerCaseStr = str.toLowerCase();
  console.log(lowerCaseStr); // Output: 'hello'
  ```

- `trim()`:
  ```javascript
  let str = '  Hello World  ';
  let trimmedStr = str.trim();
  console.log(trimmedStr); // Output: 'Hello World'
  ```

- `split()`:
  ```javascript
  let str = 'apple,orange,banana';
  let splitArr = str.split(',');
  console.log(splitArr); // Output: ['apple', 'orange', 'banana']
  ```

#### Other:
- `localeCompare()`:
  ```javascript
  let str1 = 'apple';
  let str2 = 'banana';
  console.log(str1.localeCompare(str2)); // Output: -1
  ```

- `normalize()`:
  ```javascript
  let str = '\u006E\u0303';
  console.log(str.normalize()); // Output: 'ñ'
  ```

- `repeat()`:
  ```javascript
  let str = 'Hello';
  console.log(str.repeat(3)); // Output: 'HelloHelloHello'
  ```

### Object Methods:

#### Property Management:
- `Object.keys()`:
  ```javascript
  let obj = { a: 1, b: 2, c: 3 };
  let keys = Object.keys(obj);
  console.log(keys); // Output: ['a', 'b', 'c']
  ```

- `Object.values()`:
  ```javascript
  let obj = { a: 1, b: 2, c: 3 };
  let values = Object.values(obj);
  console.log(values); // Output: [1, 2, 3]
  ```

- `Object.entries()`:
  ```javascript
  let obj = { a: 1, b: 2, c: 3 };
  let entries = Object.entries(obj);
  console.log(entries); // Output: [['a', 1], ['b', 2], ['c', 3]]
  ```

- `Object.getOwnPropertyNames()`:
  ```javascript
  let obj = { a: 1, b: 2 };
  let props = Object.getOwnPropertyNames(obj);
  console.log(props); // Output: ['a', 'b']
  ```

#### Prototype and Inheritance:
- `Object.getPrototypeOf()`:
  ```javascript
  let obj = {};
  console.log(Object.getPrototypeOf(obj) === Object.prototype); // Output: true
  ```

- `Object.setPrototypeOf()`:
  ```javascript
  let obj = {};
  let protoObj = { a: 1 };
  Object.setPrototypeOf(obj, protoObj);
  console.log(obj.a); // Output: 1
  ```

#### Miscellaneous:
- `Object.hasOwnProperty()`:
  ```javascript
  let obj = { a: 1 };
  console.log(obj.hasOwnProperty('a')); // Output: true
  console.log(obj.hasOwnProperty('b')); // Output: false
  ```

- `Object.is()`:
  ```javascript
  console.log(Object.is(1, '1')); // Output: false
  console.log(Object.is(NaN, NaN)); // Output: true
  ```

-

 `Object.isExtensible()`:
  ```javascript
  let obj = {};
  console.log(Object.isExtensible(obj)); // Output: true
  ```

- `Object.isSealed()`:
  ```javascript
  let obj = {};
  Object.seal(obj);
  console.log(Object.isSealed(obj)); // Output: true
  ```

- `Object.isFrozen()`:
  ```javascript
  let obj = {};
  Object.freeze(obj);
  console.log(Object.isFrozen(obj)); // Output: true
  ```

### Function Methods:

#### Execution Control:
- `Function.prototype.call()`:
  ```javascript
  function greet() {
    return `Hello, ${this.name}!`;
  }
  let person = { name: 'Alice' };
  console.log(greet.call(person)); // Output: 'Hello, Alice!'
  ```

- `Function.prototype.apply()`:
  ```javascript
  function greet() {
    return `Hello, ${this.name}!`;
  }
  let person = { name: 'Alice' };
  console.log(greet.apply(person)); // Output: 'Hello, Alice!'
  ```

- `Function.prototype.bind()`:
  ```javascript
  function greet() {
    return `Hello, ${this.name}!`;
  }
  let person = { name: 'Alice' };
  let boundGreet = greet.bind(person);
  console.log(boundGreet()); // Output: 'Hello, Alice!'
  ```

#### Miscellaneous:
- `Function.prototype.toString()`:
  ```javascript
  function greet() {
    return 'Hello';
  }
  console.log(greet.toString()); // Output: 'function greet() { return 'Hello'; }'
  ```

- `Function.prototype.length`:
  ```javascript
  function sum(a, b) {
    return a + b;
  }
  console.log(sum.length); // Output: 2
  ```

### Number Methods:

#### Conversion:
- `Number.parseFloat()`:
  ```javascript
  let numStr = '3.14';
  let num = Number.parseFloat(numStr);
  console.log(num); // Output: 3.14
  ```

- `Number.parseInt()`:
  ```javascript
  let numStr = '42';
  let num = Number.parseInt(numStr);
  console.log(num); // Output: 42
  ```

#### Formatting:
- `Number.prototype.toFixed()`:
  ```javascript
  let num = 3.14159;
  console.log(num.toFixed(2)); // Output: '3.14'
  ```

- `Number.prototype.toPrecision()`:
  ```javascript
  let num = 123.456;
  console.log(num.toPrecision(4)); // Output: '123.5'
  ```

- `Number.prototype.toExponential()`:
  ```javascript
  let num = 12345;
  console.log(num.toExponential(2)); // Output: '1.23e+4'
  ```

#### Validation:
- `Number.isNaN()`:
  ```javascript
  console.log(Number.isNaN(NaN)); // Output: true
  ```

- `Number.isFinite()`:
  ```javascript
  console.log(Number.isFinite(42)); // Output: true
  console.log(Number.isFinite(Infinity)); // Output: false
  ```

- `Number.isInteger()`:
  ```javascript
  console.log(Number.isInteger(42)); // Output: true
  console.log(Number.isInteger(42.5)); // Output: false
  ```

### Math Methods:

#### Basic Operations:
- `Math.abs()`:
  ```javascript
  console.log(Math.abs(-5)); // Output: 5
  ```

- `Math.max()`:
  ```javascript
  console.log(Math.max(2, 4, 6)); // Output: 6
  ```

- `Math.min()`:
  ```javascript
  console.log(Math.min(2, 4, 6)); // Output: 2
  ```

- `Math.pow()`:
  ```javascript
  console.log(Math.pow(2, 3)); // Output: 8
  ```

- `Math.sqrt()`:
  ```javascript
  console.log(Math.sqrt(16)); // Output: 4
  ```

- `Math.round()`:
  ```javascript
  console.log(Math.round(3.14)); // Output: 3
  ```

- `Math.floor()`:
  ```javascript
  console.log(Math.floor(3.9)); // Output: 3
  ```

- `Math.ceil()`:
  ```javascript
  console.log(Math.ceil(3.1)); // Output: 4
  ```

#### Trigonometry:
- `Math.sin()`:
  ```javascript
  console.log(Math.sin(Math.PI / 2)); // Output: 1
  ```

- `Math.cos()`:
  ```javascript
  console.log(Math.cos(0)); // Output: 1
  ```

- `Math.tan()`:
  ```javascript
  console.log(Math.tan(Math.PI / 4)); // Output: 1
  ```

- `Math.acos()`:
  ```javascript
  console.log(Math.acos(0)); // Output: 1.5707963267948966
  ```

- `Math.asin()`:
  ```javascript
  console.log(Math.asin(0.5)); // Output: 0.5235987755982989
  ```

- `Math.atan()`:
  ```javascript
  console.log(Math.atan(1)); // Output: 0.7853981633974483
  ```

#### Logarithms:
- `Math.log()`:
  ```javascript
  console.log(Math.log(Math.E)); // Output: 1
  ```

- `Math.log10()`:
  ```javascript
  console.log(Math.log10(100)); // Output: 2
  ```

- `Math.log2()`:
  ```javascript
  console.log(Math.log2(8)); // Output: 3
  ```

#### Randomness:
- `Math.random()`:
  ```javascript
 

 console.log(Math.random()); // Output: a random number between 0 and 1
  ```

#### Others:
- `Math.sign()`:
  ```javascript
  console.log(Math.sign(-5)); // Output: -1
  console.log(Math.sign(0)); // Output: 0
  console.log(Math.sign(5)); // Output: 1
  ```

- `Math.trunc()`:
  ```javascript
  console.log(Math.trunc(3.9)); // Output: 3
  ```

- `Math.PI`:
  ```javascript
  console.log(Math.PI); // Output: 3.141592653589793
  ```

- `Math.E`:
  ```javascript
  console.log(Math.E); // Output: 2.718281828459045
  ```

### Date Methods:

#### Construction and Access:
- `Date.now()`:
  ```javascript
  console.log(Date.now()); // Output: current timestamp in milliseconds
  ```

- `new Date()`:
  ```javascript
  console.log(new Date()); // Output: current date and time
  ```

- `Date.parse()`:
  ```javascript
  console.log(Date.parse('2023-04-15')); // Output: timestamp for April 15, 2023
  ```

#### Conversion:
- `Date.prototype.toString()`:
  ```javascript
  let date = new Date('2023-04-15');
  console.log(date.toString()); // Output: 'Sat Apr 15 2023 00:00:00 GMT+0000 (Coordinated Universal Time)'
  ```

- `Date.prototype.toDateString()`:
  ```javascript
  let date = new Date('2023-04-15');
  console.log(date.toDateString()); // Output: 'Sat Apr 15 2023'
  ```

- `Date.prototype.toISOString()`:
  ```javascript
  let date = new Date('2023-04-15');
  console.log(date.toISOString()); // Output: '2023-04-15T00:00:00.000Z'
  ```

#### Comparison:
- `Date.prototype.getTime()`:
  ```javascript
  let date = new Date('2023-04-15');
  console.log(date.getTime()); // Output: timestamp for April 15, 2023 in milliseconds
  ```

- `Date.prototype.getTimezoneOffset()`:
  ```javascript
  let date = new Date();
  console.log(date.getTimezoneOffset()); // Output: time-zone offset in minutes for the current locale
  ```

### RegExp Methods:

#### Matching:
- `RegExp.prototype.test()`:
  ```javascript
  let regex = /hello/;
  console.log(regex.test('Hello World')); // Output: false
  ```

- `RegExp.prototype.exec()`:
  ```javascript
  let regex = /hello/;
  let match = regex.exec('Hello World');
  console.log(match); // Output: null (no match found)
  ```

### Promise Methods:

#### Creation and Composition:
- `Promise.resolve()`:
  ```javascript
  let promise = Promise.resolve('Resolved');
  promise.then(value => console.log(value)); // Output: 'Resolved'
  ```

- `Promise.reject()`:
  ```javascript
  let promise = Promise.reject('Rejected');
  promise.catch(reason => console.log(reason)); // Output: 'Rejected'
  ```

- `Promise.all()`:
  ```javascript
  let promise1 = Promise.resolve('One');
  let promise2 = Promise.resolve('Two');
  Promise.all([promise1, promise2]).then(values => console.log(values)); // Output: ['One', 'Two']
  ```

- `Promise.race()`:
  ```javascript
  let promise1 = new Promise(resolve => setTimeout(resolve, 100, 'One'));
  let promise2 = new Promise(resolve => setTimeout(resolve, 50, 'Two'));
  Promise.race([promise1, promise2]).then(value => console.log(value)); // Output: 'Two'
  ```

- `Promise.allSettled()`:
  ```javascript
  let promise1 = Promise.resolve('One');
  let promise2 = Promise.reject('Two');
  Promise.allSettled([promise1, promise2]).then(results => console.log(results));
  /* Output:
  [
    { status: 'fulfilled', value: 'One' },
    { status: 'rejected', reason: 'Two' }
  ]
  */
  ```

#### Execution and Handling:
- `Promise.prototype.then()`:
  ```javascript
  let promise = Promise.resolve('Resolved');
  promise.then(value => console.log(value)); // Output: 'Resolved'
  ```

- `Promise.prototype.catch()`:
  ```javascript
  let promise = Promise.reject('Rejected');
  promise.catch(reason => console.log(reason)); // Output: 'Rejected'
  ```

- `Promise.prototype.finally()`:
  ```javascript
  let promise = Promise.resolve('Resolved');
  promise.finally(() => console.log('Finally executed')); // Output: 'Finally executed'
  ```

### Set Methods:

#### Manipulation and Iteration:
- `Set.prototype.add()`:
  ```javascript
  let set = new Set();
  set.add(1);
  set.add(2);
  console.log(set); // Output: Set { 1, 2 }
  ```

- `Set.prototype.delete()`:
  ```javascript
  let set = new Set([1, 2, 3]);
  set.delete(2);
  console

.log(set); // Output: Set { 1, 3 }
  ```

- `Set.prototype.clear()`:
  ```javascript
  let set = new Set([1, 2, 3]);
  set.clear();
  console.log(set); // Output: Set {}
  ```

- `Set.prototype.has()`:
  ```javascript
  let set = new Set([1, 2, 3]);
  console.log(set.has(2)); // Output: true
  ```

- `Set.prototype.forEach()`:
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
- `Map.prototype.set()`:
  ```javascript
  let map = new Map();
  map.set('key1', 'value1');
  map.set('key2', 'value2');
  console.log(map); // Output: Map { 'key1' => 'value1', 'key2' => 'value2' }
  ```

- `Map.prototype.delete()`:
  ```javascript
  let map = new Map([['key1', 'value1'], ['key2', 'value2']]);
  map.delete('key2');
  console.log(map); // Output: Map { 'key1' => 'value1' }
  ```

- `Map.prototype.clear()`:
  ```javascript
  let map = new Map([['key1', 'value1'], ['key2', 'value2']]);
  map.clear();
  console.log(map); // Output: Map {}
  ```

- `Map.prototype.has()`:
  ```javascript
  let map = new Map([['key1', 'value1'], ['key2', 'value2']]);
  console.log(map.has('key2')); // Output: true
  ```

- `Map.prototype.get()`:
  ```javascript
  let map = new Map([['key1', 'value1'], ['key2', 'value2']]);
  console.log(map.get('key2')); // Output: 'value2'
  ```

- `Map.prototype.forEach()`:
  ```javascript
  let map = new Map([['key1', 'value1'], ['key2', 'value2']]);
  map.forEach((value, key) => console.log(`${key}: ${value}`));
  // Output:
  // key1: value1
  // key2: value2
  ```

### Error Methods:

#### Construction:
- `Error.prototype.toString()`:
  ```javascript
  let error = new Error('Error message');
  console.log(error.toString()); // Output: 'Error: Error message'
  ```

- `Error.prototype.stack`:
  ```javascript
  let error = new Error('Error message');
  console.log(error.stack);
  // Output:
  // Error: Error message
  //     at <anonymous>:1:13
  ```

