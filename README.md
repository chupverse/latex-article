# About

This is a proposal of template to write article by using latex

# Installation

* Windows: [MikTeX](https://miktex.org/download)
* Mac OS X: [MacTeX](https://www.tug.org/mactex/mactex-download.html)
* Linux: [TeXLive](https://tug.org/texlive/)
  
# Testing and using

Here is a skeleton on what your LaTeX document should contain:

```latex
\documentclass{zmdocument}

\title{Title}
\author{Author}
\licence[path/to/image]{Licence name}{URL} % optional
\logo{logo.png}  % if ./logo.png is available

\begin{document}
\maketitle
\tableofcontents

%% ... The rest of your document
\end{document}
``
See [the `article.tex` file in tests](./tests/article.tex) for a complete example.

