# Rust
# Rust concepts from their book

## Create a project without cargo
### First you should create a file_name.rs and run the following code to build in to the binary file so by ./file_name run that
```
rustc file_name.rs
./file_name
```

### Create rust project through cargo, notice that it contains git files like .git and .gitignore
```
cargo new hello_cargo --bin
cargo build
```
### Runable(binary) file is in target/debug/

## Cargo uses the Cargo.lock to keep track of dependencies in your application

### but we can also use cargo run to compile and then run
```
cargo run
```
