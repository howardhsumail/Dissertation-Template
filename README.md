# Dissertation LaTeX Template

This template is based on the [Dissertation Formatting Manual](https://guides.lib.uci.edu/gradmanual/templates) from the UC-Irvine Libraries. The design uses the [arXiv style](https://github.com/kourgeorge/arxiv-style) which is based on the the [NeurIPS](https://nips.cc/) styling. The reference style includes [AEA](https://github.com/ShiroTakeda/econ-bst/blob/master/customization/econ-econometrica.bst) (lastname, firstname) and [Econometrica](https://github.com/ShiroTakeda/econ-bst/blob/master/customization/econ-aea.bst) (lastname, abbreviated firstname).

Based on the NIPS styling, it makes this singlec-olumn dissertation template esthetic and convenient for reading. Instead of integrating the formatting into a single style file, this template defines the styles and format in the `main.tex` preambles and collects all the imported packages in the `package.sty`. This approach not only makes the editing source more transparent but also easier to customize.

Various LaTeX syntaxes are also demonstrated throughout the document such as spacing, hyperlinked footers, abbreviations, coloring, listing, table-of-contents customization, hyper-referencing, figure and table formatting with decimal alignment, mathematics symbols, and graphic elements. Users can refer to the syntax during editing.

🎉 The compiled template PDF can be viewed [here](https://www.haochehsu.com/other/Dissertation_LaTeX_Template.pdf).

---

### 🖋 The Template
This template includes:
  - Setting: `package.sty`
  - Content: `main.tex`, `Chapter1.tex`, `Chapter2.tex`, `Chapter3.tex`, `reference.bib` (references database)
  - Style files:
    - arXiv style: `arxiv.sty`
    - Bibliography style: `aea.bst` and `ecta.bst`

### 📐 Usage

User only need to customize the `package.sty` in the `Style` folder and edit the 5 **Content** files. Bibliography style is located in `main.tex`: 

```tex
\bibliographystyle{Style/aea} # Style/ecta
```

#### Online

For online TeX editing, [download](https://github.com/howardhsumail/Dissertation-Template/archive/refs/heads/main.zip) this template, upload all the files and folders to [Overleaf](https://www.overleaf.com/), and compile the `main.tex`.

#### Offline

For local editing, [download](https://github.com/howardhsumail/Dissertation-Template/archive/refs/heads/main.zip) this template and edit with [Texmaker](https://www.xm1math.net/texmaker/) and [TeXstudio](https://www.texstudio.org/) (requires [MacTeX](https://www.tug.org/mactex/) for Mac and [MiKTeX](https://miktex.org/download) for Windows) or [Texpad](https://apps.apple.com/us/app/texpad-latex-editor/id458866234?mt=12).

### 📒 General Notes

For help, comments, bug reporting, and change requests, please [contact](mailto:howardhsumail@gmail.com) the author. You can use or redistribute this project, however, the author takes no responsibility for whatever usage of this template. Finally, You are very welcome to contribute to this template.

---

The UCI dissertation template on overleaf can be accessed [here](https://www.overleaf.com/latex/templates/university-of-california-irvine-thesis/bzsqmxszcpny). The UCI template PDF can be viewed [here](https://www.haochehsu.com/other/uci_thesis_template.pdf).
