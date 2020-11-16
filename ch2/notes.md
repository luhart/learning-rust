# Chapter 2: Programming a Guessing Game

this chapter explores the fundamentals.

learn about let, match, methods, associated functions, using external crates, etc.

## import io lib
```rust
use std::io;
```

## using variables
```rust
let mut x = String::new();
```
- 'let' creates a variable
- 'mut' makes the variable mutable
- 'x' variable name
- '=' binds value on right to variable name on left
- 'String::new' is a fn that returns a new instance of a 'String'
- 'String' is a string type from the standard library that is a growable, UTF-8 encoded bit of text
- "left_type::right_fn" indicates right side is an associated function of left side type
- an associated function is a 'static method'. they are implemented on a type rather than on a particular instance of a type


