# An overview of key ideas 

Linear algebra progresses from vectors to matrices to subspaces.  

## Vector

​	We can multiply vectors by scalars, add, and subtract. Given vector $\mathrm{u}$,$\mathrm{v}$,and $\mathrm{w}$ we can form the **linear combination** $x_1\mathrm{u}+x_2\mathrm{v}+x_3\mathrm{w}=\mathrm{b}$.

​	An example in $\R^3$ would be:  
$$
\mathrm{u}=\begin{bmatrix}1\\-1\\0\end{bmatrix},
\mathrm{v}=\begin{bmatrix}0\\1\\-1\end{bmatrix},
\mathrm{w}=\begin{bmatrix}0\\0\\1\end{bmatrix}
$$
​	The collection of all combinations of $\mathrm{u}$ and $\mathrm{v}$ forms a plane. Taking all combinations of some vectors creates a subspace.

## Matrix

​	Create a matrix A with vectors $\mathrm{u}$ , $\mathrm{v}$ and $\mathrm{w}$ in its columns: 
$$
A =\begin{bmatrix}1&0&0\\
-1& 1&0\\
0&-1&1\end{bmatrix}
$$
The product,  
$$
\begin{align}
A\mathrm{x} &=\begin{bmatrix}1&0&0\\
-1& 1&0\\
0&-1&1\end{bmatrix}\begin{bmatrix}x_1\\x_2\\x_3\end{bmatrix}\\
&=\begin{bmatrix}x_1\\
x_2-x_1\\
x_3-x_2
\end{bmatrix}
=\begin{bmatrix}b_1\\
b_2\\
b_3
\end{bmatrix}
\end{align}
$$
Then,
$$
\begin{align}
\begin{bmatrix}x_1\\
x_2\\
x_3
\end{bmatrix}
=\begin{bmatrix}b_1\\
b_1+b_2\\
b_1+b_2+b_3
\end{bmatrix}
\end{align}
$$
This just says,
$$
\begin{align}
\mathrm{x} &=\begin{bmatrix}1&0&0\\
1& 1&0\\
1&1&1\end{bmatrix}\begin{bmatrix}b_1\\b_2\\b_3\end{bmatrix}\\
\end{align}
$$
