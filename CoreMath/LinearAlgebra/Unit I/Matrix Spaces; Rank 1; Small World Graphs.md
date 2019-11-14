# Matrix Spaces; Rank 1; Small World Graphs

##  New vector space 

###  3 by 3 matrices 

The dimension of $M$ is 9; we must choose 9 numbers to specify an element of $M$. The space M is very similar to $R^9$. A good choice of basis is:  
$$
\begin{bmatrix}1&0&0\\
0& 0&0\\
0&0&0\end{bmatrix},\begin{bmatrix}0&1&0\\
0& 0&0\\
0&0&0\end{bmatrix},
\begin{bmatrix}0&0&1\\
0& 0&0\\
0&0&0\end{bmatrix},\dots\begin{bmatrix}0&0&0\\
0& 0&0\\
0&1&0\end{bmatrix},\begin{bmatrix}0&0&0\\
0& 0&0\\
0&0&1\end{bmatrix}
$$
 The subspace of symmetric matrices $S$ has dimension 6.  
$$
\begin{bmatrix}1&0&0\\
0& 0&0\\
0&0&0\end{bmatrix},\begin{bmatrix}0&1&0\\
1& 0&0\\
0&0&0\end{bmatrix},\begin{bmatrix}0&0&1\\
0& 0&0\\
1&0&0\end{bmatrix},\begin{bmatrix}0&0&0\\
0& 1&0\\
0&0&0\end{bmatrix},
\begin{bmatrix}0&0&0\\
0& 0&1\\
0&1&0\end{bmatrix},
\begin{bmatrix}0&0&0\\
0& 0&0\\
0&0&1\end{bmatrix}
$$
 The dimension of $U$ is again 6;  
$$
\begin{bmatrix}1&0&0\\
0& 0&0\\
0&0&0\end{bmatrix},\begin{bmatrix}0&1&0\\
0& 0&0\\
0&0&0\end{bmatrix},\begin{bmatrix}0&0&1\\
0& 0&0\\
0&0&0\end{bmatrix},\begin{bmatrix}0&0&0\\
0& 1&0\\
0&0&0\end{bmatrix},
\begin{bmatrix}0&0&0\\
0& 0&1\\
0&0&0\end{bmatrix},
\begin{bmatrix}0&0&0\\
0& 0&0\\
0&0&1\end{bmatrix}
$$
 The subspace $D = S ∩ U$ of diagonal 3 by 3 matrices has dimension 3.  

 If we take all possible sums of elements of $S$ and elements of $U$ we get what we call the sum $S + U$. This is a subspace of $M$. In fact,$ S + U = M.$ 
$$
dim S + dim U = dim S ∪ U + dim S ∩ U
$$

###  Differential equations 

The solutions of:
$$
\frac{d^2y}{dx^2}+y=0
$$
is:
$$
y=c_1cosx+c_2cosx,
$$
