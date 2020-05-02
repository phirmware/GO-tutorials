# Intro to Go

For developers looking forward to learning Go

### History

The Go programming language was created by some awesome developers at Google, generally they wanted a language that had 3 main properties:

1. Fast compile time
2. Ease of development
3. Fast execution

All 3 of these were hard to find in a programming language, Go was created to be that language.

Go has all of the mentioned properties above.
1. It has a very fast compile time.
2. Ease of development as it reduces many of the complexities that come with C
3. Fast execution

### Installation
Go to https://golang.org/dl/ to download Go, follow the directions to setup your first go lang project.

### Documentation
An important factor with working with Go is knowing your way around the documantation.
Visit https://golang.org/doc/

### Lessons

###### 1. Intro to GO
- Intro to go
- Anatomy of a Go file
- Declaring and assigning variables
- Running go programs

###### 2. Types in GO
- Integers - int int8 int32 int64 ...
 `var age int = 4`

- Float - float32 float64
`var gpa float64 = 4.0`

- Strings "Pancakes"
`var flower string = "daisy"`

- Boolean - true false
`var canDrink bool = age > 21`

- Using relect Go package to check type of a variable
`
var x = 10;
reflect.TypeOf(x)
`
- Type conversion in Go
`
var y = float64(x)
fmt.println(reflect.TypeOf(y))
`

###### 3. IF ELSE Conditional statements
- `
if condition {
    fmt.println("Awesome")
}
`
- `if condition {
    fmt.println("Awesome")
} else if condition { 
    fmt.println("cool")
}`

- Variable scoping with IF statements
`
if err := someFunction(); err != nil {
    fmt.println(err)
}
`

###### 4. FOR LOOPS
- `
for i := 0; i <= 100; i++ {
    fmt.Println(i)
}
` Prints 0 to 100
