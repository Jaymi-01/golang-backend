# Main Use Cases Of Go

- For writing performant applications
- For running on scaled, distributed systems

# Characteristics of Go

- it has a simple and readable syntax
- it is efficient and safe
- it is used on the server-side of applications
- it has a fast build time
- it requires fewer resources
- it is a compiled language thats compiles into single binary, and consistent across different OS

## Declaration of Entry Point Of Execution

- Entry point is a main function that go will look for to execute the application, and it is created using `func`

## Packages

- Go programs are organized into packages
- Go's standard library provides different core packages for us to use, eg `fmt` which you can use by importing

# Variables

- Variables are used to store values
- when you create a `variable` with certain value, and you don't declare it in the code, you get a `declared and not used:` error, same also applies when you import a `package` and don't use the package in the code

# Constants

- They are like variables, except their values do not change

# Printing Function

- when you are printing a text mixed with variables, you can use a function called `printf`. it is used for printing formatted data
- `%v` is a special character for placeholder
- `\n` is a special character to break line
- `printf` function allows you to tell go how to format the variables you are referencing
