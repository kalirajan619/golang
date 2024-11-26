# Starting with GO Basics Course from Udemy

## Install GO:

Run time to build and execute the go program

Go to URL: https://go.dev/dl/

Download and install based on the version you require and OS

Once installed, go to the terminal and run the command `go` This should show if GO is installed

To run the first program in Go, Create a folder and name the file main.go

Program GIT Link: https://github.com/kalirajan619/golang/blob/main/helloworld/main.go

## To run the GO Program:
Run command ```go run main.go```

## To get Executable of go:
Run the command ```go build main.go``` it will create a binary file with the name of the package that will be used for executing ./main in shell and in Windows run main.exe

### Why should we use package main ?

In GO programming language there are two types of packages executable and reusable like helper

if we use package main, GO will automatically build it as an executable but any other custom name will consider it as a helper code

One more thing to note is if you use package main, make sure you use a func named main() in the same program.

### what is import fmt ?

import “fmt” means giving access to our package main to use code from other package named fmt. fmt is short form of format. In go all printing statement is handled using fmt package. fmt is standard library of GO. To get list of all standard library use this link: https://pkg.go.dev/std

### what is func ?

func is short form of function. It will use to execute main function for go

### Order of GO script

Package — package declaration

Import — import required package for our go program

function — declare function tell go to do things
