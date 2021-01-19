# Hello World compile time in C C++ C# Go Java JavaScript Kotlin Python Rust
```sh
bash
cd py
cd ../py
python --version
# Python 3.8.4
time python main.py
# real    0m0.128s
# user    0m0.000s
# sys     0m0.015s

cd ../js
node --version
# v12.18.3
time node index.js
# real    0m0.173s
# user    0m0.000s
# sys     0m0.031s

cd ../golang
go version
# go version go1.15
time go run .
# real    0m0.701s
# user    0m0.015s
# sys     0m0.015s
time go build
# real    0m0.759s
# user    0m0.015s
# sys     0m0.031s
time ./golang
# real    0m0.071s
# user    0m0.000s
# sys     0m0.046s


cd ../c
time gcc main.c
# real    0m0.545s
# user    0m0.046s
# sys     0m0.000s
time ./a
# real    0m0.051s
# user    0m0.000s
# sys     0m0.031s


cd ../cpp
time g++ main.cpp
# real    0m1.165s
# user    0m0.000s
# sys     0m0.047s
time ./a
# real    0m0.058s
# user    0m0.015s
# sys     0m0.000s

cd ../rs
cargo version
# cargo 1.45.0
rustc --version
# rustc 1.45.0
cargo clean
time cargo run --release
# real    0m1.006s
# user    0m0.000s
# sys     0m0.031s
time cargo build --release
# real    0m1.000s
# user    0m0.015s
# sys     0m0.015s
time target/release/rs
# real    0m0.057s
# user    0m0.000s
# sys     0m0.031s

cd ../cs
dotnet --list-sdks
dotnet --version
# 3.1.301
time dotnet new console
# real    0m3.160s
# user    0m0.015s
# sys     0m0.015s
dotnet clean
time dotnet run
# real    0m3.075s
# user    0m0.000s
# sys     0m0.031s

cd ../Java
which java
java -version
# java version "14.0.2"
time java Java.java
# real    0m1.103s
# user    0m0.000s
# sys     0m0.046s
time javac Java.java
# real    0m1.104s
# user    0m0.000s
# sys     0m0.047s
time java Java
# real    0m0.171s
# user    0m0.015s
# sys     0m0.031s

cd ../kt
which kotlinc
kotlinc -version 
# kotlinc-jvm 1.3.72 (JRE 14.0.2+12-46)

time kotlinc-jvm hello.kt
# real    0m5.070s
# user    0m0.197s
# sys     0m0.448s

# run:
time kotlin HelloKt
# real    0m0.837s
# user    0m0.182s
# sys     0m0.510s

time kotlinc-jvm hello.kt -include-runtime -d hello.jar
# real    0m5.780s
# user    0m0.091s
# sys     0m0.527s

# run:
time java -jar hello.jar
# real    0m0.200s
# user    0m0.015s
# sys     0m0.047s
```