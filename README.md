# go-post-example

[![Build Status](https://travis-ci.org/northbright/go-post-example.svg?branch=master)](https://travis-ci.org/northbright/go-post-example)
[![Go Report Card](https://goreportcard.com/badge/github.com/northbright/go-post-example)](https://goreportcard.com/report/github.com/northbright/go-post-example)

[Golang](http://golang.org) example to do HTTP POST request from client and handle the request in server side.

#### Client
* [Values.Encode()](https://godoc.org/net/url#Values.Encode) encodes the values into “URL encoded” form ("bar=baz&foo=quux") **sorted** by **key**.

#### Server
* [Request.ParseForm()](https://godoc.org/net/http#Request.ParseForm) will parse form data and update Request.PostForm.
