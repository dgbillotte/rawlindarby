## Examples

// defining functions

```javascript
`add(a,b) -> return a+b
```
or 
```javascript
'add(a,b) { return a+b }
```
or
```javascript
`add(a,b) -> {
  return a+b
}

add = `(a,b) -> {
  return a+b
}
```
```javascript
// function invocation
num = add(2,3) // -> 5

num = add.call(5,8) // -> 13
```

```javascript
if( num > limit , '() { return "abc" }, '() { return "xyz" } )

if( num > limit ,           // condition
    '() { return "abc" } ,  // if clause
    '() { return "xyz" } )  // else clause
```
