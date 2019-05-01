# learnGo
Go Snippets and programs written on the go

My Notes:

Day 1 :

Key Concepts:
============
- Compiled, Statically typed
- Executables are OS specific
- Statically Linked ( Bigger executables but no need for VMs for running)
- No Inheritance
- No operator or method overloading (unique signature)
- No Structured exception handling (handle in return)
- No Implicit numeric conversions (Always explicitly type) 

- Borrows C sytax and  next-gen language for C
- Reduces the amount of typing, consise program 

Syntax:
=======
- Case sensitive
- variable and package names are lower and mixed case (like private)
- Exported functions/fields have initial Upper case (like public)
- no semicolon needed ()
```
var animals [3]string
animals[0] = "cat"
animals[1] = "dog"
animals[2] = "lion"
```

- code blocks are inside braces have the { in the same line
```
count := 0
for i := 0; i < 10; i++ {
    count += 1
}
```


