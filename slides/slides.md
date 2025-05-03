class: center, middle

# Welcome to Remark.js

---

## Agenda

1. Introduction to Remark.js
2. Features and Benefits
3. How to Create Slides
4. Live Demo

---

## Introduction to Remark.js

- Markdown-driven slideshow tool
- Runs directly in your browser
- Highly customizable with CSS and JavaScript

---

## Features and Benefits

### Features:
- Simple Markdown syntax
- Supports speaker notes and incremental slides
- Integrates LaTeX for math expressions

### Benefits:
- No additional software required
- Lightweight and responsive
- Open-source and free to use

---

## How to Create Slides

1. Write your slides in this Markdown file (e.g., `slides.md`).
2. `go run main.go` to generate and host `slides.html`, or just run `make`
   in the slides directory.

---

## Live Demo

> "The best way to learn is by doing!"  
> Start creating your own presentation now.

---

## Code Example

```go
package main

import "fmt"

// a long function that causes the code block to need a scrollbar
// to demonstrate that code blocks can be scrolled
func longFunction() {
    // do nothing for several lines
    fmt.Println("Hello, World!")
    fmt.Println("Hello, World!")
    fmt.Println("Hello, World!")
    fmt.Println("Hello, World!")
    fmt.Println("Hello, World!")
    fmt.Println("Hello, World!")
    fmt.Println("Hello, World!")
    fmt.Println("Hello, World!")
    fmt.Println("Hello, World!")
    fmt.Println("Hello, World!")
    fmt.Println("Hello, World!")
    fmt.Println("Hello, World!")
}

func main() {
    fmt.Println("Hello, World!")
}
```

---

## Image Example

Locally hosted image, scaled to 40% of the slide width:

![:img Local Image, 40%](images/logo.svg)

Remotely hosted image:
![Remark.js Logo](https://raw.githubusercontent.com/remarkjs/remark/1f338e72/logo.svg?sanitize=true)

---

class: center, middle

# Thank You!

