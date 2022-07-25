# Using the system LaTeX installation with matplotlib

We use the pgf backend of matplotlib to create publication quality pdf
plots.

The example uses the modern `lualatex` engine, so you'll need a relatively
recent `TeXLive`, everything >= 2016 should work.

The method itself also supports `pdflatex` and `xelatex`.

For more information see:

* https://matplotlib.org/stable/tutorials/text/pgf.html
* https://matplotlib.org/stable/tutorials/introductory/customizing.html

To use this backend, include your plotting routine (written in pyhton) in this
directory and include a line saving your plot to the './build/' directory.
Then add to the Makefile in a similar way to the example plots.
