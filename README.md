# JavaScript Versions Small CheatSheet


 # ES2016

 ## `Array.prototype.includes` 
 *Check if an array contains an item*
 ```javascript 
 > const numbers = [1, 2, 3, 4, 8, 16, 32, 64];
undefined
> numbers
[ 1, 2, 3, 4, 8, 16, 32, 64 ]
> numbers.includes(8)
true
> numbers.includes(22)
false
>
```
## `Exponentiation operator (**)`
```javascript
// x ** y

let squared = 2 ** 2;
// same as: 2 * 2

let cubed = 2 ** 3;
// same as: 2 * 2 * 2
```

```javascript
// x **= y

let a = 2;
a **= 2;
// same as: a = a * a;
```

  
  
# ES2017

## Async functions

Async functions allow you to write promise-based code as if it were synchronous, but without blocking the main thread. Thanks to async functions asynchronous code is more readable.

```javascript
async function myAsyncFunction() {
  try {
    const fulfilledValue = await promise;
  }
  catch (rejectedValue) {
    // …
  }
}
```
### Variants of async functions.

- Async function declarations: 
  ```javascript 
  async function foo() {}
  ```
- Async function expressions: 
  ```javascript
  const foo = async function () {};
  ```
- Async method definitions: 
  ```javascript
  let obj = { async foo() {} }
  ```  
- Async arrow functions: 
  ```javascript
  const foo = async () => {};
  ```

## `Object.values`/`Object.entries`
  
### `Object.entries`

Object.entries(x) coerces x to an Object and returns the entries of its enumerable own string-keyed properties, in an Array:
```javascript
> Object.entries({ one: 1, two: 2 })
[ [ 'one', 1 ], [ 'two', 2 ] ]
```
Properties, whose keys are symbols, are ignored:
```javascript
> Object.entries({ [Symbol()]: 123, foo: 'abc' });
[ [ 'foo', 'abc' ] ]
```

## `String padding`
[String padding](http://exploringjs.com/es2016-es2017/ch_string-padding.html)                                      

## `Object.getOwnPropertyDescriptors`
[`Object.getOwnPropertyDescriptors`](https://github.com/ljharb/proposal-object-getownpropertydescriptors)          

## Trailing commas in function parameter lists and calls
[Trailing commas in function parameter lists and calls](https://github.com/tc39/proposal-trailing-function-commas) 

[Shared memory and atomics](https://github.com/tc39/ecmascript_sharedmem)                                          


