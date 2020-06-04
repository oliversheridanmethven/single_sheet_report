# Single sheet lay report

## Author

Oliver Sheridan-Methven, June 2020.  
[oliver.sheridan-methven@maths.ox.ac.uk](mailto:oliver.sheridan-methven@maths.ox.ac.uk)

## Description

An abridged version of the InFoMM lay report designed to fit on a single sheet of A4. 

## Usage

Copy the MWE example folder and then type in your lay report. Only modify the mwe.tex file. Starting the report should be as:

```
\documentclass[a4paper, 10pt, english, oneside]{extarticle}
\input{preamble}

\author{Oliver\\Sheridan-Methven} % Linebreak if you have a long name. 
\title{Some Interesting Project Title} 
\myface{sheridan_face}

\begin{document}
\maketitle 

% Start typing. 
\end{document}
```

For a fully worked example see the Roxana Pamfil example (which I created to mimic an original template based on one she produced).
