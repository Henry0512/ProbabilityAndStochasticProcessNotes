# Notes on Probability Theory and Stochastic Processes

This repository contains my personal notes on probability theory and stochastic processes. The content is primarily based on the module *Probability Theory and Stochastic Processes* (3412110099 / BBC4941) offered by the Joint Programme between Beijing University of Posts and Telecommunications (BUPT) and Queen Mary University of London (QMUL).

## Contents

- Calculus Basics
- Events and Their Probabilities
- Random Variables
- Random Vectors
- Limit Theorems
- Introduction to Stochastic Processes
- Stationary Stochastic Processes
- Discrete-Time Markov Chains
- Independent Increment Processes (*Under construction*)

## Getting Started

### Build from Source

To build the PDF file from the LaTeX source, a latexmkrc file is provided. You can compile the PDF by simply running the following command in your terminal:

```bash
latexmk -r .latexmkrc main.tex
```

You can also use your favorite configuration and engine (e.g., `pdflatex`, `xelatex`, or `lualatex`) to build the PDF file. The main file is `main.tex`.

### Download Pre-compiled PDF

If you prefer not to build the PDF yourself, you can download the latest compiled version directly from the GitHub Actions Artifacts (triggered on every push) or from the Releases section of this repository.