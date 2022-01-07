# GROESTLSUM
[![ISC License](http://img.shields.io/badge/license-ISC-blue.svg)](https://github.com/pedroalbanese/groestlsum/blob/master/LICENSE.md) 
[![GoDoc](https://godoc.org/github.com/pedroalbanese/groestlsum?status.png)](http://godoc.org/github.com/pedroalbanese/groestlsum)
[![Go Report Card](https://goreportcard.com/badge/github.com/pedroalbanese/groestlsum)](https://goreportcard.com/report/github.com/pedroalbanese/groestlsum)
[![GitHub go.mod Go version](https://img.shields.io/github/go-mod/go-version/pedroalbanese/groestlsum)](https://golang.org)
[![GitHub release (latest by date)](https://img.shields.io/github/v/release/pedroalbanese/groestlsum)](https://github.com/pedroalbanese/groestlsum/releases)
### Grøstl Recursive Hasher
<PRE>
Usage of groestlsum:
groestlsum [-v] [-c <hash.groestl>] [-r] <file.ext>
  -c string
        Check hashsum file.
  -r    Process directories recursively.
  -v    Verbose mode. (for CHECK command)
  </PRE>
  
### Examples:

#### Generate hashsum list:
```sh
$ ./groestlsum [-r] "*.*" > hash.txt
```
##### Always works in binary mode. 

#### Check hashsum file:
```sh
$ ./groestlsum [-v] -c hash.txt
```
##### Exit code is always 0 in verbose mode. 

## License

This project is licensed under the ISC License.
##### Copyright (c) 2020-2021 Pedro Albanese - ALBANESE Lab.
