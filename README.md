# Testcase Generator

This is a C++ program for generating testcases for algorithmic problems. The program takes in constraints for each test case and generates corresponding input and output files.

## Getting Started
### Prerequisites
To run this program, you'll need to have the following installed:
- C++ compiler
- git

### Installation

```bash
git clone https://github.com/yashshingade28/testcase_generator.git
```
### Usage

To generate testcases, follow these steps:
1) Open the generator.cpp file and set the values of nooftests and noofvars according to the number of test cases and variables you need for your problem.
2) Set the constraints for each test case in the constraint array. The constraint array is a 3D array of integers, where the first dimension represents the test case number, the second dimension represents the variable number, and the third dimension represents the minimum and maximum values of the variable, respectively. For example, constraint[i][j][0] represents the minimum value of the jth variable for the ith test case, and constraint[i][j][1] represents the maximum value of the jth variable for the ith test case.
3) Save the file and compile it using your C++ compiler.
4) Run the compiled executable to generate the input and output files in the input and output folders respectively.

The generated input files will be named inp0.txt, inp1.txt, and so on, while the output files will be named out0.txt, out1.txt, and so on. You can modify the naming convention by changing the testnum variable in the main() function of the program.

To use the generated testcases, write your solution to the problem in the sol.cpp file and compile it. Then, run your compiled program with the corresponding input file as input and compare the output with the corresponding output file generated by the program.

### Example
You can check out the example folder for an example of how to use the generator. The example folder contains a sample problem and its solution along with the generator program.

## Contributing
If you'd like to contribute to this project, feel free to fork the repository and submit a pull request.

## License
This project is licensed under the MIT License - see the LICENSE.md file for details.
