# LinuxFest NorthWest 2025 Recap

Linux Fest NorthWest 2025 summary.

## Overview

This repository contains the slide deck and a small Go-based live-reload server for presenting the Linux Fest NorthWest 2025 recap.

## Prerequisites

- Go 1.18 or later  
- A working internet connection to download Go module dependencies  

## Getting Started

1. **Clone the repository**  
   ```bash
   git clone https://github.com/ciwg/LFNW2025.git
   cd LFNW2025
   ```

2. **Browse the static slides**  
   Open `slides/slides.html` in your browser.

## Serving with Live Reload

If you’d like to edit the markdown and see changes immediately:

```bash
cd slides
go mod download            # fetch dependencies
make all                   # runs `go run main.go`
```

Then open your browser to:

```
http://localhost:8192
```

As you edit `slides.md`, the page will auto-reload.

## Project Structure

```
LFNW2025/
├─ README.md               # Project overview & usage
└─ slides/
   ├─ Makefile             # `all` → runs `go run main.go`
   ├─ go.mod, go.sum       # Go module definition & lockfile
   ├─ main.go              # Live-reload web server
   ├─ slides.md            # Slide content (Markdown)
   ├─ slides.thtml         # HTML template for rendering slides
   ├─ slides.html          # Pre-generated HTML copy
   └─ images/
      └─ logo.svg          # Slide asset
```

## Regenerating the Static HTML

If you ever want to rebuild `slides.html` from `slides.md` without running the server:

```bash
# (optional) install pandoc if you prefer a standalone conversion:
pandoc slides/slides.md -o slides/slides.html
```

## Contributing

1. Fork the repo  
2. Create a feature branch  
3. Open a pull request  


