# PhD Thesis

This repository contains the LaTeX source files of my PhD thesis entitled "Gradient-Damage Modeling of Dynamic Brittle Fracture: Variational Principles and Numerical Simulations".

## PDF version

An author-generated PDF version is available at [http://thesis.litianyi.me](http://thesis.litianyi.me).

## LaTeX compilation

The simplest way is to use the `latexmk` script available in all latest TeXLive distributions. Make sure that it calls the `pdflatex` program. You only need to compile the main LaTeX file:

```
latexmk main.tex
```

It should include all the chapter TeX files in the `chapters` folder and automatically call several times `pdflatex` and `biber` to obtain the final `main.pdf` file.

## License information

This work is licensed under a [Creative Commons "Attribution 4.0 International" license](https://creativecommons.org/licenses/by/4.0/deed.en). Licensees may copy, distribute, display and perform the work and make derivative works and remixes based on it only if they give the author or licensor the credits (attribution) in the following manner

- Li, T. (2016, October). Gradient-Damage Modeling of Dynamic Brittle Fracture: Variational Principles and Numerical Simulations (Doctoral dissertation, Université Paris-Saclay).

Interested readers can freely use or adapt the document structure, the title page, etc., to their own needs.
