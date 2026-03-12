---
layout: post
title: Go for the Impatient
date: 2026-03-12 16:42 +0800
---

> 出色的 Go 程序员：大道至简。
我：大道智减。
> 
    

> The only way to learn a new programming language is by writing programs in it. — *The C Programming Language*
> 

# 1 Hello 世界

依照传统，我们的旅途以 “Hello World” 开始：

As is tradition, the journey starts with saying `hello` to the world.

```go
package main

import "fmt"

func main() {
	p := fmt.Println
	
	p("Hello, 世界!")
}
```