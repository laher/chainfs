# Chainfs

A go package which chains together filesystems so that you can combine fs.FS filesystems.

`chainfs.FS` keeps looking through a slice of `fs.FS` filesytems in order to find a given file. It returns the first match.

[![Go Reference](https://pkg.go.dev/badge/github.com/laher/chainfs.svg)](https://pkg.go.dev/github.com/laher/chainfs)