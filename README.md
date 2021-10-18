# nude

**图片裸体检测** 原项目地址 https://github.com/koyachi/go-nude

<br>

## Quick Start

```go
package main

import "github.com/xzyan/nude"

func main() {
    data, _ := ioutil.ReadFile("demo.png")
    has, e := nude.IsImageNude(&data)
}
```

## Installing

```
go get github.com/matsuwin/nude
```
