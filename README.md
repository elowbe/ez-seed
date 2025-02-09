# ez-seed

## Overview
A utility module that manages seed generation for random number operations. It either uses a provided seed value or generates a new random seed when none is specified or when the input is invalid.

## Module Inputs
- **seed**: A numerical value used as the seed for random number generation. Accepts a double value.

## Module Outputs
- **seed_**: The final seed value used for random number generation. Outputs as an integer.

## Notes
- If the input seed is empty or less than 0, the module will generate a new random seed
- The output is always a valid integer that can be used for seeding random number generators
