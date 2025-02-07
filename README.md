# Integer Division Truncation Bug in C
This repository demonstrates an example of integer division truncation in C.  Integer division in C discards the fractional part of the result, potentially leading to inaccurate calculations.  This is a common pitfall for developers unfamiliar with the behavior of integer division. The solution demonstrates using floating-point numbers to obtain more precise results. 

## Bug
The `bug.c` file shows a simple example where integer division leads to truncation. Dividing an integer by another integer results in an integer without a fractional part. 

## Solution
The `bugSolution.c` file demonstrates a solution where floating-point numbers are used to avoid the truncation issue. Casting the integers to `float` or `double` before division maintains the fractional part of the result, resulting in a more accurate calculation.