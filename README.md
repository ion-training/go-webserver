# go-simple-webserver
simple web server made in go

# How to use this repo
Clone and cd into repo
```
https://github.com/ion-training/go-webserver.git
```
```
cd go-webserver
```

# Compile src code into binary
Compile the code
```
go build main.go
```

# Start the webserver (build binary)
```
./main
```

The web server responds to any route on localhost using GET method.

Examples of request URLs:
- http://localhost:3000/
- http://localhost:3000/dogs
- http://localhost:3000/any/random/

# Stop the webserver
Use CTRL+C


# Sample output
```
$ ./main
Starting the server on :3000...

```
```
$ tree
.
├── LICENSE
├── README.md
└── main.go

0 directories, 3 files
$ go build main.go
$
$ tree
.
├── LICENSE
├── README.md
├── main
└── main.go

0 directories, 4 files

```
$ curl localhost:3000
<h1>welcome to my site!</h1>
$
```
