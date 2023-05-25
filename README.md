# Test Case Generator

This is a test case generator script that utilizes Equivalence Partitioning and Boundary Value Analysis techniques to generate test cases for a given input space.

## Features

- Generates test cases based on Equivalence Partitioning and Boundary Value Analysis principles
- Supports validation of input space to ensure meaningful test case generation
- Handles positive integers within a specified range
- Includes handling of boundary values and non-numeric values

## Usage

1. Set the input range by modifying the `input_space_min` and `input_space_max` variables in the script.
2. Run the script to generate test cases.
3. The generated test cases will be displayed in the console output.

## Validation

The script includes validation checks for the input space to ensure meaningful test case generation. The following validations are performed:

- Maximum value should be greater than the minimum value.
- Maximum value should be at least 3 greater than the minimum value.
- Values must be positive integers.

If the input space fails any of these validations, the script will print the corresponding reason(s) for the invalid input space.

## Techniques Used

The test case generator utilizes two techniques for test case generation:

### Equivalence Partitioning

- Divides the input space into equivalence classes based on the characteristics and behavior of the system under test.
- Generates test cases for each equivalence class to ensure coverage of different scenarios.

### Boundary Value Analysis

- Identifies the boundaries of the input space and tests values at those boundaries.
- Ensures thorough testing of edge cases and potential issues related to boundary values.

## Example Output

Here is an example output of the generated test cases:

Test Case 1: 5 (Type: Equivalence Partitioning, Expected: Valid)
Test Case 2: 10 (Type: Equivalence Partitioning, Expected: Valid)
Test Case 3: 15 (Type: Equivalence Partitioning, Expected: Valid)
Test Case 4: 20 (Type: Equivalence Partitioning, Expected: Valid)
Test Case 5: -5 (Type: Equivalence Partitioning, Expected: Invalid)
Test Case 6: -10 (Type: Equivalence Partitioning, Expected: Invalid)
Test Case 7: -15 (Type: Equivalence Partitioning, Expected: Invalid)
Test Case 8: -20 (Type: Equivalence Partitioning, Expected: Invalid)
Test Case 9: 4 (Type: Boundary Value Analysis, Expected: Invalid)
Test Case 10: 5 (Type: Boundary Value Analysis, Expected: Valid)
Test Case 11: 6 (Type: Boundary Value Analysis, Expected: Valid)
Test Case 12: 19 (Type: Boundary Value Analysis, Expected: Valid)
Test Case 13: 20 (Type: Boundary Value Analysis, Expected: Valid)
Test Case 14: 21 (Type: Boundary Value Analysis, Expected: Invalid)
Test Case 15: A (Type: Non-Numeric Value, Expected: Invalid)
Test Case 16: @ (Type: Non-Numeric Value, Expected: Invalid)


## Contributions

Contributions to the test case generator are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This code is released under the [MIT License](LICENSE).





