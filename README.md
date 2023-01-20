# Hello World build/compile time in C C++ C# Go Java JavaScript Kotlin Python Rust
```sh
bash
cd golang
go version
# go version go1.19.5 linux/amd64
go clean
time go run .
# real    0m0.116s
# user    0m0.121s
# sys     0m0.051s
time go build
# real    0m0.189s
# user    0m0.216s
# sys     0m0.065s
time ./hello
# real    0m0.002s
# user    0m0.002s
# sys     0m0.000s

cd ../py
python3 --version
# Python 3.10.6
time python3 main.py
# real    0m0.016s
# user    0m0.008s
# sys     0m0.008s

cd ../js
node --version
# v19.4.0
time node index.js
# real    0m0.049s
# user    0m0.032s
# sys     0m0.016s

cd ../c
gcc --version
# 11.3.0
time gcc main.c
# real    0m0.045s
# user    0m0.015s
# sys     0m0.029s
time ./a.out
# real    0m0.001s
# user    0m0.001s
# sys     0m0.000s


cd ../cpp
g++ --version
# 11.3.0
time g++ main.cpp
# real    0m0.535s
# user    0m0.322s
# sys     0m0.072s
time ./a.out
# real    0m0.002s
# user    0m0.000s
# sys     0m0.002s

cd ../rs
cargo version
# cargo 1.66.1 
rustc --version
# rustc 1.66.1
cargo clean
time cargo run --release
# release [optimized] target(s) in 0.63s
# real    0m0.702s
# user    0m0.246s
# sys     0m0.114s
cargo clean
time cargo build --release
# Finished release [optimized] target(s) in 0.43s
# real    0m0.502s
# user    0m0.399s
# sys     0m0.145s
time ${target}/release/rs
# real    0m0.007s
# user    0m0.005s
# sys     0m0.003s

cd ../Java
which java
java -version
# openjdk version "17.0.4" 2022-07-19
time java Java.java
# real    0m0.588s
# user    0m1.120s
# sys     0m0.057s
time javac Java.java
# real    0m0.614s
# user    0m1.209s
# sys     0m0.073s
time java Java
# real    0m0.056s
# user    0m0.026s
# sys     0m0.010s

cd ../kt
which kotlinc
kotlinc -version 
# kotlinc-jvm 1.7.21 (JRE 11.0.13+0-b1751.21-8125866)

time kotlinc-jvm hello.kt
# real    0m5.301s
# user    0m11.734s
# sys     0m0.602s

# run:
time kotlin HelloKt
# real    0m0.421s
# user    0m0.397s
# sys     0m0.056s

time kotlinc-jvm hello.kt -include-runtime -d hello.jar
# real    0m6.530s
# user    0m12.283s
# sys     0m1.270s

# run:
time java -jar hello.jar
# real    0m0.085s
# user    0m0.049s
# sys     0m0.018s

cd ../cs
dotnet --list-sdks
# 7.0.102
dotnet --version
# 7.0.102
time dotnet new console
# real    0m1.886s
# user    0m1.812s
# sys     0m0.206s

# dotnet clean
time dotnet run
# real    0m4.458s
# user    0m3.790s
# sys     0m0.311s

```