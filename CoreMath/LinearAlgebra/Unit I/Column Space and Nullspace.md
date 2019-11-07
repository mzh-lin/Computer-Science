# Column Space and nullspace

## Review of subspaces

For any two vectors $v$ and $w$ in the space and any two real numbers c and d, the vector $cv + dw $is also in the vector space.  

A plane $P$ containing $\begin{bmatrix}0\\0\\0\end{bmatrix}$ and a line $L$ containing $\begin{bmatrix}0\\0\\0\end{bmatrix}$ are both subspaces of $R^3$. The union $P ∪ L$ of those two subspaces is generally not a subspace, because the sum of a vector in $P$ and a vector in $L$ is probably not contained in $P ∪ L$. The intersection $S ∩ T$ of two subspaces $S$ and $T$ is a subspace. To prove this, use the fact that both $S$ and $ T$ are closed under linear combinations to show that their intersection is closed under linear combinations.  

## Column space of $A$ 

The **column space** of a matrix $A$ is the vector space made up of all linear combinations of the columns of $A$.  

### Solving $A\mathrm{x}=\mathrm{b}$

*For what vectors $\mathrm{b}$ does $A\mathrm{x}=\mathrm{b}$ have a solution $\mathrm{x}$?* 

Let,
$$
A=\begin{bmatrix}1&1&2\\
2&1&3\\
3&1&4\\
4&1&5\end{bmatrix}
$$

Only three columns cannot fill the entire four dimensional vector space – some vectors $\mathrm{b}$ cannot be expressed as linear combinations of columns of $A$.  

The system of linear equations $A\mathrm{x}=\mathrm{b}$ is **solvable** exactly when $b$ is a vector in the column space of $A$.  

## Nullspace of $A$ 

The nullspace of a matrix A is the collection of all solutions $\mathrm{x}=\begin{bmatrix}0\\0\\0\end{bmatrix}$ equation $A\mathrm{x} = 0$.  

$A(X_1+X_2) =AX_1+AX_2=0+0$

$A(cx)=c(Ax)=c(0)$

For example,
$$
\begin{bmatrix}1&1&2\\
2&1&3\\
3&1&4\\
4&1&5\end{bmatrix}\begin{bmatrix}x_1\\
x_2\\
x_3\end{bmatrix}=\begin{bmatrix}0\\
0\\
0\\
0\end{bmatrix}
$$
This nullspace is a line $c\begin{bmatrix}1\\1\\-1\end{bmatrix}$ in $R^3$.

 ### Other values of b 

The solutions to the equation: 
$$
\begin{bmatrix}1&1&2\\
2&1&3\\
3&1&4\\
4&1&5\end{bmatrix}\begin{bmatrix}x_1\\
x_2\\
x_3\end{bmatrix}=\begin{bmatrix}1\\
2\\
3\\
4\end{bmatrix}
$$
do not form a subspace. The zero vector is not a solution to this equation. The set of solutions forms a line in $R^3$ that passes through the points $\begin{bmatrix}1\\0\\0\end{bmatrix}$ and $\begin{bmatrix}0\\-1\\1\end{bmatrix}$ but not $\begin{bmatrix}0\\0\\0\end{bmatrix}$ .  