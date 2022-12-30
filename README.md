# Scaffolder
This is a simple Scaffolder to generate templates to speedup of development. Currently it supports React and Golang web templates.

## How to use
Add $GOROOT and $GOPATH to your $PATH in your shell (`.bashrc`, `.zshrc`, ...). On MacOS M1 you can do it by:
```bash
export GOPATH=$HOME/golang
export GOROOT=/opt/homebrew/opt/go/libexec
export PATH=$PATH:$GOPATH/bin
export PATH=$PATH:$GOROOT/bin
```
Install the package
```bash
go install github.com/Guilospanck/scaffolder@latest
```
Then run:
```bash
scaffolder react
# or
scaffolder go
```
