# Day 03 Notes - Java Developer Journey

* How negative numbers are stored using 2's Complement
* Step by step conversion process
* Why 2's complement is used internally
* Floating point number storage explained
* Exponent representation and normalization
* What is bias in floating point representation 
* Normal vs Edge cases in floating point representation
* Why exact values are sometimes NOT retrieved
* Precision errors explained simply

# Negative Number
byte b = 42 // (00101010)
byte { _ _ _ _ _ _ _ _} -> -128 to + 127

byte b = -42 ( this - 2's complement then -42 answer)

 MSB -> 11010010 <- LSB
