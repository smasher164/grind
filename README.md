# grind [![GoDoc](http://godoc.org/github.com/jackspirou/grind?status.png)](http://godoc.org/github.com/jackspirou/grind) [![Build Status](https://travis-ci.org/jackspirou/grind.svg?branch=master)](https://travis-ci.org/jackspirou/grind) [![Go Report Card](http://goreportcard.com/badge/jackspirou/grind)](http://goreportcard.com/report/jackspirou/grind)
Grind polishes Go programs.

This version of grind is a fork from the original [rsc.io/grind](https://github.com/rsc/grind).
It contains updates that have not yet been merged into the original repository (not sure it is still maintained).

The motivation behind this fork was to merge contributions from others that allow `grind` to build on Go versions 1.4+.
The original repo only built on Go versions up to 1.3.
Updates and fixes beyond Go build versions are also welcome.

## Install
`go get github.com/jackspirou/grind`


## Usage
```bash
$ grind -h
usage: grind [-diff] [-v] packagepath... (or file...)
```

## Packages & Coverage
Package                                                               | Coverage
:-------------------------------------------------------------------- | :-----------------------------------------------------------------------------------------------------------------------------------------
[main](http://godoc.org/github.com/jackspirou/grind)                  | [![Coverage](http://gocover.io/_badge/github.com/jackspirou/grind?1)](http://gocover.io/github.com/jackspirou/grind)
[block](http://godoc.org/github.com/jackspirou/grind/block)           | [![Coverage](http://gocover.io/_badge/github.com/jackspirou/grind/block?1)](http://gocover.io/github.com/jackspirou/grind/block)
[deadcode](http://godoc.org/github.com/jackspirou/grind/deadcode)     | [![Coverage](http://gocover.io/_badge/github.com/jackspirou/grind/deadcode?1)](http://gocover.io/github.com/jackspirou/grind/deadcode)
[flow](http://godoc.org/github.com/jackspirou/grind/flow)             | [![Coverage](http://gocover.io/_badge/github.com/jackspirou/grind/flow?1)](http://gocover.io/github.com/jackspirou/grind/flow)
[gotoinline](http://godoc.org/github.com/jackspirou/grind/gotoinline) | [![Coverage](http://gocover.io/_badge/github.com/jackspirou/grind/gotoinline?1)](http://gocover.io/github.com/jackspirou/grind/gotoinline)
[grinder](http://godoc.org/github.com/jackspirou/grind/grinder)       | [![Coverage](http://img.shields.io/badge/coverage-0%-red.svg?1)](http://gocover.io/github.com/jackspirou/grind/grinder)
[grindtest](http://godoc.org/github.com/jackspirou/grind/grindtest)   | [![Coverage](http://img.shields.io/badge/coverage-0%-red.svg?1)](http://gocover.io/github.com/jackspirou/grind/grindtest)
[vardecl](http://godoc.org/github.com/jackspirou/grind/vardecl)       | [![Coverage](http://gocover.io/_badge/github.com/jackspirou/grind/vardecl?1)](http://gocover.io/github.com/jackspirou/grind/vardecl)
