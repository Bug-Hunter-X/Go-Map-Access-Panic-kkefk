# Go Map Access Panic

This repo demonstrates a common error in Go: accessing a map before it's initialized.  Go maps do not have default values like Python dictionaries; attempting to access a key in an uninitialized map results in a runtime panic.

The `bug.go` file contains code that demonstrates this issue.  `bugSolution.go` shows the corrected version.

## How to reproduce

1. Clone the repo
2. Run `go run bug.go`  (Observe the panic)
3. Run `go run bugSolution.go` (See the corrected behavior)