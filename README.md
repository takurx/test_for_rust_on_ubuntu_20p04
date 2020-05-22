#test_for_rust_on_ubuntu_20p04

## compile
```
sharo@kirima:~$ rustc hello.rs -o hello
sharo@kirima:~$ ./hello
Hello, world!
```

## cargo
```
sharo@kirima:~/Github/test_for_rust_on_ubuntu_20p04$ cargo new hello
     Created binary (application) `hello` package
sharo@kirima:~/Github/test_for_rust_on_ubuntu_20p04$ cd hello/
sharo@kirima:~/Github/test_for_rust_on_ubuntu_20p04/hello$ cargo build
   Compiling hello v0.1.0 (/home/sharo/Github/test_for_rust_on_ubuntu_20p04/hello)
    Finished dev [unoptimized + debuginfo] target(s) in 0.31s
sharo@kirima:~/Github/test_for_rust_on_ubuntu_20p04/hello$ cargo run
    Finished dev [unoptimized + debuginfo] target(s) in 0.02s
     Running `target/debug/hello`
Hello, world!
```
