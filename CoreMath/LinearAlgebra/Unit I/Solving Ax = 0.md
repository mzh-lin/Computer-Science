# Solving Ax = 0: pivot variables, special solutions 

## Computing the nullspace 

The nullspace of a matrix $A$ is made up of the vectors $x$ for which $Ax = 0$ 

Suppose:
$$
A=\begin{bmatrix}1&2&2&2\\
2&4&6&8\\
3&6&8&10\\\end{bmatrix}
$$
The first step of elimination gives us:  
$$
A=\begin{bmatrix}1&2&2&2\\
2&4&6&8\\
3&6&8&10\\\end{bmatrix}\longrightarrow\begin{bmatrix}1&2&2&2\\
0&0&2&4\\
0&0&2&4\\\end{bmatrix}
$$

$$
\begin{bmatrix}1&2&2&2\\
0&0&2&4\\
0&0&2&4\\\end{bmatrix}\longrightarrow\begin{bmatrix}1&2&2&2\\
0&0&2&4\\
0&0&0&0\\\end{bmatrix}=U
$$

The matrix $U$ is in **echelon (staircase)** form.  

The rank of a matrix $A$ equals the number of pivots it has. In this example, the rank of $A$ (and of $U$) is 2.  

## Special solutions 

 In our example, columns 1 and 3 are **pivot columns** containing pivots, and columns 2 and 4 are **free columns**. 

The rank $r$ of $A$ equals the number of pivot columns, so the number of free columns is $n − r$: the number of columns (variables) minus the number of pivot columns. This equals the number of special solution vectors and the dimension of the nullspace.

## Reduced row echelon form 

By continuing to use the method of elimination we can convert U to a matrix R in **reduced row echelon form (rref form)**, with pivots equal to 1 and zeros above and below the pivots.  
$$
U=\begin{bmatrix}1&2&2&2\\
0&0&2&4\\
0&0&0&0\\\end{bmatrix}\longrightarrow\begin{bmatrix}1&2&0&-2\\
0&0&2&4\\
0&0&0&0\\\end{bmatrix}\longrightarrow\begin{bmatrix}1&2&0&-2\\
0&0&1&2\\
0&0&0&0\\\end{bmatrix}=R
$$
If some rows of $A$ are linearly dependent, the lower rows of the matrix $R$ will be filled with zeros:  
$$
R=\begin{bmatrix}I&F\\
0&0\end{bmatrix}
$$
If $N$ is the nullspace matrix $N = \begin{bmatrix}-F\\I\end{bmatrix}$ then $RN = 0$. (Here $I$ is an $n − r$ by $n − r$ square matrix and $0$ is an $m$ by $n − r$ matrix.) The columns of $N$ are the special solutions.  