# Multiplication and Inverse Matrices

## Matrix Multiplication 

We discuss four different ways of thinking about the product $AB = C$ of two matrices. If $A$ is an $m × n$ matrix and $B$ is an $n × p$ matrix, then $C$ is an $m × p$ matrix. We use $c_{ij}$ to denote the entry in row $i$ and column $j$ of matrix $C$.  



## Standard (row times column) 

The standard way of describing a matrix product is to say that $c_{ij}$ equals the dot product of row $i$ of matrix $A$ and column $j$ of matrix $B$. In other words,  
$$
c_{ij}=\sum_{k=1}^n{a_{ik}b_{kj}}
$$

## Columns 

The product of matrix $A$ and column $j$ of matrix $B$ equals column $j$ of matrix $C$. This tells us that the columns of $C$ are combinations of columns of $A$.  



## Rows 

The product of row $i$ of matrix $A$ and matrix $B$ equals row $i$ of matrix $C$. So the rows of $C$ are combinations of rows of $B$.  



## Column times row 

A column of A is an $m × 1$ vector and a row of B is a $1 × p$ vector. Their product is a matrix: 
$$
\begin{bmatrix}2\\
3\\
4\end{bmatrix}\begin{bmatrix}1&6\end{bmatrix} = \begin{bmatrix}2&12\\
3&18\\
4&24\end{bmatrix}
$$
We’ll see that this is equivalent to saying that the *row space* of this matrix is a single line, as is the *column space* .

The product of $A$ and $B$ is the sum of these ”column times row” matrices:  
$$
AB=\sum_{k=1}^{n}\begin{bmatrix}a_{1k}\\
...\\
a_{nk}\end{bmatrix}\begin{bmatrix}b_{k1}&...&b_{kn}\end{bmatrix}
$$

## Blocks 

If we subdivide $A$ and $B$ into blocks that match properly, we can write the product $AB = C$ in terms of products of the blocks: 
$$
\begin{bmatrix}A_1 & A_2\\
A_3 & A_4\end{bmatrix}\begin{bmatrix}B_1 & B_2\\
B_3 & B_4\end{bmatrix} = \begin{bmatrix}C_1 & C_2\\
C_3 & C_4\end{bmatrix}
$$
Here $C_1=A_1B_1+A_2B_3$.

