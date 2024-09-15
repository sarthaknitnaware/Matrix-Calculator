# Matrix Calculator

## Overview

This project is a simple **Matrix Calculator** built using Java. It provides basic operations on matrices including **addition**, **subtraction**, and **multiplication**. The user can input two matrices and choose which operation to perform on them. The result of the operation is displayed on the console.

## Features

The project supports the following matrix operations:

1. **Matrix Addition**: Adds two matrices of the same dimensions.
2. **Matrix Subtraction**: Subtracts one matrix from another if they have the same dimensions.
3. **Matrix Multiplication**: Multiplies two matrices where the number of columns in the first matrix equals the number of rows in the second matrix.

## How It Works

- **Matrix Addition**: Adds corresponding elements from the two matrices.
- **Matrix Subtraction**: Subtracts corresponding elements of the second matrix from the first matrix.
- **Matrix Multiplication**: Performs matrix multiplication, where each element in the resulting matrix is the sum of the products of the corresponding row from the first matrix and the column from the second matrix.

The program also includes a method to **display matrices** to the console.

## Code Structure

1. **`add()`**: Adds two matrices element-wise.
2. **`subtract()`**: Subtracts matrix2 from matrix1 element-wise.
3. **`multiply()`**: Multiplies two matrices according to matrix multiplication rules.
4. **`displayMatrix()`**: Displays the matrix in a readable format on the console.

## Getting Started

### Prerequisites

To run this project, you need:

- Java Development Kit (JDK) version 8 or higher
- A basic understanding of Java and matrix operations.

### How to Run

1. **Clone the repository** (if using version control):
   ```bash
   git clone https://github.com/your-username/matrix-calculator.git
   cd matrix-calculator
   ```

2. **Compile the Java file**:
   ```bash
   javac matrixCalculator.java
   ```

3. **Run the program**:
   ```bash
   java matrixCalculator
   ```

4. **Input**:
   - Enter the number of rows and columns for both matrices.
   - Provide the elements of both matrices.
   - Choose the operation (1 for Addition, 2 for Subtraction, or 3 for Multiplication).

### Example

#### Input:

```
Enter the number of rows for matrix 1: 2
Enter the number of columns for matrix 1: 2
Enter elements for matrix 1:
1 2
3 4

Enter the number of rows for matrix 2: 2
Enter the number of columns for matrix 2: 2
Enter elements for matrix 2:
5 6
7 8

Choose the operation:
1. Addition
2. Subtraction
3. Multiplication
```

#### Output (Example for Addition):

```
Matrix Addition:
6 8 
10 12
```


## Future Improvements

- **Matrix Transposition**: Add functionality to transpose matrices.
- **Matrix Inversion**: Implement matrix inversion for square matrices.
- **Handling Exceptions**: Improve error handling for invalid inputs (e.g., mismatched dimensions).
- **Support for Floating-Point Numbers**: Add support for decimal matrix elements.

---

**Enjoy working with matrices using the Matrix Calculator!**
