# Strassen's Algorithm for Matrix Multiplication

This project implements **Strassen's algorithm** for matrix multiplication in Java. Strassen's algorithm is a divide-and-conquer algorithm that reduces the time complexity of matrix multiplication from \(O(n^3)\) to approximately \(O(n^{2.81})\), making it more efficient for large matrices.

## Features

- The user inputs the matrix size.
- The program generates two random matrices of the specified size.
- The matrix multiplication is performed using Strassen's algorithm for sizes divisible by 2, and normal matrix multiplication is used when the size is not divisible by 2.
- The multiplication result is shown along with the execution time.

- An **identity matrix** can be generated and multiplied by a matrix for verification purposes, ensuring that multiplying any matrix by the identity matrix results in the original matrix.
- This section of the code is commented out for generating the identity matrix. Line 81 (StrassenAlgorithm.java file) should be uncommented and line 83 (StrassenAlgorithm.java file) should be commented in this case.

## How to Run the Project

### Prerequisites

- JDK 8 or higher.

### Steps

1. Clone or download the repository from .....
2. Compile the Java files using your preferred IDE or terminal:
   ```bash
   javac StrassenMatrixMultiplication.java
   ```
3. Run the program:
   ```bash
   java StrassenMatrixMultiplication
   ```
4. The program will ask you to enter the matrix size in the terminal. After that, it will generate two matrices, multiply them using Strassen's algorithm, display the result matrix, and show the execution time. 



## Performance

The program measures the execution time of the matrix multiplication process and prints it to allow for performance analysis.


## License

This project is open-source and available under the MIT License.


## Folder Structure

The workspace contains two folders by default, where:

- `src`: the folder to maintain sources
- `lib`: the folder to maintain dependencies

Meanwhile, the compiled output files will be generated in the `bin` folder by default.

