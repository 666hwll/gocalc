# gocalc
A simple cli calculator written in Go
### Goals:
- web server 
- the closest thing to minimalism while having a functioning calculator you could use (only stdlib) 🔥
### Installation:
``` bash
go build -o gocalc calculator64.go
```
or

``` bash
gccgo -o gocalc 
```
### new features of the normal calculator:
- cli flags
- Tan, Sin, Cos, Log, facility with the Gamma function
- confusion because of the flags usage lol
### what does not work intensionally because minimalism (it is not a bug; it is a feature!):
- Brackets
