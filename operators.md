## Operators / Functions

### Notes
- At first I was thinking about having an extensive operator set, but started seeing how it could get out of control. For now it seems simpler to focus on implementing everything as functions to get started.

### Numeric
* + - * / % ^ (as usual)
* += -= *= /= %= ^= (as usual)
* ++ -- (if it works with all the other syntax, no prob if not)
* bitwise: shifts, and, or, xor, not( << >> & | ^ ~) (or similar...)
* boolean: and, or, not (&& || !) (maybe keywords "and", "or", "not")

### String
* + concatenation
* * multiply "abc"*3 -> "abcabcabc"
* regexp (match & replace)
* interpolation ${}

### List/Array
* push, pop, shift, unshift
* range
* slice
* split/join
* map, collect, etc


### Comments
* // single-line
* /* */ multi-line
