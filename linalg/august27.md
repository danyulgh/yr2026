# vectors

$$
\begin{eqnarray}
\text{m components of an m-dimension vector: } \\ \\ 
\vec{u} = {<u_1,u_2,...,u_m>} = 
\begin{bmatrix}  
u_1 \\  
u_2 \\  
... \\
u_m
\end{bmatrix} \\
\vec{u} \in \mathbb{R}^{m*1} \text{: real numbers, m rows, 1 column}
\end{eqnarray}
$$

$$
\begin{eqnarray}
\text{vector addition: } \\ \\
\vec{u}+\vec{v} = 
\begin{bmatrix}
u_1 + v_1 \\
u_2 + v_2 \\ 
... \\
u_3 + v_3 \\
\end{bmatrix}
\end{eqnarray}
$$

$$
\begin{eqnarray}
\text{scalar multiplication: } \\ \\ 
k\vec{u} = 
\begin{bmatrix}  
ku_1 \\  
ku_2 \\  
... \\
ku_m
\end{bmatrix} \\
\end{eqnarray}
$$

$$
\begin{eqnarray}
\text{magnitude = norm of the vector: } \\ \\ 
||\vec{u}|| = 
||\begin{bmatrix}
u_1 \\
u_2 \\
... \\
u_3
\end{bmatrix}||
= \sqrt{u_1^2+u_2^2+...+u_m^2}
\end{eqnarray}
$$

$$
\begin{eqnarray}
\text{distance between two vectors = magnitude of vector difference: } \\ \\ 
d = ||\vec{u}-\vec{v}|| = ||\vec{v}-\vec{u}|| =
||\begin{bmatrix}
u_1 - v_1\\
u_2 - v_2\\
... \\
u_3 - v_3
\end{bmatrix}||
= \sqrt{(u_1-v_1)^2+(u_2-v_2)^2+...+(u_m-v_m)^2}
\end{eqnarray}
$$

$$
\begin{eqnarray}
\text{normalization: } \\ \\
\hat{u} = \frac{\vec{u}}{||\vec{u}||} = \frac{1}{||\vec{u}||} \vec{u} \\ \\
\text{note: } ||\hat{u}|| = 1
\end{eqnarray}
$$