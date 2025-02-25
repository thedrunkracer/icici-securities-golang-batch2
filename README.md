## Golang

### Presentation link

https://docs.google.com/presentation/d/1WVvsbvgHKBrNrKtnT4XWRfrsfkNlbw5u6L9O1DeVBn0/edit?usp=sharing


### keywords

break,case,chan,const,continue,default,defer,else,fallthrough, for, func,go,goto, if, import,interface,map,package,range,return,select,struct, switch,type, var (25 out of 25)

### builtin 

append, cap,clear, close,complex,copy, delete, imag,len,, make, max,min, new,panic,print, println,, real,recover,  (18 out 18)

### go mod

```bash
go mod init demo
```

### go run 

```bash
go run .
go run main.go
go run main.go anothermain.go
```

### go build 

```bash
go build -o build/hello .
go build main.go anothermain.go
go build -o hello main.go
```

### go build for release

```bash
go build -ldflags="-s -w" -o build/hello-small .   
```

### go compilation targets

```bash
go tool dist list 
```

```bash
GOOS=linux GOARCH=amd64 go build -o build/hello_linux_amd64 .
```

### Go env 

```bash
GOOS
GOARCH
GOROOT
```


### Escape analysis

```bash
go build -gcflags="-m" main.go
```

### panic,defer,recover


```bash
go tool compile -o output.o main.go
```

```bash
go tool link -o demo output.o
```


### How to link C 

1. Should have c code 
2. compile gcc or clang
3. 
