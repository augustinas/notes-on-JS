## Notes and ideas on JavaScript and its peculiarities ##

[Synchronous vs Asynchronous JS](asyncPattern/async.md)

### Functions

Defining functions: function declaration _vs_ function expressions

The simplest function declaration:

```javascript
function add(a, b) {
  return a + b;
}
```

...and function expressions:

```javascript
var multiply = function (a, b) {
  return a * b;
};
```

__What's the difference?!__

And both definitions can be used together.

```javascript
var factorial = function fac(n) {
  return n < 2 ? 1 : n * fac(n-1)
};
console.log(factorial(5));
```

