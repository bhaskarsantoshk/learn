# Go

# Intro:

- Go is a statically typed and compiled programming language.
- Statically typed : The variables are explicitly typed and determined at compile time.
- Compiled language: A language that translates source code to machine code before execution.
- C++ has fast execution but slow and inefficient building , Java and .NET compile fast but have slow execution, Python/Ruby/JS are easy to write but are slower in exution. Go combines best of all : Efficent and fast compilation, Fast execution and easy to program.
- Go with the concept of Goroutines make the best use of multi core and multi processor computers.
- Go has better Memory Mangement.
- Go, in general, has only one way of getting a particular operation done - so, It’s easy to read other people’s code.
- Go doesn’t have operator oveloading.

# More … :

- File names are in lower letters ( can have _ if it’s a multi word file name ) and file name extention is `.go`
- The package to which the `.go` file belongs will be indicated on the *first* line.
- Pacakge names are also in lower case.  For example: `package main`
- A standalone executable belongs to main. Each Go application contains one main.
- Packages and the files within them must be compiled in the correct order.
- Factoring the keyword: calling a keyword once on multiple instances.
    
    ```go
    import (
      "fmt"
      "log"
      "strings"
    )
    ```
