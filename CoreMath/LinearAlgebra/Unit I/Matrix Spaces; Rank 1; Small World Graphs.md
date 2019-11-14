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
This solution space is a two dimensional vector space with basis vectors $cos x$ and $sin x$ 

###  Rank 4 matrices 

 Now let $M$ be the space of 5 × 17 matrices. The subset of $M$ containing all rank 4 matrices is not a subspace, even if we include the zero matrix, because the sum of two rank 4 matrices may not have rank 4.  

 In $R^4$, the set of all vectors $v=\begin{bmatrix}v_1\\v_2\\v_3\\v_4\end{bmatrix}$, for which $v_1 + v_2 + v_3 + v_4 = 0$ is a subspace. It contains the zero vector and is closed under addition and scalar multiplication. It is the nullspace of the matrix $A=\begin{bmatrix}1&1&1&1\end{bmatrix}$. Because $A$ has rank 1, the dimension of this nullspace is $n − r = 3$. The subspace has the basis of special solutions:  
$$
\begin{bmatrix}-1\\1\\0\\0\end{bmatrix},
\begin{bmatrix}-1\\0\\1\\0\end{bmatrix},
\begin{bmatrix}-1\\0\\0\\1\end{bmatrix}
$$

###  Rank one matrices 

 Every rank 1 matrix $A$ can be written $A = UV^T,$ where $U$ and $V$ are column vectors. We’ll use rank 1 matrices as building blocks for more complex matrices.  
$$
A=\begin{bmatrix}-1&4&5\\2&8&10\\\end{bmatrix}=\begin{bmatrix}-1\\2\\\end{bmatrix}\begin{bmatrix}-1&4&5\end{bmatrix}
$$

###  Small world graphs 

 In this class, a **graph** $G$ is a collection of nodes joined by edges:  

