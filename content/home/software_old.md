+++
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://sourcethemes.com/academic/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

widget = "blank"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = false  # Activate this widget? true/false
weight = 100  # Order that this section will appear.

title = "Software"
subtitle = ""

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "2"

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.

  # Background color.
  # color = "navy"
  
  # Background gradient.
  # gradient_start = "DarkGreen"
  # gradient_end = "ForestGreen"
  
  # Background image.
  # image = "image.jpg"  # Name of image in `static/img/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.

  # Text color (true=light or false=dark).
  # text_color_light = true

[design.spacing]
  # Customize the section spacing. Order is top, right, bottom, left.
  padding = ["20px", "0", "20px", "0"]

[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""
+++

DFO-LS: Derivative-Free Optimization for Least-Squares
------------------------------------------------------
*[[GitHub]](https://github.com/numericalalgorithmsgroup/dfols)*

DFO-LS is a Python library for solving nonlinear least-squares problems, with optional box constraints. It is a derivative-free solver, meaning it only requires function values, and no first (or higher) derivatives. As a result, it is particularly useful for situations when function evaluations are expensive, or when they are noisy.

Examples of using DFO-LS for parameter fitting and solving nonlinear systems of equations are given in the [documentation](https://numericalalgorithmsgroup.github.io/dfols). There is also a demonstration of how standard (derivative-based) solvers fail when function evaluations are noisy.

DFO-LS is based on [DFO-GN](https://github.com/numericalalgorithmsgroup/dfogn), but includes more features, including: improved robustness to noise, reduced initialization cost, and greater flexibility in parameter choices.

Py-BOBYQA: Derivative-Free Optimization for General Objectives
--------------------------------------------------------------
*[[GitHub]](https://github.com/numericalalgorithmsgroup/pybobyqa)*

Py-BOBYQA is a Python implementation of [Powell](https://en.wikipedia.org/wiki/Michael_J._D._Powell)'s BOBYQA (original [paper](http://www.damtp.cam.ac.uk/user/na/NA_papers/NA2009_06.pdf) and [code](http://mat.uc.pt/~zhang/software.html)). It is a derivative-free solver for general objective minimization, with optional bound constraints.

It also includes a number of features originally from [DFO-LS](https://github.com/numericalalgorithmsgroup/dfols) (see above), which improve its flexibility and robustness to noise. The documentation for Py-BOBYQA is [here](https://numericalalgorithmsgroup.github.io/pybobyqa).

PyCUTEst: Python Interface to CUTEst Optimization Test Environment
------------------------------------------------------------------
*[[GitHub]](https://github.com/njfowkes/pycutest)*

This is a Python wrapper for [CUTEst](https://github.com/ralna/CUTEst), a Fortran package for testing (nonlinear) optimization software. More details are available in the [documentation](https://jfowkes.github.io/pycutest).

PyCUTEst is based on the CUTEr wrapper by [Arpad Buermen](http://fides.fe.uni-lj.si/~arpadb/software-pycuter.html) and developed jointly with [Jaroslav Fowkes](http://people.maths.ox.ac.uk/fowkes).

DFO-GN: Derivative-Free Optimization using Gauss-Newton
-------------------------------------------------------
*[[GitHub]](https://github.com/numericalalgorithmsgroup/dfogn)*

DFO-GN is a Python library for solving nonlinear least-squares problems, with optional box constraints.
[DFO-LS] (https://github.com/numericalalgorithmsgroup/dfols) (see above) is a newer version of this package with more features. The documentation for DFO-GN is [here](https://numericalalgorithmsgroup.github.io/dfogn).

Other Contributions
-------------------

I have contributed code to the [NAG Library](https://www.nag.com/numeric/cl/nagdoc_latest/html/genint/acknow.html) and [ANUGA](https://anuga.anu.edu.au), a tsunami and flood modelling package.

