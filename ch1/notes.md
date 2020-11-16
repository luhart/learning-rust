# Chapter 1: Getting Started 

compile and run a program 
```bash
rustc file.rs
./file
```

## cargo
- Rust's build system and package manager
- create a new project with Cargo

### create a rust project
```bash
cargo new hello_cargo
```

### build & run
```bash
cargo build
cargo run
```

### check to see if your code compiles
```bash
cargo check
```

## misc

- function_name!() calls a macro instead of a normal function
- rust is an ahead-of-time compiled language, meaning you can run compiled programs (executables) and run it on a machine without rust installed

