# TODOs

## ImagesToLARModel

- Implement a check for grid sizes
- Implement compression of model

## PngStack2Array3dJulia

## LARUtils

## GenerateBorderMatrix

## ImagesConversion

- Move the creation of models directory outside the loop
- Block merge step and smoothing step could be merged together? (and model compression?)
- Every process takes a copy of the sparse  boundary matrix, try to use a shared array or something similar to reduce network communications
- Use a parameter for controlling number of smoothing iterations
- Study Requires.jl and see if we can use a lazy load for python libraries

## Lar2Julia

## Model2Obj

## Smoother

## Tests

- Update all old tests (they don't work after package refactoring)
- Add new tests for:
  - PngStack2Array3dJulia
  - LARUtils
  - GenerateBorderMatrix
  - Lar2Julia
  - Model2Obj

## Documentation

- Finish documentation for introduction
