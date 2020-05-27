+++
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://sourcethemes.com/academic/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

widget = "blank"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 20  # Order that this section will appear.

title = "Research"
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

Optimization
------------
[Optimization](https://en.wikipedia.org/wiki/Mathematical_optimization)---finding the maximum or minimum of a function---is one of the most important classes of problem in computational mathematics, arising often in scientific and industrial applications. My focus is on [nonlinear optimization](https://en.wikipedia.org/wiki/Nonlinear_programming), where the function to be optimized (the 'objective' function) is some nonlinear, possibly nonconvex function usually with little known structure.

**Nonlinear optimization resources**

Together with Coralia Cartis and Jaroslav Fowkes (University of Oxford), I maintain a page of [resources for nonlinear optimization](opt/), including a collection of software and test problems.

Derivative-Free Optimization (DFO)
----------------------------------
Generally speaking, to optimize a nonlinear objective, you approximate it locally by some simpler function (such as a low-order Taylor series). To construct this simpler function, you need to evaluate the objective and its derivatives at some set of points. Evaluating the derivative of the objective can be done in several ways:

* If you know the analytic form of the objective, you can compute its derivatives using calculus.
* If you have access to computer code for evaluating the objective, [automatic differentiation](https://en.wikipedia.org/wiki/Automatic_differentiation) could be used to compute analytic derivatives.
* Otherwise, you have to approximate the derivative, e.g. using [finite differencing](https://en.wikipedia.org/wiki/Numerical_differentiation). 

However, if the objective is [black-box](https://en.wikipedia.org/wiki/Black_box), expensive to evaluate or noisy (e.g. a Monte Carlo simulation, or involves the finite termination of an iterative procedure), these approaches may be impractical or inaccurate. [Derivative-free optimization (DFO)](https://en.wikipedia.org/wiki/Derivative-free_optimization) is the field devoted to nonlinear optimization of objectives when you only have access to (possibly inaccurate) evaluations of the objective.

**My research**

I develop and study *model-based* DFO algorithms. This is a class of DFO method which tries to incorporate features of derivative-based methods, and ultimately build local approximations to the objective (e.g. by polynomial interpolation). I have developed several algorithms and software packages for solving least-squares problems with DFO methods, and developed techniques which make model-based DFO more robust to noise, able to local minima, and tackle large-scale problems via dimensionality reduction.


