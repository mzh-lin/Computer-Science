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
If $A\mathrm{x} = \mathrm{b}$ has a solution, then $b3 − b2 − b1 = 0$.  