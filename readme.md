# Tensor OPE Project

This project provides symbolic operations and integrals for calculating the Operator Product Expansion (OPE) of gluon vertex operators with tensor terms. It implements the algorithm described in the appendix of the accompanying paper.

## Files

1. **functions.wl**: Contains all the defined functions used for symbolic computations.
2. **examples.nb**: Includes usage examples demonstrating how to call the functions and their expected outputs.
3. **results.nb**: Stores the results of 6,7 and 8 point verification, showing the agreement between our results with the Queen Mary results.

## How to Use

1. Open `functions.wl` in Mathematica and evaluate the entire notebook to load all functions.
2. Open `examples.nb` and run the cells to see how to use each function step by step.
3. Refer to `results.nb` to check the expected output.

## Example Output

```mathematica
Integrand[{{1, 2, 3}, {4, 5, 6}}, v]
(* Expected output: ... *)