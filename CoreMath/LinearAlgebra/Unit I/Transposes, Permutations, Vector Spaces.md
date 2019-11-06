# Transposes, Permutations, Vector Spaces $R^n$



## Permutations

Multiplication by a permutation matrix $P$ swaps the rows of a matrix; Our factorization $A = LU$ then becomes $PA = LU$, where $P$ is a **permutation** matrix which reorders any number of rows of $A$. Recall that $P^{−1} = P^{T}$, $i.e$. that $P^TP = I$. 



## Transposes 

We can describe $A^T$ by: $A^T_{ij}  = A_{ji} $.

A matrix $A$ is **symmetric** if $A^T = A$. Given any matrix $R$ (not necessarily square) the product $R^TR$ is always **symmetric**, because $(R^TR)^T = R^T(RT)^T = R^TR$. (Note that $(R^T)^T = R$.) 

## Vector spaces 

We can add vectors and multiply them by numbers, which means we can discuss **linear combinations** of vectors. These combinations follow the rules of a **vector space**. 

One such vector space is $R^2$, the set of all vectors with exactly two real number components. 



## Closure 

The collection of vectors with exactly two **positive** real valued components is not a vector space. Why? The sum of any two vectors in that collection is again in the collection, but multiplying any vector by, say, −5, gives a vector that’s not in the collection. 



If a collection of vectors is *closed* under linear combinations ($i.e.$ under addition and multiplication by any real numbers), and if multiplication and addition behave in a reasonable way, then we call that collection a **vector space**. 

## Subspaces 

A vector space that is contained inside of another vector space is called a subspace of that space. 

The subspaces of $R^2$ are: 

1. all of $R^2$
2. any line through $\begin{bmatrix}0\\0\end{bmatrix}$ and
3. the zero vector alone $(Z)$

The subspaces of $R^3$ are: 

1. all of $R^3$
2. any plane through the origin,
3. any line through the origin, and,
4. the zero vector alone $(Z)$.

## Column space 

Given a matrix $A$ with columns in $R^3$, these columns and all their linear combinations form a subspace of $R^3$. This is the column space $C(A)$. 

If $A=\begin{bmatrix}1&3\\2&3\\4&1\end{bmatrix}$, the column space of $A$ is the plane through the origin in $R^3$ containing  $\begin{bmatrix}1\\2\\4\end{bmatrix}$ and $\begin{bmatrix}3\\3\\1\end{bmatrix}$.