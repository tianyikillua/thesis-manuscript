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

This work is licensed under a [Creative Commons "Attribution 4.0 International" license](https://creativecommons.org/licenses/by/4.0). Licensees may copy, distribute, display and perform the work and make derivative works and remixes based on it only if they give the author the credits (attribution). The following BiBTeX source code can be used to cite the current document:

``` latex
@phdthesis{Li:2016,
  Author = {Li, Tianyi},
  Month = oct,
  School = {Université Paris-Saclay},
  Title = {{G}radient-{D}amage {M}odeling of {D}ynamic {B}rittle {F}racture: {V}ariational {P}rinciples and {N}umerical {S}imulations},
  Type = {phdthesis},
  Year = {2016}}
```

Interested readers can freely use or adapt the document structure, the title page, etc., to their own needs.
