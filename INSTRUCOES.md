# INSTRUCOES.md

## 1) How to execute the program
To execute the program, you should run the main file using the command line. Make sure to have the necessary dependencies installed. The command to run is:

```bash
python main.py
```

## 2) Program functionality overview
This program is designed for matrix operations such as addition, subtraction, calculating determinants, transposing matrices, multiplying matrices, and finding inverses. It provides a user-friendly interface for performing these operations in a straightforward manner.

## 3) Detailed explanation of each operation
### Sum/Subtraction
The program allows you to input two matrices and perform addition or subtraction based on user selection. The matrices must be of the same dimension.

### Determinant 3x3
To calculate the determinant of a 3x3 matrix, you input the matrix in a specific format, and the program uses the formula:

```
|A| = a(ei - fh) - b(di - fg) + c(dh - eg)
```
where the matrix A is:
```
| a b c |
| d e f |
| g h i |
```

### Transpose
The transpose operation converts the rows of the matrix into columns. Input the matrix, and the program will output the transposed matrix.

### Multiplication
Matrix multiplication is performed by ensuring the number of columns in the first matrix equals the number of rows in the second matrix. The program handles the multiplication logic internally.

### Inverse 2x2
To find the inverse of a 2x2 matrix, the program uses the formula:

```
A_inv = (1/det(A)) * | d -b |
                 | -c  a |
```
where `det(A)` is the determinant of the matrix A.

## 4) Input/Output examples
### Example 1: Addition
**Input:**
Matrix A:
```
| 1 2 |
| 3 4 |
```
Matrix B:
```
| 5 6 |
| 7 8 |
```
**Output:**
```
| 6 8 |
| 10 12 |
```

### Example 2: Determinant 3x3
**Input:**
Matrix:
```
| 1 2 3 |
| 0 1 4 |
| 5 6 0 |
```
**Output:**
```
|A| = -1
```

## 5) Group members information
- User1: John Doe
- User2: Jane Smith
- User3: Mike Johnson
- User4: Magnunson

Please make sure to update the file as necessary.