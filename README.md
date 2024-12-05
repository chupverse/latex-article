## About

This respository contains a LaTeX template for manuscripts writen by members of both the University and University Hospital at Poitiers.

## Instaling Latex

* Windows: [MikTeX](https://miktex.org/download)
* MacOS: [MacTeX](https://www.tug.org/mactex/mactex-download.html)
* Linux: [TeXLive](https://tug.org/texlive/)

## Compiling LaTex

An easy way to edit and compile LaTeX in a code editor is to use 'TexMaker' which is available on Linux, MacOS, and Windows.

## Testing and using

Here is a skeleton on what your LaTeX document should contain:

```latex
\documentclass{article}
\usepackage{chupverse}

\title{Title of your manuscript}

\author{
  Names of the first author \\
  Institute \\
 \texttt{Email}
   \And
  \And
  Names of the 2nd author \\
  Institute \\
 \texttt{Email}
}

\begin{document}
\maketitle

\begin{abstract}
The text of your abstract
\end{abstract}

\keywords{Key1 \and  Key2 \and Key3}

%% ... The rest of your document

\end{document}
``
