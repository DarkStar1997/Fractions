# Fractions

This is a lightweight library for performing arithmetic operations with fractions. In various fields specially in the domain of numerical analysis, we often face a lot of difficulties regarding the accuracy of the floating point operations. Because of rounding off errors in floating point operations and also with problems related to numerical stability. Most of these problems can be tackled conveniently if these operations are done with fractions. This header-only library implements most of the arithmetic operations so that fractions can be used almost as easily as normal integers or floating-point numbers. As shown in the tests, when the [GNU Multiprecision Library](https://gmplib.org/) is used as the backend for this library, all the computations give **exact** results with no chance of overflow ( definitely not division by 0 :P ).

## Dependencies

* A C++11 compliant compiler

## Optional Dependencies

* [GNU Multiprecision Library](https://gmplib.org/)
