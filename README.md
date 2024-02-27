## Arithmetics.jl

Basic & advanced arithmetic operations and their derivative (for backpropagation) + formatting functions.

## Features
- Arithmetic operations.
- Activation functions.
- Derivative functions.
- Precision formatting.
- Type stable concatenation. (REALLY fast)

## Key Functions
- Basic statistics: `mean`, `std`.
- Activation functions: `relu`, `leakyrelu`, `sigmoid`...: .
- Derivation functions: `∂relu`, `∂leakyrelu`, `∂sigmoid`, `∂abs`...: .
- Stable differentiation: `rel_stable_diff`
- Formatting: `fp_2_floor`, `fp_2_round`
- Constans for standardization: `ϵ`, `ϵ64`
- Concatenation: `vcat_nospread`, `hcat_nospread`, `cat_nospread`, `stack1`

## Usages.
```julia
result = relu(input_value)   # Example: Activation Function
```

## Simple one file repo
Check out the code for more details. https://github.com/Cvikli/Arithmetics.jl/blob/main/src/Arithmetics.jl