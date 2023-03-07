<h1 align="center">FLOAT REPRESENTATION</h1>
<p align="center">
  <img width="460" height="300" src="https://www.c-programming-simple-steps.com/images/IEEE-754-float-representation.png">
</p>

## [MANTISSA](docs/README.md)
* the part of a logarithm after the decimal point in math. (mathematics)
* the part of a floating-point number which represents the significant digits of that number. in omputer  according to OXFORD DICTIONARY

## [EXPONENT](README/CONTRIBUTING.md) 
* An exponent refers to the number of times a number is multiplied by itself.
* For example, 2 to the 3rd (written like this: 23) means: 2 x 2 x 2 = 8. 23 is not the same as 2 x 3 = 6. according to What is an Exponent? [exponents](http://www.mclph.umn.edu/mathrefresh/exponents)

## [BIAS](docs/CONTRIBUTING.md) 
* Algorithmic bias describes systematic and repeatable errors in a computer system that create "unfair" outcomes, such as "privileging" one category over another in ways different from the intended function of the algorithm.

### In IEEE 754 floating-point numbers, the exponent is biased in the engineering sense of the word 
- the value stored is offset from the actual value by the exponent bias, also called a biased exponent. 
- Biasing is done because exponents have to be signed values in order to be able to represent both tiny and huge values, but two's complement, the usual representation for signed values, would make comparison harder" accprding to wikipedia. 

```
[sign][biased exponent][significand]
[0][01111111][00000000000000000000000]
```