# groestlsum
[![ISC License](http://img.shields.io/badge/license-ISC-blue.svg)](https://github.com/pedroalbanese/groestlsum/blob/master/LICENSE.md) 
[![GoDoc](https://godoc.org/github.com/pedroalbanese/groestlsum?status.png)](http://godoc.org/github.com/pedroalbanese/groestlsum)
[![GitHub downloads](https://img.shields.io/github/downloads/pedroalbanese/groestlsum/total.svg?logo=github&logoColor=white)](https://github.com/pedroalbanese/groestlsum/releases)
[![Go Report Card](https://goreportcard.com/badge/github.com/pedroalbanese/groestlsum)](https://goreportcard.com/report/github.com/pedroalbanese/groestlsum)
[![GitHub go.mod Go version](https://img.shields.io/github/go-mod/go-version/pedroalbanese/groestlsum)](https://golang.org)
[![GitHub release (latest by date)](https://img.shields.io/github/v/release/pedroalbanese/groestlsum)](https://github.com/pedroalbanese/groestlsum/releases)
### Grøstl-256 Recursive Hasher
<PRE>
Usage of groestlsum:
groestlsum [-c &lt;hash.groestl&gt;] [-r] &lt;file.ext&gt;
  -c string
        Check hashsum file.
  -r    Process directories recursively.
</PRE>
  
### Examples:
#### Generate hashsum list:
```sh
$ ./groestlsum [-r] "*.*" > hash.txt
```
#### Check hashsum file:
```sh
$ ./groestlsum -c hash.txt
$ echo $?
```
## License
This project is licensed under the ISC License.
##### Copyright (c) 2020-2022 Pedro F. Albanese - ALBANESE Research Lab.
