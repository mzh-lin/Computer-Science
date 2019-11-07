# The geometry of linear equations

Example:
$$
\begin{aligned}
2x+y=0\\
-x+2y=3
\end{aligned}
$$
The fundamental problem of linear algebra is to solve n linear equations in n unknowns.

* Row Picture
* Column Picture
* Matrix Picture

## Row Picture

The intersection of the plots (if they do intersect) represents the solution to the system of equations. 

![1572879482897](E:\GitHub\Computer-Science\CoreMath\LinearAlgebra\Unit I\1572879482897.png)

The Row Equations is like:
$$
\begin{bmatrix}2 & -1 \\-1 & 2\end{bmatrix}*\begin{bmatrix}x\\y\end{bmatrix} = \begin{bmatrix}0\\3\end{bmatrix}
$$

## Column Picture

In the column picture we rewrite the system of linear equations as a single equation by turning the coefficients in the columns of the system into vectors: 
$$
x*\begin{bmatrix}2\\-1\end{bmatrix}+y*\begin{bmatrix}-1\\2\end{bmatrix} = \begin{bmatrix}0\\3\end{bmatrix}
$$
the $xc+yd$ is called a **linear combination** of $c$ and $d$. 

Geometrically,

![1572880006551](E:\GitHub\Computer-Science\CoreMath\LinearAlgebra\Unit I\1572880006551.png)

## Matrix Picture 

Consider a single equation by using matrices and vectors :
$$
\begin{bmatrix}2 & -1 \\-1 & 2\end{bmatrix}\begin{bmatrix}x\\y\end{bmatrix} = \begin{bmatrix}0\\3\end{bmatrix}
$$
The matrix $A = \begin{bmatrix}2 & -1 \\-1 & 2\end{bmatrix} $ is called the *coefficient matrix*. The vector $\mathrm{x}  = \begin{bmatrix}x \\ y\end{bmatrix}$ is the vector of unknowns. The values on the right hand side of the y equations form the vector $b$: 
$$
A\mathrm{x} = \mathrm{b}
$$

## Matrix Multiplication

How do we multiply a matrix $A $ by a vector $\mathrm{x}$ ?  

One method is to think of the entries of $\mathrm{x} $ as the coefficients of a **linear combination** of the column vectors of the matrix:  
$$
\begin{aligned}
\begin{bmatrix}2 & 5 \\1 & 3\end{bmatrix}\begin{bmatrix}1\\2\end{bmatrix} &= 1*\begin{bmatrix}2\\1\end{bmatrix}+2*\begin{bmatrix}5\\3\end{bmatrix}\\
&=\begin{bmatrix}2·1+5·2\\1·1+3·2\end{bmatrix}\\
&=\begin{bmatrix}12\\7\end{bmatrix} 
\end{aligned}
$$

## Linear Independence 

Given a matrix A, can we solve:  
$$
A\mathrm{x} =\mathrm{b}
$$
for every possible vector $\mathrm{b} $?  

​	If the answer is “no”, we say that A is a singular matrix. In this singular case its column vectors are linearly dependent; all linear combinations of those vectors lie on a point or line (in two dimensions) or on a point, line or plane (in three dimensions). **The combinations don’t fill the whole space**.  

## Reference

[The Geometry of Linear Equations](https://ocw.mit.edu/courses/mathematics/18-06sc-linear-algebra-fall-2011/ax-b-and-the-four-subspaces/the-geometry-of-linear-equations/MIT18_06SCF11_Ses1.1sum.pdf )