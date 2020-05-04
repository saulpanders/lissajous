# lissajous.go

creates a .gif of a randomly generated lissajous curve. Inspired by a golang tutorial book I read (will link source when I find it).

Give you the option of just generating the .gif or serving it locally over port 8000 (so you can view in a web browser).
## Usage
### Compile
```
go build lissajous.go
```
### Run
Generate .gif
```
lissajous.exe gif
```

To serve on localhost:8000
```
lissajous.exe web
```

### Example
![lissajous example](./l.gif)
