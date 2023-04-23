# Golang Playground

## Apr 22, 2023: Getting Started with Golang
### Useful Commands 
```
# initialize new module
go mod init github.com/path/to/module
```
```
# organize the clearn up go.mod and go.sum
go mod tidy
```
```
# check why is the module a dependecy
go mod why -m github.com/path/to/module
```
```
# build and install a binary 
go install github.com/path/to/bin@lates
```
```
# add or update dependecy
go get github.com/path/to/module
```
```
# use specific version
go get github.com/dep/commit@branch
```
```
# upgrade all modules used in subdirs
go get -u ./...
```
```
# remove dependencies 
go get github.com/dep/legacy@none
```


