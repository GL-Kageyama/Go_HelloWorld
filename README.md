# Go Lang Hello World

## Code
```Go
package main

import "fmt"

func main() {
	fmt.Println("Hello, World!");
}
```
## Comment
The Go language can hide the build process with the "go run" command.  
Of course, it is also possible to build explicitly with the "go build" command.  

## Output Sample
$ go run hello.go  
Hello, World!  
$ go build -o hello hello.go  
$ ./hello  
Hello, World!  
