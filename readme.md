CHROTRAN (Model Analysis & Decision Support)
=======================================


Installation
------------

\textsc{chrotran} must be compiled using the GFortran complier (freely available as part of the GNU Compiler Collection).
It is based on the open-source \textsc{pflotran} code base, and the installation procedure is essentially the same as that required to build \textsc{pflotran} from source, and \textsc{chrotran} requires all the libraries upon which \textsc{pflotran} depends, including PETSc \citep{balaypetsc} and others.
For installation of required libraries, the \textsc{pflotran} installation instructions\footnote{Available at \url{http://documentation.pflotran.org/user_guide/how_to/installation/installation.html}.} are applicable, except that \textsc{chrotran}, rather than \textsc{pflotran}, should be cloned from its repository\footnote{Not officially released yet; anonymous access can be facilitated through editor for review purposes.}

The following checkout of PETSc is required to run the current release version of \textsc{chrotran}:

```
git checkout 1a9d3c3c50abf60098813fdf7291fe3540415115
```

Examples
------------



