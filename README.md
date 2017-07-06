# JavaScript Versions CheatSheet

Finished proposals are proposals that have reached stage 4, and are included in the [latest draft](https://tc39.github.io/ecma262/) of the specification.


 # ES2016
 ----------------------------

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

  
  
*ES2017* |                                                                              |
------------------------------------
Feature name | Definition & Example |
[`Object.values`/`Object.entries`](http://exploringjs.com/es2016-es2017/ch_object-entries-object-values.html)      | 
[String padding](http://exploringjs.com/es2016-es2017/ch_string-padding.html)                                      | 
[`Object.getOwnPropertyDescriptors`](https://github.com/ljharb/proposal-object-getownpropertydescriptors)          | 
[Trailing commas in function parameter lists and calls](https://github.com/tc39/proposal-trailing-function-commas) | 
[Async functions](https://github.com/tc39/ecmascript-asyncawait)                                                   | 
[Shared memory and atomics](https://github.com/tc39/ecmascript_sharedmem)                                          | 


