# Julia Function Bug

This repository demonstrates a simple bug in a Julia function that handles negative inputs incorrectly. The function `myfunction` is intended to return the square of a positive input and 0 for non-positive inputs. However, it currently does not correctly handle negative numbers, leading to unexpected results.

## Bug Description
The function `myfunction` does not correctly handle negative input.  It should return 0 for negative inputs, but it produces unexpected outputs instead.

## Solution
The solution addresses this by explicitly checking for and handling negative inputs to return 0 as intended.
