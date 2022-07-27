# MLBook
Chapter-by-chapter sets of Jupyter Notebooks, with Data Files.  The Notebooks are coded in Matlab, Python, and Julia
To install a Jupyter notebook go to anaconda.com and follow the directions.  This will automatically install the latest Python for you.

The advantage of Jupyter notebooks is that one can document one's code step-by-step with commentary and Latex-compatible notes and scientific formulae.
This makes it easier to share one's research results with others, as well as provides to oneself a reminded of what one did step-by-step.
Of course, in regular coding, one can add in commentary line-by-line, but Jupyter allows the Latex-style notation.

To install the latest Julia, go to https://www.julialang.org/ and follow the instructions for downloading and installation
To link Julia to the Jupyter notebook, open the Julia program in its shell and type the following two commands
========================
using Pkg
Pkg.add("IJulia")
========================

Linking Matlab to the Jupyter notebook is a bit more complex.   There are many ad-hoc instructions but now Matlab is providing support
for using Jupyther notebooks with Matlab.  Go to the following website for more information:

https://www.mathworks.com/products/reference-architectures/jupyter.html



