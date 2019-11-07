# Factorization into $A = LU$

> Section 2.6 in the 4th or 5th edition 

## Inverse of a product 

The inverse of a matrix product $AB$ is $B^{−1} A^{−1}$.  

## Transpose of a product 

We obtain the **transpose** of a matrix by exchanging its rows and columns. The transpose of a matrix product $AB$ is $B^TA^T$. For any invertible matrix $A$, the inverse of $A^T$ is  $(A^{−1})^T$ .  

## $A = LU$

> How is $A$ relate to $U$?

The matrix $U$ is upper triangular with pivots on the diagonal. The matrix $L$ is lower triangular and has ones on the diagonal. Sometimes we will also want to factor out a diagonal matrix whose entries are the pivots:  
$$
{A\atop\begin{bmatrix}2&1\\
8&7\end{bmatrix}}{\ \atop=}{L\atop\begin{bmatrix}1&0\\
4&1\end{bmatrix}}{D\atop\begin{bmatrix}2&0\\
0&3\end{bmatrix}}{U'\atop\begin{bmatrix}1&1/2\\
0&1\end{bmatrix}}
$$

In the three dimensional case, if $E_{32}E_{31}E_{21} A = U$ then $A = E^{−1}_{31}E^{−1}_{21}E^{-1}_{32} U =LU$.  

For example, suppose $E_{31}$ is the identity matrix and $E_{32}$ and $E_{21}$ are as shown below:  
$$
{E_{32}\atop\begin{bmatrix}1&0&0\\
0&1&0\\0&-5&1\end{bmatrix}}{E_{21}\atop\begin{bmatrix}1&0&0\\
-2&1&0\\0&0&1\end{bmatrix}}{\ \atop=}{E\atop\begin{bmatrix}1&0&0\\
-2&1&0\\10&-5&1\end{bmatrix}}
$$
The factorization $A = LU$ is preferable to the statement $EA = U$ because the combination of row subtractions does not have the effect on $L$ that it did on $E$. Here $L =E^{−1}= E^{−1}_{21}E^{−1}_{32} $:  
$$
{E_{21}^{-1}\atop\begin{bmatrix}1&0&0\\
2&1&0\\0&0&1\end{bmatrix}}{E_{32}^{-1}\atop\begin{bmatrix}1&0&0\\
0&1&0\\0&5&1\end{bmatrix}}{\ \atop=}{L\atop\begin{bmatrix}1&0&0\\
2&1&0\\0&5&1\end{bmatrix}}
$$
If there are no row exchanges, the multipliers from the elimination matrices are copied directly into $L$.  

## How expensive is elimination? 

A typical operation is to multiply one row and then subtract it from another, which requires on the order of $n$ operations. There are n rows, so the total number of operations used in eliminating entries in the first column is about $n^2$.  

The total number of operations needed to factor A into LU is on the order of $n^3$ :
$$
1^2+2^2+\dots+(n-1)^2+n^2=\sum_{i=1}^ni^2\approx\int_{0}^{n}x^2dx=\frac{1}{3}n^3
$$

## Row exchanges 

To swap two rows, we multiply on the left by a **permutation** matrix. 
$$
P_{12}=\begin{bmatrix}0&1&0\\
1& 0&0\\
0&0&1\end{bmatrix}
$$
There are $n!$ different ways to permute the rows of an $n × n$ matrix (including the permutation that leaves all rows fixed) so there are $n!$ **permutation** matrices. These matrices form a **multiplicative group**.  