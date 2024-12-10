# Python Learning Progress 
 
## Setup (December 8, 2024) 
- Installed VS Code 
- Created virtual environment 
- Installed pytest 
- Created first test file 
- Completed initial environment setup 
 
## Variable Naming Conventions (December 9, 2024)
### Concepts Covered:
- Descriptive vs. generic names: Using meaningful names like `number_to_check` instead of `n`
- Snake case convention: Using underscores for Python variables (`is_prime` not `isPrime`)
- Constant naming: Using uppercase for constants (e.g., `MAX_VALUE = 100`)
- Loop variable conventions: When to use single letters like `i` appropriately
- Boolean naming: Using prefix questions or states (`is_prime`, `has_factors`)

### Code Implementation:
- Refactored number_analysis.py to use clearer variable names:
  * Changed input variable to be more descriptive
  * Used meaningful names for calculation variables
  * Applied proper naming for boolean flags

### Best Practices Noted:
- Avoid single-letter names except in simple loops
- Make names pronounceable and searchable
- Use consistent naming patterns throughout code
- Keep names concise but clear

## Number Theory (December 8, 2024) 
### Concepts Covered: 
- Even/Odd Detection: Using modulo (%) operator to check remainders 
- Prime Numbers: Numbers only divisible by 1 and themselves 
- Factor Finding: Identifying all numbers that divide evenly 
- Perfect Square/Cube Detection (December 9, 2024): Using roots to check for perfect squares and cubes
 
### Code Implementation: 
- Created number_analysis.py with following features: 
  * Even/odd checker using number % 2 
  * Prime number detection using loop and division 
  * Factor finder that prints all divisors
  * Perfect square detection using square root
  * Perfect cube detection using cube root
 
## Next Steps 
- [ ] Implement perfect number detection 
- [ ] Add Fibonacci sequence checker 
- [ ] Add more test cases
- [ ] Add documentation for handling edge cases (negative numbers, zero, etc.)
 
## Questions & Notes