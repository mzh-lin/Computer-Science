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

## Inverses 

### Square matrices 

If A is a square matrix, the most important question you can ask about it is whether it has an inverse $A^{−1}$. If it does, then $A^{−1}A=I=AA^{−1}$ and we say that $A$ is **invertible** or **nonsingular**.  

If A is **singular** – $i.e.$ $A$ does not have an inverse – its determinant is zero and we can find some non-zero vector $\mathrm{x}$ for which $A\mathrm{x} = 0$.  For example:
$$
\begin{bmatrix}1 & 3\\
2 &6\end{bmatrix}\begin{bmatrix}3 \\
-1 \end{bmatrix} = \begin{bmatrix}0\\
0\end{bmatrix}
$$
”A times column $j$ of $A^{-1}$equals column $j$ of the identity matrix”. This is just a special form of the equation $A\mathrm{x} = \mathrm{b}$. 

## Gauss-Jordan Elimination 

We can use the method of elimination to solve two or more linear equations at the same time. Just augment the matrix with the whole identity matrix $I$:  
$$
\left[
    \begin{array}{rr|rr}
      1 & 3 & 1 &0\\
      2 & 7 & 0 &1
    \end{array}
\right]
\longrightarrow
\left[
    \begin{array}{rr|rr}
      1 & 3 & 1 &0\\
      0 & 1 & -2 &1
    \end{array}
\right]
\longrightarrow
\left[
    \begin{array}{rr|rr}
      1 & 0 & 7  &-3\\
      0 & 1 & -2 &1
    \end{array}
\right]
$$
Then,
$$
A^{-1}=\begin{bmatrix}7 & -3\\
-2 &1\end{bmatrix}
$$
As in the last lecture, we can write the results of the elimination method as the product of a number of elimination matrices $E_{ij}$ with the matrix $A$. Letting $E$ be the product of all the $E_{ij}$, we write the result of this Gauss-Jordan elimination using block matrices: $E[ A | I ] = [ I | E ]$. But if $EA = I$, then $E = A^{−1}$. 