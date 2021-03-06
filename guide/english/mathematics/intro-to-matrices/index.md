---
title: Intro to Matrices
---
## Intro to Matrices
A matrix is a 2D array of values. Below you can see how its organized.

![alt text](https://upload.wikimedia.org/wikipedia/commons/thumb/b/bb/Matrix.svg/494px-Matrix.svg.png)


It is composed by rows, and columns. Each position can be found with (row number, column number). For example, if you want the number 7 of the matrix below, you need to get the element on the position (2,3), second row (because it is the row number), third column (because it is the column number). Another example would be if you want to get the position of the number 1 below. The position would be (2, 1) because it is on row 2 and column 1.

![alt text](https://wikimedia.org/api/rest_v1/media/math/render/svg/55375914df4213b621f22cb1e5a0d6eb09af29df)

The usuals operations works for matrices, but adddition and subtraction is made on the elements of the same position (so the two matrices needs to have the same size). Multiplication is different so matrix A x matrix B, A needs to have the same size of transpose of B. 

Transpose is the operations of inver the rows and columns of a matrix.

![alt text](https://wikimedia.org/api/rest_v1/media/math/render/svg/51f6dba024e104b412ed0562163ca9a11fcb9463)

You can also think of it as the column num of matrix A needs to be the same as the row size of matrix B. The size of the new array is the row num of matrix A and the column num of matrix B.

#### Types of Matrices
1. Square Matrix- A matrix with equal no. of rows and columns is called a square matrix.

2. Diagonal Matrix- A square matrix with only diagonal elements as non-zero elements. For example: 
  ![alt text](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQQgGANz1Dgr3d4tzSkJjS4LMIeM3MGsC2LO6wcKMQXHHCg10ax)

3. Scalar Matrix- A diagonal matrix is said to be scalar if all of its diagonal elements are the same.
  ![alt text](https://qph.fs.quoracdn.net/main-qimg-1cbbbaac2443a2725acedfe63b95f2e5)
  
4. Identity Matrix- A diagonal matrix is said to be identity if all of its diagonal elements are equal to one, denoted by I.
  ![alt text](https://qph.fs.quoracdn.net/main-qimg-6f2d174e18b8a327973289af2eca72ec)
  
5. Triangular Matrix: A square matrix is said to be triangular if all of its elements above the principal diagonal are zero (lower triangular matrix) or all of its elements below the principal diagonal are zero (upper triangular matrix).
  ![alt text](https://3.bp.blogspot.com/-vR6xL2kgNIw/WK18Gw-xzwI/AAAAAAAAALA/g0ihK15Juug152JBZeZ31rb8Rx5tUsuQQCLcB/s1600/ltm.png)


#### Addition and Subraction of Matrices
To add or subtract matrices, they must be the same size. For example, if I had a 3x3 matrix, I can only add with another 3x3 martrix. To add or subtract, get the first position of the first matrix, and add or subtract to the first position on the second matrix. Do this for all of the positions. You will end up with a new matrix with the addition or subtraction. 

![alt text](https://mathpullzone-8231.kxcdn.com/wp-content/uploads/add-two-matrices.jpg)
![alt text](https://mathpullzone-8231.kxcdn.com/wp-content/uploads/subtracting-matrices.jpg)

#### More Information:
[Wikipedia](https://en.wikipedia.org/wiki/Matrix_(mathematics))
