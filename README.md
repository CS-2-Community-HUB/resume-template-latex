# LaTeX Resume Template
A clean, minimal LaTeX resume template built for professionals who want a sharp, ATS-friendly layout. It’s easy to customize, looks great in print and PDF, and doesn’t require any fancy LaTeX packages.

Based off of [sb2nov/resume](https://github.com/sb2nov/resume/).
Originally forked from [jakegut/resume](https://github.com/jakegut/resume).

## Prerequisites
To compile the resume template, you'll need:
- A LaTeX distribution:
  - [TeX Live](https://www.tug.org/texlive/) (Linux/macOS)
  - [MiKTeX](https://miktex.org/) (Windows)
- A LaTeX editor (optional but helpful):
  - [TeXstudio](https://www.texstudio.org/)
  - [Overleaf](https://www.overleaf.com/) (web-based, no installation required)
- Basic familiarity with `.tex` files

### Homebrew (macOS)
If you're on macOS and want to compile locally, you can install everything via [Homebrew](https://brew.sh):
```zsh
brew install --cask mactex
```

After installation, you may need to add LaTeX binaries to your PATH:
```zsh
export PATH="/Library/TeX/texbin:$PATH"
```

You can now compile the resume using ```pdflatex```:
```zsh
pdflatex resume.tex
```

## Getting Started
Below you'll find the steps to use this resume template. 
1. Ensure that you have the prerequisites installed
2. Fork this repository
   - Be sure to name it something like resume-firstname-lastname
3. Modify the template to fit your experience! 

