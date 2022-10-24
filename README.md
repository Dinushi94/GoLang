# GoLang
Learning and practicing Golang 

GoLang

Developed in 2007 and launched in 2009
Developed By Google Employees Robert Griesemar, Rob Pike, Ken Thompson
Go is developed as a community-led open-source project.
Go is compiled and statically typed programming language built to be simple high-performing, readable and efficient.
GoLang also supports environment-adopting patterns. (like dynamic languages.)
Go similar to C
Go developed as an alternative to C++ and Java also Python. 
GoLang is easy to learn the fast language.
Dropbox, Docker, Facebook, Netflix, Uber, and Twitter used Go. 


Why Go as a New Language? 

Before GoLang google used Python, Java, and C++ as key languages, those languages are very powerful but google clarifies the limits of these languages.
 Python is very easy to use but slows it takes some time to get deployment that's the main challenge in using python for large projects. 
Java is a very fast but increasingly complex type of system.
C and C++ take some time to compile its slow when they compile and also a complex type system. 

GoLang solved the 

Slow build time
Uncontrolled dependencies
Effort duplication of writing automatic tools
Cross-language development 

GoLang 

Strong and statically typed
Excellent community
Easy to learn
Key Featured
Simplicity
Fast compile times
Garbage collected
Built-in concurrency
Compile to standalone binaries

GoLang Disadvantages 

Too simplistic
No VM support
Error handling cloud be better
Issues with IOS development
Runtime safety concerns
No GUI library

Go works by using "goroutines," or lightweight processes, which allows further efficiencies. Go also uses a collection of packages for efficient dependency management.

Applied to GoLang 

Cloud-native development 
Go’s concurrency and networking features, and its high degree of portability, make it well-suited for building cloud-native apps.
Distributed network services	
Network applications live and die by concurrency, and Go’s native concurrency features—goroutines and channels, mainly—are well suited for such work. Consequently, many Go projects are for networking, distributed functions, and cloud services: APIs, web servers, minimal frameworks for web applications, and the like.
Utilities and stand-alone tools
Go programs compile to binaries with minimal external dependencies. That makes them ideally suited to creating utilities and another tooling because they launch quickly and can be readily packaged up for redistribution

Go Compiled

Go is a compiled, statically typed language
The Go tool can run a file without precompiling
Compiled executables are OS specific
Compiled apps contain a statically linked runtime
No external virtual machine is needed. 	

Object Oriented with Go

Can define custom interfaces
Custom types can implement one or more interfaces
Custom types can have member methods
Custom structs(data structures) can have member fields

Go Doesn’t support

Type inheritance (no classes)
Method or operator overloading
Structured exception handling
Implicit numeric conversions 

Go Syntax Rules

Go is case sensitive
Variable and package names are lowercase and mixed case
Names of public fields have initial uppercase characters
The initial uppercase character means the symbol is exported

Hello World 

package main
 
import "fmt"
 
func main() {
    fmt.Println("Hello Dinushi!")
}
 




Declare the main package (a package is a way to group functions, and it's made up of all the files in the same directory).
Import the popular fmt package, which contains functions for formatting text, including printing to the console. This package is one of the standard library packages you got when you installed Go.
Implement the main function to print a message to the console. The main function executes by default when you run the main package.


package main
 
import "fmt"
 
func main() {
 
    var a = " Dinushi Dhananjani"
    fmt.Printf("My Name is %s", a)
}
 























