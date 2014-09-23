#go-watch

Bash script to watch and automatically rerun go files

###Installation
1. (OSX) Use brew to io install fswatch `$ brew install fswatch`
2. Clone repo: `$ git clone https://github.com/mnibecker/go-watch`
3. Inside the repo, make file go-watch executeable `$ chmod -x go-watch`
4. Move go-watch to somewhere in your system path. For example: `$ sudo mv go-watch /usr/local/bin`
5. Have a great time!

###Usage

Use `go-watch` instead of `go run` to run your project. For example:
```
$ go-watch main.go
```
