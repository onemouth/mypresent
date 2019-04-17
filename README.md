# Mypresent

A redistribution of [present](https://github.com/golang/tools) from golang tools.

## Install

```
go get -u -v github.com/leexun/mypresent
```

## Extra features

### Pure HTML

```
```html
<div class="slogan">
  <div>
    <p><b>About me</b></p>
  </div>
</div>
```htmlend
```

### Monaco editor

```
.monaco ./code/example.go
```

## Note

GC optimization is currently disabled. Will use parameter to control this.