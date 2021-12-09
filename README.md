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

### The other advantage of using Cargo is that the commands are the same no matter what operating system you’re on, so at this point we will no longer be providing specific instructions for Linux and Mac versus Windows.

### When your project is finally ready for release, you can use ```cargo build --release``` to compile your project with optimizations. This will create an executable in target/release instead of target/debug. These optimizations make your Rust code run faster, but turning them on makesyour program take longer to compile.

### If you’re benchmarking the running time of your code, be sure to ```run cargo build --release``` and benchmark with the executable in target/release.
