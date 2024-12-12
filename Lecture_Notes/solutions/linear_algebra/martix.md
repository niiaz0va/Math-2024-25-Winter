## 1. Basic Operations on Matrices

For following matrices 

$$
\mathbf{A}=
\begin{pmatrix}
1 & 2 \\
3 & 4 
\end{pmatrix}
\qquad
\mathbf{B}=
\begin{pmatrix}
5 & 6 \\
7 & 8
\end{pmatrix}
\quad
\mathbf{C}=
\begin{pmatrix}-1 & 2 \\
3 & 0
\end{pmatrix}
\qquad
\mathbf{D}=
\begin{pmatrix}-1 & 2 & 3 \\
4 & 0 & 6 
\end{pmatrix}
\qquad
\mathbf{E}=
\begin{pmatrix}
1 & 2\\
4 & 5\\
7 & 8
\end{pmatrix}
$$

1. Calculate: $\mathbf{A}+\mathbf{B}$;  $\mathbf{B}-\mathbf{A}$;  $\mathbf{A}+\mathbf{C}$; $\mathbf{D}+\mathbf{E}$. 

2. Calculate $\frac{1}{2}\mathbf{A}$, $2\mathbf{B}$, $-3\mathbf{C}$, and $4\mathbf{D}$.

3. Calculate the products $\mathbf{A}\cdot \mathbf{B}$; $\mathbf{B} \cdot \mathbf{A}$; $\mathbf{A} \cdot \mathbf{D}$; $\mathbf{D} \cdot \mathbf{E}$.

### solutions 1  :
 #### 1. A+B
 $$
\mathbf{A}
\begin{pmatrix}
1 & 2 \\
3 & 4 
\end{pmatrix}
\qquad+ 
\mathbf{B}
\begin{pmatrix}
5 & 6 \\
7 & 8
\end{pmatrix}
\qquad =
\begin{pmatrix}
6 & 8 \\
10 & 12
\end{pmatrix}.
$$

#### 2. B-A
$$
\mathbf{B}
\begin{pmatrix}
5 & 6 \\
7 & 8
\end{pmatrix}
\qquad - 
\mathbf{A}
\begin{pmatrix}
1 & 2 \\
3 & 4
\end{pmatrix}
\qquad =
\begin{pmatrix}
4 & 4 \\
4 & 4
\end{pmatrix}.
$$

#### 3. A+C
$$
\mathbf{A} = 
\begin{pmatrix}
1 & 2 \\
3 & 4
\end{pmatrix}
\quad + \quad
\mathbf{C} = 
\begin{pmatrix}-1 & 2 \\
3 & 0
\end{pmatrix}
\quad =
\begin{pmatrix}
0 & 4 \\
6 & 4
\end{pmatrix}
$$

#### 4. D+E

D+E is not defined due to incompatible dimensions.

### solutions for 2  :
#### 1. A1/2
$$
\mathbf{A} = 
\begin{pmatrix}
1 & 2 \\
3 & 4
\end{pmatrix}
\quad \times \quad \frac{1}{2} = 
\begin{pmatrix}
\frac{1}{2} & 1 \\
\frac{3}{2} & 2
\end{pmatrix}
$$
#### 2. B*2
$$
\mathbf{B} = 
\begin{pmatrix}
5 & 6 \\
7 & 8
\end{pmatrix}
\quad \times \quad 2 = 
\begin{pmatrix}
10 & 12 \\
14 & 16
\end{pmatrix}
$$

#### 3. -3*C

$$
\mathbf{C} = 
\begin{pmatrix}-1 & 2 \\
3 & 0
\end{pmatrix}
\quad \times \quad -3 = 
\begin{pmatrix}
3 & -6 \\-9 & 0
\end{pmatrix}
$$
#### 4. 4*D
$$
\mathbf{D} = 
\begin{pmatrix}-1 & 2 & 3 \\
4 & 0 & 6
\end{pmatrix}
\quad \times \quad 4 = 
\begin{pmatrix}-4 & 8 & 12 \\
16 & 0 & 24
\end{pmatrix}
$$

### solutions for 3:
#### 1. A*B

$$
\mathbf{A} = 
\begin{pmatrix}
1 & 2 \\
3 & 4
\end{pmatrix}
\quad \text{and} \quad
\mathbf{B} = 
\begin{pmatrix}
5 & 6 \\
7 & 8
\end{pmatrix}
$$

$$
\mathbf{A} \cdot \mathbf{B} = 
\begin{pmatrix}
(1 \cdot 5 + 2 \cdot 7) & (1 \cdot 6 + 2 \cdot 8) \\
(3 \cdot 5 + 4 \cdot 7) & (3 \cdot 6 + 4 \cdot 8)
\end{pmatrix}=
\begin{pmatrix}
19 & 22 \\
43 & 50
\end{pmatrix}
$$

---

#### 2.B*A

$$
\mathbf{B} = 
\begin{pmatrix}
5 & 6 \\
7 & 8
\end{pmatrix}
\quad \text{and} \quad
\mathbf{A} = 
\begin{pmatrix}
1 & 2 \\
3 & 4
\end{pmatrix}
$$

$$
\mathbf{B} \cdot \mathbf{A} = 
\begin{pmatrix}
(5 \cdot 1 + 6 \cdot 3) & (5 \cdot 2 + 6 \cdot 4) \\
(7 \cdot 1 + 8 \cdot 3) & (7 \cdot 2 + 8 \cdot 4)
\end{pmatrix}=
\begin{pmatrix}
23 & 34 \\
31 & 46
\end{pmatrix}
$$

---

#### 3. A*D

$$
\mathbf{A} = 
\begin{pmatrix}
1 & 2 \\
3 & 4
\end{pmatrix}
\quad \text{and} \quad
\mathbf{D} = 
\begin{pmatrix}-1 & 2 & 3\\
4 & 0 & 6
\end{pmatrix}
$$

$$
\mathbf{A} \cdot \mathbf{D} = 
\begin{pmatrix}
(1 \cdot -1 + 2 \cdot 4) & (1 \cdot 2 + 2 \cdot 0) & (1 \cdot 3 + 2 \cdot 6) \\
(3 \cdot -1 + 4 \cdot 4) & (3 \cdot 2 + 4 \cdot 0) & (3 \cdot 3 + 4 \cdot 6)
\end{pmatrix}=
\begin{pmatrix}
7 & 2 & 15 \\
13 & 6 & 33
\end{pmatrix}
$$

---

#### 4. D*E
$$
\mathbf{D} = 
\begin{pmatrix}-1 & 2 & 3\\
4 & 0 & 6
\end{pmatrix}
\quad \text{and} \quad
\mathbf{E} = 
\begin{pmatrix}
1 & 2 \\
4 & 5 \\
7 & 8
\end{pmatrix}
$$

$$
\mathbf{D} \cdot \mathbf{E} = 
\begin{pmatrix} -1 & 2 & 3 \\
4 & 0 & 6
\end{pmatrix}
\cdot
\begin{pmatrix}
1 & 2 \\
4 & 5 \\
7 & 8
\end{pmatrix} =
\begin{pmatrix}
(-1 \cdot 1 + 2 \cdot 4 + 3 \cdot 7) & (-1 \cdot 2 + 2 \cdot 5 + 3 \cdot 8) \\
(4 \cdot 1 + 0 \cdot 4 + 6 \cdot 7) & (4 \cdot 2 + 0 \cdot 5 + 6 \cdot 8)
\end{pmatrix} =
\begin{pmatrix}
28 & 32 \\
46 & 56
\end{pmatrix}
$$

---
![alt text](<Снимок экрана 2024-12-12 082440.png>)
---
