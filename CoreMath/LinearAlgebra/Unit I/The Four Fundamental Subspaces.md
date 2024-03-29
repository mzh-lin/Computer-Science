# The Four Fundamental Subspaces

##  Four subspaces 

 Any $m$ by $n$ matrix $A$ determines four subspaces :

###  Column space, $C(A)$ 

 $C(A)$ consists of all combinations of the columns of $A$ and is a vector space in $R^m$. 

### Nullspace, N(A) 

This consists of all solutions $x$ of the equation $Ax = 0$ and lies in $R^n$. 

### Row space, $C(A^T)$ 

The combinations of the row vectors of $A$ form a subspace of $R^n$. We equate this with $C(A^T)$, the column space of the transpose of $A$. 

### Left nullspace, $N(A^T)$ 

We call the nullspace of $A^T$ the left nullspace of $A$. This is a subspace of $R^m$.  

##  Basis and Dimension 

###  Column space 

The $r$ pivot columns form a basis for $C(A) $:
$$
dim\ N(A)=r
$$

### Nullspace

The special solutions to $Ax = 0$ correspond to free variables and form a basis for $N(A)$. An $m$ by $n$ matrix has $n − r$ free variables: 
$$
dim\ N(A) = n − r. 
$$

###  Row space 

$$
A=\begin{bmatrix}1&2&3&1\\
1& 1&2&1\\
1&2&3&1\end{bmatrix}\longrightarrow\dots\longrightarrow
\begin{bmatrix}1&0&1&1\\
0& 1&1&0\\
0&0&0&0\end{bmatrix}=\begin{bmatrix}I&F\\
0&0\end{bmatrix}=R
$$

Although the column spaces of $A$ and $R$ are different, the row space of $R$ is the same as the row space of $A$. The rows of $R$ are combinations of the rows of $A$, and because reduction is reversible the rows of $A$ are combinations of the rows of $R$. The first $r$ rows of $R$ are the ”echelon” basis for the row space of $A$: 
$$
dim\ C(A^T) = r.
$$

###  Left nullspace 

The matrix $A^T$ has m columns. We just saw that r is the rank of $A^T$, so the number of free columns of $A^T$ must be $m − r$:  
$$
dim\ N(A^T) = m − r.
$$
The left nullspace is the collection of vectors $y$ for which $A^Ty = 0$. Equivalently, $y^TA = 0$; here $y$ and $0$ are row vectors.  
$$
\begin{bmatrix}A_{m*n}&I_{m*n}\end{bmatrix}\longrightarrow\begin{bmatrix}R_{m*n}&E_{m*n}\end{bmatrix}
$$

$$
EA=\begin{bmatrix}-1&2&0\\
1& -1&0\\
-1&0&1\end{bmatrix}\begin{bmatrix}1&2&3&1\\
1& 1&2&1\\
1&2&3&1\end{bmatrix}=
\begin{bmatrix}1&0&1&1\\
0& 1&1&0\\
0&0&0&0\end{bmatrix}=R
$$

The bottom $m − r$ rows of E satisfy the equation $y^TA = 0$ and form a basis for the left nullspace of $A$.  

## New vector space

The collection of all $3 × 3$ matrices forms a vector space; call it $M$. We can add matrices and multiply them by scalars and there’s a zero matrix (additive identity). If we ignore the fact that we can multiply matrices by each other, they behave just like vectors. 

Some subspaces of $M$ include:  

- all upper triangular matrices  
- all symmetric matrices  
- $D$, all diagonal matrices 

$D$ is the intersection of the first two spaces. Its dimension is 3; one basis for $D$ is: 
$$
\begin{bmatrix}1&0&0\\
0& 0&0\\
0&0&0\end{bmatrix},
\begin{bmatrix}1&0&0\\
0& 3&0\\
0&0&0\end{bmatrix},
\begin{bmatrix}0&0&0\\
0& 0&0\\
0&0&7\end{bmatrix}
$$


