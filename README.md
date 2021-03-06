# Fractions

This is a lightweight library for performing arithmetic operations with fractions. In various fields specially in the domain of numerical analysis, we often face a lot of difficulties regarding the accuracy of the floating point operations. Because of rounding off errors in floating point operations and also with problems related to numerical stability. Most of these problems can be tackled conveniently if these operations are done with fractions. This header-only library implements most of the arithmetic operations so that fractions can be used almost as easily as normal integers or floating-point numbers. As shown in the tests, when the [GNU Multiprecision Library](https://gmplib.org/) is used as the backend for this library, all the computations give **exact** results with no chance of overflow ( definitely not division by 0 :P ). The following image shows the output for the exact computations performed by this library for a simple Gauss Elemination implementation.


![Gauss Elemination](https://github.com/DarkStar1997/Fractions/blob/master/screenshots/Gauss%20Elemination/image2.png)



The above image basically shows the solution of a system of equations of the form **AX = B** with 3 unknowns where

A = { 12.34,   23/12,         34,
         98,      23,      35.12,
         73,      41,    123/412, }, with A being a 3ˣ3 matrix
         
B = {    45,   42.23,      98/67  }, with B being a 3ˣ1 matrix

and the solution X also being a 3ˣ1 matrix

## Dependencies

* A C++11 compliant compiler

## Optional Dependencies

* [GNU Multiprecision Library](https://gmplib.org/)
