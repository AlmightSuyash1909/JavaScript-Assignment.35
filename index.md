1. What will be the output of the following code with reason (write the error message if any)
```js
{
  let username = 'John';
}
console.log(username); // username is not defined  
```

2. What will be the output of the following code with reason (write the error message if any)

```js
{
  var username = 'John';
}
console.log(username); // "John"
```

3. What will be the output of the following code with reason (write the error message if any)

```js
{
  const username = 'John';
}
console.log(username); // username not defined
```

4. What will be the output of the following code with reason (write the error message if any)

```js
{
  let num = 21;
}
let secondNum = 200;
function add() {
  return num + num2;
}
console.log(add()); // num is not defined
```

5. What will be the output of the following code with reason (write the error message if any)

```js
{
  var num = 21;
}
let secondNum = 200;
function add() {
  return num + num2;
}
console.log(add()); // num2 is mot defined
```

6. What will be the output of the following code with reason (write the error message if any)

```js
for (let i = 0; i < 20; i++) {
  //
}
console.log(i); // i is not defined
```

7. What will be the output of the following code with reason (write the error message if any)

```js
for (var i = 0; i < 20; i++) {
  //
}
console.log(i); // 20
```

8. What will be the output of the following code with reason (write the error message if any)

```js
for (const i = 0; i < 20; i++) {
  //
}
console.log(i); // assignment to constant variable
```

9. What will be the output of the following code with reason (write the error message if any)

```js
if (true) {
  let user = 'John';
}
console.log(user); // "user is not defined"
```

10. What will be the output of the following code with reason (write the error message if any)

```js
if (true) {
  var user = 'John';
}
console.log(user); // "John"
```

11. What will be the output of the following code with reason (write the error message if any)

```js
if (true) {
  const user = 'John';
}
console.log(user); // user is not defined
```

12. What will be the output of the following code with reason (write the error message if any)

```js
if (true) {
  const number = 21;
  console.log(number++);
} // assignment to constant variable
```

13. What will be the output of the following code with reason (write the error message if any)

```js
if (true) {
  const number = 21;
  console.log((number += 21));
} // assignment to constant variable
```

14. What will be the output of the following code with reason (write the error message if any)

```js
function first() {
  let one = 1;
  function second() {
    let two = 2;
    return one + two;
  }
}

console.log(first()); //   
```

15. What will be the output of the following code with reason (write the error message if any)

```js

function first() {
  let one = 1;
  function second() {
    let two = 2;
    return one + two;
  }
  second();
}

console.log(first()); // undefined
```

16. What will be the output of the following code with reason (write the error message if any)

```js
function first() {
  let one = 1;
  function second() {
    let two = 2;
  }
  second();
  return one + two;
}

console.log(first()); // two is not defined
```

17. What will be the output of the following code with reason (write the error message if any)

```js
function first() {
  let one = 1;
  function second() {
    let two = 2;
    return one + two;
  }
  return second();
}

console.log(first()); // 3
```

18. What will be the output of the following code with reason (write the error message if any)

```js
function first() {
  let one = 1;
  function second() {
    let two = 2;
    let one = 100;
    return one + two;
  }
  return second();
}

console.log(first()); // 102
```

19. What will be the output of the following code with reason (write the error message if any)

```js
let three = 300;
function first() {
  let one = 1;
  let three = 3;
  function second() {
    let two = 2;
    let one = 100;
    return one + two + three;
  }
  return second();
}

console.log(first()); // 105
```

20. What will be the output of the following code with reason (write the error message if any)

```js
let three = 300;
function first() {
  let one = 1;
  let two = 2;
  function second() {
    let one = 100;
    return one + two + three;
  }
  return second();
}

console.log(first()); // 402
```