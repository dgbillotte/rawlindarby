## Examples

// defining functions

`add(a,b) -> return a+b

or 

'add(a,b) { return a+b }

or

`add(a,b) -> {
  return a+b
}

add = `(a,b) -> {
  return a+b
}


// function invocation
num = add(2,3) // -> 5

num = add.call(5,8) // -> 13


if( num > limit , '() { return "abc" }, '() { return "xyz" } )

if( num > limit ,           // condition
    '() { return "abc" } ,  // if clause
    '() { return "xyz" } )  // else clause
