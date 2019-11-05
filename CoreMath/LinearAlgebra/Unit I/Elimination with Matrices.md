# Elimination with Matrices

##Method of Elimination 

​	**Elimination** is the technique most commonly used by computer software to solve systems of linear equations. It finds a solution x to $A\mathrm{x} = \mathrm{b}$ whenever the matrix $A$ is invertible.  

​	Example,
$$
A=\begin{bmatrix}1&2&1\\
3& 8&1\\
0&4&1\end{bmatrix}and \  
\mathrm{b}=\begin{bmatrix}2\\
12\\
2\end{bmatrix}
$$

​	We started with an **invertible** matrix $A$ and ended with an upper triangular matrix $U$; the lower left portion of $U$ is filled with zeros. Pivots 1, 2, 5 are on 2 the diagonal of $U$.  
$$
A=\begin{bmatrix}1&2&1\\
3& 8&1\\
0&4&1\end{bmatrix} \longrightarrow \begin{bmatrix}1&2&1\\
0& 2&-2\\
0&4&1\end{bmatrix}
 \longrightarrow U=\begin{bmatrix}1&2&1\\
0& 2&-2\\
0&0&5\end{bmatrix}
$$

$$
\mathrm{b}=\begin{bmatrix}2\\
12\\
2\end{bmatrix} \longrightarrow \begin{bmatrix}2\\
6\\
10\end{bmatrix}
$$

​	The method of elimination transforms the equation $A\mathrm{x} = \mathrm{b}$ into a new equation $U\mathrm{x} = \mathrm{c}$. 

​	If there is a zero in the pivot position, we must exchange that row with one below to get a non-zero value in the pivot position.

​	If there is a zero in the pivot position and **no non-zero value below it**, then the matrix A is **not invertible**. Elimination can not be used to find a unique solution to the system of equations – it doesn’t exist.  

## Elimination Matrices 

​	The product of a matrix (3x3) and a column vector (3x1) is a column vector (3x1) that is a linear combination of the columns of the matrix.  
$$
\begin{bmatrix}1&0&0\\
-3& 1&0\\
0&0&1\end{bmatrix}
\begin{bmatrix}1&2&1\\
3& 8&1\\
0&4&1\end{bmatrix}=
\begin{bmatrix}1&2&1\\
0& 2&-2\\
0&4&1\end{bmatrix}
$$
(Which means substract 3 times Row 1 from Row 2)

​	The **elimination matrix** used to eliminate the entry in row $m$ column $n$ is denoted $E_{mn}$. Matrix multiplication is **associative**. Thus $E_{32}(E_{21}A)=U$ also can be wrote as $(E_{32}E_{21})A=U$. The product $E_{32}E_{21}$ tells us how to get from $A$ to $U$. The inverse of the matrix $E_{32}E_{21}$ tells us how to get from $U$ to $A$. If we solve $U\mathrm{x} = EA\mathrm{x} = E\mathrm{b}$, then it is also true that $A\mathrm{x} = \mathrm{b}$.  

​	A **permutation** matrix exchanges two rows of a matrix; for example,
$$
P=\begin{bmatrix}0&1&0\\
1& 0&0\\
0&0&1\end{bmatrix}
$$

## Inverses 

We have a matrix: 
$$
E_{21}=\begin{bmatrix}1&0&0\\
-3& 1&0\\
0&0&1\end{bmatrix}
$$
which subtracts 3 times Row 1 from Row 2. To “undo” this operation we must add 3 times Row 1 to Row 2 using the inverse matrix:  
$$
E_{21}=\begin{bmatrix}1&0&0\\
3& 1&0\\
0&0&1\end{bmatrix}
$$
In fact, $E_{21}^{-1}E_{21}=I$.