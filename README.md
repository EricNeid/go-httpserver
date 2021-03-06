# go-httpserver

A simple webserver for serving static files, written in go. 

## Install

```sh
 go get github.com/CombatMage/go-httpserver
```

## Build

Go into folder go-httpserver and execute

```sh
 go build
```

Example for cross compilation for Windows

```sh
 GOOS=windows GOARCH=386 go build
```

## Usage

```sh
 go-httpserver
```

The server allows you to configure multiple properties

* port
* directory to serve
* index html
* run endless or wait for user input to shut down

Example (default values):

```sh
 go-httpserver -port=8080 -serveDir=www -index=www/index.html -interactive=false
```
