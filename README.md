# Stoa Calculator

> Stoa Calculator is a powerful calculator that have everything you need to do any kind of calculations!

[![Generic badge](https://img.shields.io/badge/Version-1.1.0-<COLOR>.svg)](https://pypi.org/project/StoaCalculator/)
[![Windows](https://img.shields.io/badge/OS-Windows-brightgreen.svg)](https://img.shields.io/badge/OS-Windows-brightgreen.svg)
[![Status](https://img.shields.io/badge/Status-Stable-brightgreen.svg)](https://img.shields.io/badge/Status-Stable-brightgreen.svg)
[![Downloads](https://pepy.tech/badge/stoacalculator)](https://pepy.tech/project/stoacalculator)

This calculator can do from basic aritmethic to advanced calculus, we will be releasing more
updates and adding more features, our goal is to make this calculator the most powerful calculator
ever to exist.

![](https://raw.githubusercontent.com/jorgeeldis/StoaCalculator/main/stoaheader.png)

## Installation

<!--
OS X & Linux:

```sh
npm install my-crazy-module --save
```
-->

Windows:

```sh
python3 -m pip install stoacalculator
```

## Usage example

We can use Stoa Calculator in many ways, one of the best ways is to use it for trigonometry, statistics and calculus.

```py
import stoacalculator

--------------------------------------------------------------------
# Aritmethic
--------------------------------------------------------------------
# Simple Operators
stoacalculator.add_numbers(54,1587)
stoacalculator.substract_numbers(25487,64589)
stoacalculator.multiply_numbers(2547,31054)
stoacalculator.divide_numbers(54489,641257)
--------------------------------------------------------------------
# Least common divisor & Greatest common divisor
stoacalculator.LCM(6,12)
stoacalculator.GCM(12,24)
--------------------------------------------------------------------
# Decimal to Fraction
stoacalculator.D2F(0.25)
--------------------------------------------------------------------
# Largest Integer not greater than x
stoacalculator.less(-24.58)
--------------------------------------------------------------------
# Smallest integer greater than or equal to x.
stoacalculator.more(58.99)
--------------------------------------------------------------------
# Returns the fractional and integer parts of x
stoacalculator.modf(100.58)
--------------------------------------------------------------------
# Return the truncated integer parts of different numbers
stoacalculator.truncated(8.59)
--------------------------------------------------------------------

--------------------------------------------------------------------
# Trigonometry
--------------------------------------------------------------------
# Trigonometric Functions
stoacalculator.sin(90)
stoacalculator.cos(180)
stoacalculator.tan(270)
stoacalculator.asin(0.5)
stoacalculator.acos(0.5)
stoacalculator.atan(180)
stoacalculator.sinh(270)
stoacalculator.cosh(360)
stoacalculator.tanh(90)
stoacalculator.asinh(180)
stoacalculator.acosh(270)
stoacalculator.atanh(0.5)
stoacalculator.atan2(90, 180)
--------------------------------------------------------------------
# Conversion between Radians and Degree
stoacalculator.radtodeg(3.1415/2)
stoacalculator.degtorad(180)
--------------------------------------------------------------------

--------------------------------------------------------------------
# Geometry
# Triangle (Side1, Side2, Side3)
# Circle (Radius)
# Square (Side)
# Rectangle (Height & Width)
# Trapezoid (Base1, Base2, Height)
# Elipse (Major axis, Minor axis)
# Parallelogram (Base, Height)
# Sector (Radius, Angle in degree)
# Sphere (Radius)
# Cone (Radius, Height)
# Cube (Side)
# Rectangular Prism (Length, Width, Heigth)
# Cylinder (Radius, Heigth)
# Circumference (Radius)
# Diameter (Radius)
# Radius (Circumference)
--------------------------------------------------------------------
# Area of elements
stoacalculator.areacircle(25)
stoacalculator.areatriangle(25,10,30)
stoacalculator.areasquare(50)
stoacalculator.arearectangle(25,10)
stoacalculator.areatrapezoid(25,10,50)
stoacalculator.areaelipse(8,4)
stoacalculator.areaparallelogram(8,4)
stoacalculator.areasector(4,45)
--------------------------------------------------------------------
# Perimeter of elements
stoacalculator.perimetertriangle(25,25,25)
stoacalculator.perimetersquare(50)
stoacalculator.perimeterrectangle(25,10)
stoacalculator.perimetertrapezoid(25,10,50,20)
stoacalculator.perimeterparallelogram(8,4)
--------------------------------------------------------------------
# Volume of elements
stoacalculator.volumesphere(25)
stoacalculator.volumecone(5,12)
stoacalculator.volumecube(10)
stoacalculator.volumerectprism(25,10,40)
stoacalculator.volumecylinder(10,30)
--------------------------------------------------------------------
# Circle Calculations
stoacalculator.areacircle(25)
stoacalculator.circumferencecircle(25)
stoacalculator.diametercircle(25)
stoacalculator.radiuscircle(157)
--------------------------------------------------------------------


--------------------------------------------------------------------
# Algebra
--------------------------------------------------------------------
# Factorial, Absolute, Euclidean Norm
stoacalculator.factorial(52)
stoacalculator.absolute(-10)
stoaclaculator.euclidean(3, 4)
--------------------------------------------------------------------
# Exponents - Square Root of a Number
stoacalculator.sqr_root(64)
--------------------------------------------------------------------
# Exponents - a raised to the power of n
stoacalculator.pow_numbers(546,6)
--------------------------------------------------------------------
# Logarithms - Printing the log base e of 14
stoacalculator.natlog(14)
--------------------------------------------------------------------
# Logarithms - Printing the log base 5 of 14
stoacalculator.baselog(14, 5)
--------------------------------------------------------------------
# Logarithms - Returns the natural logarithm of 1+x
stoacalculator.natlog1p(64)
--------------------------------------------------------------------
# Logarithms - Returns the base-2 logarithm of x
stoacalculator.base2log(64)
--------------------------------------------------------------------
# Logarithms - Returns the base-10 logarithm of x
stoacalculator.base10log(128)
--------------------------------------------------------------------
# Polynomial Equations - Return the roots of a polynomial
# Example of polynomial: x^2+2x+2
list = [1, 2, 2]
stoacalculator.roots(list)
--------------------------------------------------------------------


--------------------------------------------------------------------
# Statistics
list = [1, 2, 5, 6]
--------------------------------------------------------------------
# Types of Mean: Regular, Floating Point, Geometric & Harmonic
stoacalculator.mean(list)
stoacalculator.floatmean(list)
stoacalculator.geometricmean(list)
stoacalculator.harmonicmean(list)
--------------------------------------------------------------------
# Types of Mode: Regular & Multimode
stoacalculator.mode(list)
stoacalculator.multimode(list)
--------------------------------------------------------------------
# Types of Median: Regular, Low, High & Grouped
stoacalculator.median(list)
stoacalculator.medianlow(list)
stoacalculator.medianhigh(list)
stoacalculator.mediangrouped(list)
--------------------------------------------------------------------
# Min number, Max number, Range and Order a list
stoacalculator.minlist(list)
stoacalculator.maxlist(list)
stoacalculator.rangelist(list)
stoacalculator.orderlist(list)
--------------------------------------------------------------------
# Types of Variance: Sample Standard & Population
stoacalculator.variance(list)
stoacalculator.popvariance(list)
--------------------------------------------------------------------
# Types of Deviation: Sample Standard & Population
stoacalculator.deviation(list)
stoacalculator.popdeviation(list)
--------------------------------------------------------------------
# Quartiles
stoacalculator.firstquartilelist(list)
stoacalculator.thirdquartilelist(list)
stoacalculator.interquartilelist(list)
--------------------------------------------------------------------
# Laplace Distribution
stoacalculator.laplace(1.45, 15)
--------------------------------------------------------------------

--------------------------------------------------------------------
# Matrices
list1 = [[2, 4], [5, -6]]
list2 = [[9, -3], [3, 6]]
--------------------------------------------------------------------
# Addition of Two Matrices
stoacalculator.addmatrices(list1, list2)
--------------------------------------------------------------------
# Multiplication of Two Matrices
stoacalculator.multiplymatrices(list1, list2)
--------------------------------------------------------------------
# Transpose of a Matrix
stoacalculator.transposematrix(list1)
--------------------------------------------------------------------
# Inner product of two Matrices
stoacalculator.innermatrices(list1, list2)
--------------------------------------------------------------------
# Dot product of two Matrices
stoacalculator.dotmatrices(list1, list2)
--------------------------------------------------------------------
# Trace of a Matrix
stoacalculator.tracematrix(list1)
--------------------------------------------------------------------
# Rank of a Matrix
stoacalculator.rankmatrix(list1)
--------------------------------------------------------------------
# Determinant of a Matrix
stoacalculator.detmatrix(list1)
--------------------------------------------------------------------
# True Inverse of a Matrix
stoacalculator.trueinvmatrix(list1)
--------------------------------------------------------------------
# Pseudo Inverse of a Matrix
stoacalculator.pseudoinvmatrix(list1)
--------------------------------------------------------------------
# Eigenvalues and eigenvectors of a matrix
stoacalculator.eigmatrix(list1)
--------------------------------------------------------------------
# Transform a matrix into a one-dimensional array
stoacalculator.flatmatrix(list1)
--------------------------------------------------------------------


# Plotting
import numpy as np
--------------------------------------------------------------------
# We recommend to always use 100 linearly spaced numbers
x = np.linspace(-5, 5, 100)
# For trigonometry we recommend to use this configuration
x = np.linspace(-np.pi,np.pi,100)
# Example of formulas
linearformula = 2*x
quadraticformula = 1*x+x**2
cubicformula = 6*x+x**3
trigonometricformula = np.sin(x)
exponentialformula = np.exp(x)
# Usage of formulas
stoacalculator.linearplot(x, linearformula)
stoacalculator.quadraticplot(x, quadraticformula)
stoacalculator.cubicplot(x, cubicformula)
stoacalculator.trigonometricplot(x, trigonometricformula)
stoacalculator.exponentialplot(x, exponentialformula)
stoacalculator.biplot(x, trigonometricformula, exponentialformula)
--------------------------------------------------------------------

--------------------------------------------------------------------
# Calculus
from sympy import *
# We have to make a constant a symbol
x = Symbol('x')
--------------------------------------------------------------------
# Partial Fractions
stoacalculator.partfrac(1 / x + (3 * x / 2 - 2)/(x - 4))
--------------------------------------------------------------------
# Limits tend to x, in this case 0
stoacalculator.limits(sin(x)/x, x, 0)
--------------------------------------------------------------------
# Integrals and Derivatives
stoacalculator.derivatives(sin(x)+exp(x)*log(x))
stoacalculator.integrals(sin(x)+exp(x)*log(x))
--------------------------------------------------------------------
# Fourier Series
stoacalculator.dfourier([1.0, 2.0, 1.0, -1.0, 1.5])
--------------------------------------------------------------------
# Inverse Fourier Series
stoacalculator.idfourier([0, 4, 0, 0])
--------------------------------------------------------------------
# Sine x Taylor Series
stoacalculator.taylor(90, 5)
--------------------------------------------------------------------
```

_For more examples and usage, please refer to the [Wiki][wiki]._

## Development setup

You'll only need to install these packages via pip; matlibplot, numpy, sympy from python, we also use statistics & math module but python already comes with those, this program already import all those modules. So you won't need to import them in your code.

```sh
pip install matplotlib
pip install numpy
pip install sympy
```

## Release History

- 1.1.0 (08/1/22)
  - Thirty-sixth Release `(Added more geometric functions)`
- 1.0.9 (08/1/22)
  - Thirty-fifth Release `(Added more geometric functions)`
- 1.0.9 (08/1/22)
  - Thirty-fifth Release `(Added more geometric functions)`
- 1.0.8 (08/1/22)
  - Thirty-fourth Release `Performance improvements & bug fixes`
- 1.0.7 (08/1/22)
  - Thirty-third Release `(Added more statistics functions)`
- 1.0.6 (08/1/22)
  - Thirty-second Release `Performance improvements & bug fixes`
- 1.0.5 (08/1/22)
  - Thirty-first Release `(Added more matrix functions)`
- 1.0.4 (08/1/22)
  - Thirtieth Release `Markdown improvements & bug fixes`
- 1.0.3 (31/12/21)
  - Twenty-ninth Release `Performance improvements & bug fixes`
- 1.0.2 (31/12/21)
  - Twenty-eigth Release `Performance improvements & bug fixes`
- 1.0.1 (31/12/21)
  - Twenty-seventh Release `Performance improvements & bug fixes`
- 1.0.0 (31/12/21)
  - Official Release `(Added more statistics functions, trigonometric functions and matrix functions)`
- 0.2.5 (26/12/21)
  - Twenty-fifth Release `(Sine x Taylor Series, base 10 log, base 2 log)`
- 0.2.4 (26/12/21)
  - Twenty-fourth Release `Performance improvements & bug fixes`
- 0.2.3 (26/12/21)
  - Twenty-third Release `Performance improvements & bug fixes`
- 0.2.2 (26/12/21)
  - Twenty-second Release `(Fourier Series & Natural Log of 1+x)`
- 0.2.1 (26/12/21)
  - Twenty-first Release `Performance improvements & bug fixes`
- 0.2.0 (26/12/21)
  - Twentieth Release `(Limits of a function, Laplace, Trunc and Modf Functions, Logarithm of x to the base of b)`
- 0.1.9 (22/12/21)
  - Nineteenth Release `(Partial Fractions, Largest Integer not greater than x, Smallest integer greater than or equal to x.)`
- 0.1.8 (21/12/21)
  - Eighteenth Release `(More Trigonometric Functions (Hyperbolic & Inverse Hyperbolic), Absolute Value & Factorial of a Number, Euclidean Norm between 2 numbers)`
- 0.1.7 (21/12/21)
  - Seventeeth Release `(Return the roots of a polynomial)`
- 0.1.6 (21/12/21)
  - Sixteenth Release `Performance improvements & bug fixes`
- 0.1.5 (21/12/21)
  - Fifteenth Release `(Decimal to Fraction Conversion)`
- 0.1.4 (21/12/21)
  - Fourteenth Release `(Least common divisor & Greatest common divisor)`
- 0.1.3 (21/12/21)
  - Thirteenth Release `Performance improvements & bug fixes`
- 0.1.2 (13/08/21)
  - Twelfth Release `Performance improvements & bug fixes`
- 0.1.1 (13/08/21)
  - Eleventh Release `Performance improvements & bug fixes`
- 0.1.0 (13/08/21)
  - Tenth Release `(Derivatives & Integrals)`
- 0.0.9 (13/08/21)
  - Ninth Release `(Plotting Calculator from Linear to Exponential Equations)`
- 0.0.8 (13/08/21)
  - Eighth Release `Fixed some typos on the script`
- 0.0.7 (13/08/21)
  - Seventh Release `Performance improvements & bug fixes`
- 0.0.6 (13/08/21)
  - Sixth Release `(Basic Statistics (Mean, Mode, Median))`
- 0.0.5 (13/08/21)
  - Fifth Release `(Basic Geometry (Area of basic shapes))`
- 0.0.4 (13/08/21)
  - Fourth Release `(Trigonometric Functions)`
- 0.0.3 (12/08/21)
  - Third Release `(Square Root)`
- 0.0.2 (27/03/21)
  - Second Release `(Powers/Exponents)`
- 0.0.1 (27/03/21)
  - First Release `(Addition, Substraction, Multiplication, Division)`

## Meta

Jorge Eldis ~ [@jorgeeldis](https://twitter.com/jorgeeldis) ~ jorgeeldisg30@gmail.com

Distributed under the MIT license. See `LICENSE` for more information.

[https://github.com/jorgeeldis/](https://github.com/jorgeeldis/)

## Contributing

1. Fork it (<https://github.com/jorgeeldis/StoaCalculator/fork>)
2. Create your feature branch (`git checkout -b feature/fooBar`)
3. Commit your changes (`git commit -am 'Add some fooBar'`)
4. Push to the branch (`git push origin feature/fooBar`)
5. Create a new Pull Request

<!-- Markdown link & img dfn's -->

[wiki]: https://github.com/jorgeeldis/StoaCalculator/wiki
