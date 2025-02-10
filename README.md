# JavaScript Loose Comparison Bug

This repository demonstrates a common JavaScript bug caused by the use of loose comparison (==) instead of strict comparison (===). Loose comparison can lead to unexpected behavior when comparing values of different types.

## Bug Description
The `foo` function aims to return 0 for null, -1 for negative numbers, and 1 for non-negative numbers. However, due to loose comparison, the function incorrectly returns 1 for the input 0.

## Bug Solution
The solution involves replacing the loose comparison (==) with strict comparison (===) to ensure type safety and produce the expected output.