# Caesar Cipher

## History

In cryptography, a Caesar cipher, also known as Caesar's cipher, the shift cipher, Caesar's code or Caesar shift, is one of the simplest and most widely known encryption techniques. It is a type of substitution cipher in which each letter in the plaintext is replaced by a letter some fixed number of positions down the alphabet. For example, with a left shift of 3, D would be replaced by A, E would become B, and so on. The method is named after Julius Caesar, who used it in his private correspondence. [Wikipedia](https://en.wikipedia.org/wiki/Caesar_cipher)


## Part 1

Create a function called `encode(msg, key)` that accepts two parameters a string `msg` and an int `key` and returns the `msg` encoded with a Caesar cipher shifted by `key` letters.

### Encoder Function Calls
| Function Call | Return Value |
| ----- | ----- |
|encode("Cat", 3) | "Fds" |
|encode("big dog", 8) | "jqo(lwo" |
|encode("Caesar", -1) | "B\`dr\`q" |

## Part 2
Create a function called `decode(msg, key)` that accepts two parameters a string `msg` and an int `key` and returns the `msg` decoded with a Caesar cipher shifted by `key` letters. This decode function should be the inverse of the encode message.

### Decoder Function Calls
| Function Call | Return Value |
| ----- | ----- |
|Decode("Fds", 3) | "Cat" |
|encode("jqo(lwo", 8) | "Caesar" |

## Part 3

1) Create a function called `main()` that asks the user whether they want to encode or decode a message with a Caesar cipher.

2) Then the program should prompt the user for the message they would like to encode/decode (depending on their selection).

3) Next the program should prompt the user for the desired key to encode/decode the message with.

4) Finally, the program should use the appropriate encode or decode function written in part 1 and 2 to encode or decode the message with the appropriate key that was provided by the user.

A shell of a program caesar_cipher.py is provided to help you get started but most of the coding is up to you. You should only use String methods, functions and concepts that were covered in our class.
