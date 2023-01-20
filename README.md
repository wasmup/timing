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
# v12.18.3          v14.15.5
time node index.js
# real    0m0.173s  0m0.154s
# user    0m0.000s
# sys     0m0.031s  0m0.047s


cd ../c
time gcc main.c
# real    0m0.545s  0m0.277s
# user    0m0.046s
# sys     0m0.000s
time ./a
# real    0m0.051s 0m0.041s
# user    0m0.000s
# sys     0m0.031s


cd ../cpp
time g++ main.cpp
# real    0m1.165s 0m0.945s
# user    0m0.000s
# sys     0m0.047s
time ./a
# real    0m0.058s 0m0.154s
# user    0m0.015s
# sys     0m0.000s

cd ../rs
cargo version
# cargo 1.45.0   1.50.0
rustc --version
# rustc 1.45.0   1.50.0
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
# 3.1.301           5.0.103 
time dotnet new console
# real    0m3.160s  0m2.619s
# user    0m0.015s
# sys     0m0.015s
dotnet clean
time dotnet run
# real    0m3.075s  0m4.075s
# user    0m0.000s
# sys     0m0.031s

cd ../Java
which java
java -version
# java version 14.0.2 15.0.2
time java Java.java
# real    0m1.103s   0m0.856s
# user    0m0.000s
# sys     0m0.046s
time javac Java.java
# real    0m1.104s  0m0.874s
# user    0m0.000s
# sys     0m0.047s
time java Java
# real    0m0.171s 0m0.229s
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