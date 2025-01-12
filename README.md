# Go Nil Map Lookup Panic

This repository demonstrates a common error in Go: panics caused by attempting to access elements of an uninitialized map.

The `bug.go` file contains code that will panic because it tries to assign a value to a key in a nil map. The `bugSolution.go` file shows how to properly handle this using a check and initialization.

This is a crucial issue because it can lead to unexpected program crashes in production environments.