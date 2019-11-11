# Solving $A\mathrm{x} = \mathrm{b}$: row reduced form $R$

##  Solvability conditions on $\mathrm{b}$

Example:
$$
A=\begin{bmatrix}1&2&2&2\\
2&4&6&8\\
3&6&8&10\\\end{bmatrix}
$$
 If $\mathrm{b}$ does not satisfy $b3 = b1 + b2$ the system has no solution.  

One way to find out whether $A\mathrm{x} = \mathrm{b}$ is solvable is to use elimination on the augmented matrix.  
$$
\begin{bmatrix}1&2&2&2&b_1\\
2&4&6&8&b_2\\
3&6&8&10&b_3\\\end{bmatrix}\longrightarrow\dots\longrightarrow\begin{bmatrix}1&2&2&2&b_1\\
0&0&2&4&b_2\\
0&0&0&0&b_3\\\end{bmatrix}
$$
If $A\mathrm{x} = \mathrm{b}$ has a solution, then $b3 − b2 − b1 = 0$. $A\mathrm{x} = \mathrm{b}$ is solvable exactly when b is in the column space $C(A)$ .

## Complete solution

### A particular solution

One way to find a particular solution to the equation $A\mathrm{x} = \mathrm{b}$ is to set all free variables to zero, then solve for the pivot variables.  

For example,
$$
\begin{align}
x_1+2x_3=1\\
2x_3=3
\end{align}
$$
which has the solution $x3 = 3/2, x1 = −2$. Our particular solution is:  
$$
A=\begin{bmatrix}-2\\
0\\
3/2\\
0\\\end{bmatrix}
$$

### Combined with the nullspace 

The general solution to $A\mathrm{x} = \mathrm{b}$ is given by $x_{complete} = x_p + x_n$, where $x_n$ is a generic vector in the nullspace.  

The nullspace of A is the collection of all combinations of the special solutions  $\begin{bmatrix}-2\\1\\0\\0\\\end{bmatrix}$ and $\begin{bmatrix}2\\0\\-2\\1\\\end{bmatrix}$. So the complete solution to the equation $A\mathrm{x} =\begin{bmatrix}1\\5\\6\\\end{bmatrix}$ is:
$$
x_{complete}=\begin{bmatrix}-2\\
0\\
3/2\\
0\\\end{bmatrix}+c_1\begin{bmatrix}-2\\1\\0\\0\\\end{bmatrix}+c_2\begin{bmatrix}2\\0\\-2\\1\\\end{bmatrix}
$$

## Rank

The rank of a matrix equals the number of pivots of that matrix. If $A$ is an $m$ by $n$ matrix of rank $r$, we know $r ≤ m$ and $r ≤ n$.

### Full column rank

If $r = n$, then from the previous lecture we know that the nullspace has dimension $n − r = 0 $ and contains only the zero vector. There are no free variables or special solutions.  

The row reduced echelon form of the matrix will look like $R=\begin{bmatrix}I\\0\end{bmatrix}$ .

### Full row rank 

If $r = m$, then the reduced matrix $R = \begin{bmatrix}I&F\end{bmatrix}$ has no rows of zeros and so there are no requirements for the entries of $b$ to satisfy. There are $n − r = n − m$ free variables, so there are $n − m$ special solutions to $A\mathrm{x} = 0$.

### Full row and column rank 

If $r = m = n$ is the number of pivots of A, then A is an invertible square matrix and R is the identity matrix.  

### Summary

|                                         | $r=m=n$ | $r=n<m$                            | $r=m<n$                           | $r<m,r<n$                              |
| --------------------------------------- | ------- | ---------------------------------- | --------------------------------- | -------------------------------------- |
| R                                       | $I$     | $\begin{bmatrix}I\\0\end{bmatrix}$ | $\begin{bmatrix}I&F\end{bmatrix}$ | $\begin{bmatrix}I&F\\0&0\end{bmatrix}$ |
| solutions to $A\mathrm{x} = \mathrm{b}$ | 1       | 0 or 1                             | infinitely many                   | 0 or infinitely many                   |

## Reference

[Solving $A\mathrm{x} = \mathrm{b}$: row reduced form $R$](https://ocw.mit.edu/courses/mathematics/18-06sc-linear-algebra-fall-2011/ax-b-and-the-four-subspaces/solving-ax-b-row-reduced-form-r/MIT18_06SCF11_Ses1.8sum.pdf )