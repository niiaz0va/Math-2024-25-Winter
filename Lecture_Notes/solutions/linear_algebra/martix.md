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

## 14. Equations of lines on a plane

### 3. The line passes through point 
 A(1, 2) and is perpendicular to the line 
 y = 2x + 3 .

---

### 1: Find the slope of the given line

The slope of the line $y = 2x + 3$ is $m_1 = 2$.

### 2: Determine the slope of the perpendicular line

$$
m_1 \cdot m_2 = -1
$$

$$
2 \cdot m_2 = -1
$$

$$
m_2 = -\frac{1}{2}
$$

### 3: Write the equation of the line

$$
y - y_1 = m(x - x_1)
$$

$$
y - 2 = -\frac{1}{2}(x - 1)
$$

### 4: Simplify the equation

Expand and simplify:

$$
y - 2 = -\frac{1}{2}x + \frac{1}{2}
$$

$$
y = -\frac{1}{2}x + \frac{5}{2}
$$

So, the equation of the line is:

$$
y = -\frac{1}{2}x + \frac{5}{2}
$$

---

### 4. To find the intersection point and the angle between the lines  y = 2x + 3  and  y = 3x + 2 .

### 1: Find the intersection point

$$
2x + 3 = 3x + 2
$$

Simplify:

$$
3 = x + 2
$$

$$
x = 1
$$

Substitute  x = 1  into either equation to find y:

$$
y = 2(1) + 3 = 5
$$

Thus, the intersection point is:

$$
(1, 5)
$$

---

### 2: Find the angle between the two lines

The slopes of the lines are: 

$$ m_1 = 2 \quad \text{from} \quad y = 2x + 3 $$ 

$$ m_2 = 3 \quad \text{from} \quad y = 3x + 2 $$

The angle between the lines is given by:

$$ 
\tan\theta = \left| \frac{m_2 - m_1}{1 + m_1 m_2} \right|
$$

Substitute 
$ m_1 = 2 $ and $ m_2 = 3 $:

$$
\tan\theta = \left| \frac{3 - 2}{1 + (2)(3)} \right| = \left| \frac{1}{7} \right|
$$

Now, find the angle by taking the arctangent:

$$ 
\theta = \arctan\left( \frac{1}{7} \right)
$$

---

### **Finally**

- **Intersection Point**:  (1, 5) 
- **Angle Between the Lines**:

$$
\theta = \arctan\left( \frac{1}{7} \right) \approx 8.13^\circ
$$

---

### 5. Find the equation of a line passing through the point A(1, 2) and parallel to the vector $\mathbf{v} = [2, 3]$

---

### 1: Parametric equation of the line

$$
x = x_1 + t v_x
$$

$$
y = y_1 + t v_y
$$

where $ t $ is a parameter

$$
x = 1 + 2t
$$

$$
y = 2 + 3t
$$

---

### 2: Eliminate the parameter $ t $ to find the Cartesian form

From the parametric equation $ x = 1 + 2t $, solve for $ t $:

$$
t = \frac{x - 1}{2}
$$

Substitute this expression for $ t $ into $ y = 2 + 3t $:

$$
y = 2 + 3\left(\frac{x - 1}{2}\right)
$$

Simplify:

$$
y = 2 + \frac{3(x - 1)}{2}
$$

$$
y = 2 + \frac{3x}{2} - \frac{3}{2}
$$

$$
y = \frac{3x}{2} + \frac{4}{2} - \frac{3}{2}
$$

$$
y = \frac{3x}{2} + \frac{1}{2}
$$

---

### Finally:

$$
y = \frac{3}{2}x + \frac{1}{2}
$$

---

### 6. We are given the line equation $ y = 2x + 3 $

### 1. Line Parallel to $ y = 2x + 3 $:

The slope of the parallel line will also be 2.

$$
y = 2x + b
$$

where $ b $ is any y-intercept. For example, if $ b = 1 $, the equation of the parallel line is:

$$
y = 2x + 1
$$

### 2. Line Perpendicular to $ y = 2x + 3 $:

Two lines are perpendicular if the product of their slopes is $-1$. Let the slope of the perpendicular line be $ m' $. The relationship between the slopes of the given line and the perpendicular line is:

$$
m \cdot m' = -1
$$

Given that the slope of the original line is $ m = 2 $, we solve for $ m' $:

$$
2 \cdot m' = -1 \quad \Rightarrow \quad m' = -\frac{1}{2}
$$

Thus, the slope of the perpendicular line is $ m' = -\frac{1}{2} $. The equation of a perpendicular line can be written as:

$$
y = -\frac{1}{2}x + b
$$

where $ b $ is any y-intercept. For example, if $ b = 4 $, the equation of the perpendicular line is:

$$
y = -\frac{1}{2}x + 4
$$

---

### Finally:

- A parallel line: $ y = 2x + 1 $
- A perpendicular line: $ y = -\frac{1}{2}x + 4 $

---

### 7. To find the distance from a point $ A(x_1, y_1) $ to a line given by the equation $ Ax + By + C = 0 $, we use the following formula:

$$
\text{Distance} = \frac{|Ax_1 + By_1 + C|}{\sqrt{A^2 + B^2}}
$$

### Step 1: Rewrite the equation of the line in the form $ Ax + By + C = 0 $

The given line equation is $ y = 2x + 3 $. We can rewrite it in standard form by subtracting $ y $ from both sides:

$$
y - 2x - 3 = 0
$$

This gives $ A = -2 $, $ B = 1 $, and $ C = -3 $.

### Step 2: Apply the formula

The coordinates of point $ A $ are $ (x_1, y_1) = (1, 2) $. Substituting $ x_1 = 1 $, $ y_1 = 2 $, $ A = -2 $, $ B = 1 $, and $ C = -3 $ into the formula:

$$
\text{Distance} = \frac{|(-2)(1) + (1)(2) - 3|}{\sqrt{(-2)^2 + 1^2}} = \frac{| -2 + 2 - 3 |}{\sqrt{4 + 1}} = \frac{|-3|}{\sqrt{5}} = \frac{3}{\sqrt{5}}
$$

### Step 3: Simplify the expression

To rationalize the denominator:

$$
\text{Distance} = \frac{3}{\sqrt{5}} \cdot \frac{\sqrt{5}}{\sqrt{5}} = \frac{3\sqrt{5}}{5}
$$

### Finally:

The distance from point $ A(1, 2) $ to the line $ y = 2x + 3 $ is:

$$
\frac{3\sqrt{5}}{5}
$$

---

### 8. We are given that the line intersects the coordinate axes at points $ A(2, 0) $ and $ B(0, 3) $. Find the equation of the line, we can use the **two-point form** of the equation of a line, which is:

$$
y - y_1 = m(x - x_1)
$$

### Step 1: Find the slope of the line

The slope $ m $ of the line through points $ A(2, 0) $ and $ B(0, 3) $ is given by the formula:

$$
m = \frac{3 - 0}{0 - 2} = \frac{3}{-2} = -\frac{3}{2}
$$

### Step 2: Write the equation of the line

Substitute the slope $ m = -\frac{3}{2} $ and point $ A(2, 0) $ into the two-point form:

$$
y - 0 = -\frac{3}{2}(x - 2)
$$

Simplify the equation:

$$
y = -\frac{3}{2}(x - 2)
$$

### Step 3: Expand the equation

$$
y = -\frac{3}{2}x + 3
$$

### Finally:

The equation of the line is:

$$
y = -\frac{3}{2}x + 3
$$

---

### 9. We are given the line equation $ y = x + 3 $, need to calculate the angle between the line and the $ Ox $-axis.

### Step 1: Find the slope of the line

The equation of the line is in slope-intercept form $ y = mx + b $, where $ m $ is the slope. From the equation $ y = x + 3 $, we see that the slope $ m = 1 $.

### Step 2: Use the formula for $ \theta $, the angle between the line and the $ Ox $-axis

$$
\tan(\theta) = m
$$

Substituting $ m = 1 $ into the formula:

$$
\tan(\theta) = 1
$$

### Step 3: To find $ \theta $, take the inverse tangent (arctan) of both sides:

$$
\theta = \tan^{-1}(1)
$$

From trigonometry, we know that:

$$
\theta = 45^\circ
$$

### Final Answer:

The angle between the line $ y = x + 3 $ and the $ Ox $-axis is:

$$
\theta = 45^\circ
$$

---

### 10. We are given the line equation $ x + y + 1 = 0 $, and we need to find a vector perpendicular to this line.

---

## 15. Equations of second-order curves (conic sections)

### 1. The equation of a circle with center at point $ A(h, k) $ and radius $ r $ is given by the standard form:

$$
(x - h)^2 + (y - k)^2 = r^2
$$

### Given:

- Center $ A(1, 2) $, so $ h = 1 $ and $ k = 2 $.
- Radius $ r = 3 $, so $ r^2 = 9 $.

### Substitute the values into the equation

Substitute $ h = 1 $, $ k = 2 $, and $ r = 3 $ into the general equation:

$$
(x - 1)^2 + (y - 2)^2 = 9
$$

---

### 2. To find the equation of a parabola intersecting the $ Ox $ axis at points $ x = 2 $ and $ x = 4 $, and passing through the point $ (3, 1) $, we can proceed as follows:

### Step 1: General Form of the Parabola

Since the parabola intersects the $ Ox $ axis at $ x = 2 $ and $ x = 4 $, we can express the equation of the parabola as:

$$
y = a(x - 2)(x - 4)
$$

where $ a $ is a constant to be determined.

### Step 2: Use the Point $ (3, 1) $

We know the parabola passes through the point $ (3, 1) $. Substituting $ x = 3 $ and $ y = 1 $ into the equation:

$$
1 = a(3 - 2)(3 - 4)
$$

This simplifies to:

$$
1 = a(1)(-1)
$$

$$
1 = -a
$$

Thus, we find:

$$
a = -1
$$

### Step 3: Write the Final Equation

Substitute $ a = -1 $ into the equation of the parabola:

$$
y = -1(x - 2)(x - 4)
$$

Simplifying:

$$
y = -(x - 2)(x - 4)
$$

Expanding:

$$
y = -x^2 + 6x - 8
$$

Thus, the equation of the parabola is:

$$
y = -x^2 + 6x - 8
$$
---

## 16. Equations of planes in space

#### 1. The plane passes through points A(1,2,3), B(3,4,5), and C(2,1,4). Find the equation of the plane.

![alt text](<Screenshot 2024-12-19 at 7.31.51 PM.png>)

#### 2. The plane passes through point A(1,2,3) and is parallel to the plane 2x+3y+4z=5. Find the equation of the plane.

The plane we are looking for must be parallel to the given plane 2x+3y+4z=5.

A parallel plane will have the same normal vector n=(2,3,4).


The general equation of a plane with normal vector (a,b,c) is ax+by+cz=d.


The plane passes through the point A(1,2,3).

Substituting x=1,y=2,z=3 into 2x+3y+4z=d, we solve for 2(1)+3(2)+4(3)=d⟹d=2+6+12=20.


Therefore, the equation of the plane is:
2x+3y+4z=20.

![alt text](<Screenshot 2024-12-19 at 7.39.37 PM.png>)

#### 3. The plane passes through point A(1,2,3) and is perpendicular to the normal vector n = [2,3,4]. Find the equation of the plane.


The plane passes through the point $A(1, 2, 3)$ .
The normal vector to the plane is $\mathbf{n} = [2, 3, 4]$ .

The general equation of a plane with a normal vector $\mathbf{n} = [a, b, c]$ is:

   $$
   a(x - x_0) + b(y - y_0) + c(z - z_0) = 0,
   $$

where $(x_0, y_0, z_0)$ is a point on the plane.

Substitute Values:
   - Normal vector: $a = 2, b = 3, c = 4$.
   - Point $A(1, 2, 3) $ : $ x_0 = 1, y_0 = 2, z_0 = 3$ .

   Substituting into the equation:

   $$
   2(x - 1) + 3(y - 2) + 4(z - 3) = 0.
   $$

Simplify the Equation:

Expand and simplify:

   $$
   2x - 2 + 3y - 6 + 4z - 12 = 0,
   $$

   $$
   2x + 3y + 4z - 20 = 0.
   $$

   The equation of the plane is:

   $$
   2x + 3y + 4z = 20.
   $$

![alt text](<Screenshot 2024-12-19 at 7.46.36 PM.png>)

#### 4. We have two planes 2x+3y+4z=5 and 3x+4y+2z=6. Find the line of intersection of these planes.

Solving the Two Plane Equations Simultaneously

Eliminate One Variable:
   - To eliminate $z$, align the coefficients of $z$ by multiplying:
   - Multiply Plane 1 by $2$ :

$$
4x + 6y + 8z = 10
$$

- Multiply Plane 2 by $4$:

$$
12x + 16y + 8z = 24
$$

   - Subtract Plane 1 from Plane 2:

$$
(12x + 16y + 8z) - (4x + 6y + 8z) = 24 - 10
$$

$$
8x + 10y = 14
$$

   - Simplify:

$$
4x + 5y = 7 \quad \text{(Equation 3)}
$$

Solve for $x$ in Terms of $y$ :

   - From Equation 3:

$$
x = \frac{7 - 5y}{4}
$$

Express $x$ and $y$ in Terms of $z$ :
   - Substitute $x = \frac{7 - 5y}{4}$ into Plane 1:

$$
2\left(\frac{7 - 5y}{4}\right) + 3y + 4z = 5
$$

$$
\frac{14 - 10y}{4} + 3y + 4z = 5
$$

   - Simplify:

$$
\frac{14 - 10y + 12y}{4} + 4z = 5
$$

$$
\frac{14 + 2y}{4} + 4z = 5
$$

$$
\frac{7 + y}{2} + 4z = 5
$$

   - Solve for $y$ in terms of $z$ :

$$
\frac{7 + y}{2} = 5 - 4z
$$

$$
y = 2(5 - 4z) - 7
$$

$$
y = 10 - 8z - 7
$$

$$
y = 3 - 8z
$$

   - Substitute $y = 3 - 8z$ into $x = \frac{7 - 5y}{4}$ :

$$
x = \frac{7 - 5(3 - 8z)}{4}
$$

$$
x = \frac{7 - 15 + 40z}{4}
$$

$$
x = \frac{-8 + 40z}{4}
$$

$$
x = -2 + 10z
$$

Parametric Form of the Line:
   - Let $z = t$ (the parameter). Then:

$$
x = -2 + 10t, \quad y = 3 - 8t, \quad z = t
$$

   - The parametric equation of the line is:

$$
\mathbf{r}(t) = (-2, 3, 0) + t(10, -8, 1)
$$

![alt text](<Screenshot 2024-12-19 at 8.04.06 PM.png>)

#### 5. Write the equation of the plane passing through point A(1,2,3) and parallel to vectors v1=[1,0,1] and v2=[0,1,-1].

1. The plane passes through the point $A(1, 2, 3)$ and is parallel to the vectors:

$$
\mathbf{v}_1 = [1, 0, 1], \quad \mathbf{v}_2 = [0, 1, -1]
$$

2. The normal vector $\mathbf{n}$ of the plane is perpendicular to both $\mathbf{v}_1$ and $\mathbf{v}_2$, which we find using the cross product:

$$
\mathbf{n} = \mathbf{v}_1 \times \mathbf{v}_2
$$

   Compute the determinant:

$$
   \mathbf{n} = \begin{vmatrix}
   \mathbf{i} & \mathbf{j} & \mathbf{k} \\
   1 & 0 & 1 \\
   0 & 1 & -1
   \end{vmatrix}
   = \mathbf{i}(0 \cdot -1 - 1 \cdot 1) - \mathbf{j}(1 \cdot -1 - 0 \cdot 0) + \mathbf{k}(1 \cdot 1 - 0 \cdot 0)
$$

   Simplify:

$$
   \mathbf{n} = \mathbf{i}(-1) - \mathbf{j}(-1) + \mathbf{k}(1)
$$

$$
   \mathbf{n} = [-1, 1, 1]
$$

   The normal vector is:

$$
   \mathbf{n} = [-1, 1, 1]
$$

---

Writing the Equation of the Plane.

The general equation of a plane is:

$$
n_1(x - x_1) + n_2(y - y_1) + n_3(z - z_1) = 0
$$

where:
- $(x_1, y_1, z_1)$ is a point on the plane,
- $\mathbf{n} = [n_1, n_2, n_3]$ is the normal vector.

Substitute:
- Point $A(1, 2, 3)$,
- Normal vector $\mathbf{n} = [-1, 1, 1]$,

$$
-1(x - 1) + 1(y - 2) + 1(z - 3) = 0
$$

Simplify:

$$
-x + 1 + y - 2 + z - 3 = 0
$$

$$
-x + y + z - 4 = 0
$$

Rewriting:

$$
x - y - z + 4 = 0
$$

Thus, the equation of the plane is:

$$
x - y - z + 4 = 0.
$$

![alt text](<Screenshot 2024-12-19 at 8.12.36 PM.png>)

#### 6. We have the plane 2x+3y+4z=5. Find an example of a plane parallel and perpendicular to it.

Plane Parallel to $2x + 3y + 4z = 5$
- Planes parallel to $2x + 3y + 4z = 5$ will have the same normal vector $\mathbf{n} = [2, 3, 4]$.
- The equation of a parallel plane is:

$$
2x + 3y + 4z = D
$$

  where $D$ is any constant. For example:

$$
2x + 3y + 4z = 10
$$

  This plane is parallel to the original plane.

Plane Perpendicular to $2x + 3y + 4z = 5$
- A perpendicular plane will have a normal vector that is orthogonal to the normal vector $\mathbf{n} = [2, 3, 4]$ of the original plane.
- To find a plane perpendicular to the original, we can choose any vector $\mathbf{n'}$ that satisfies $\mathbf{n} \cdot \mathbf{n'} = 0$.
- For example, choose $\mathbf{n'} = [1, -2, 1]$. The dot product $\mathbf{n} \cdot \mathbf{n'} = 2(1) + 3(-2) + 4(1) = 0 $ , so they are perpendicular.
- The equation of the perpendicular plane is:

  $$
  x - 2y + z = D
  $$

  Example of a perpendicular plane:

  $$
  x - 2y + z = 4
  $$

![alt text](<Screenshot 2024-12-19 at 8.19.05 PM.png>)

#### 7. We have the plane 2x+3y+4z=5 and point A(1,2,3) .Find the distance from point A to this plane.

Distance Formula:
The distance from a point $(x_1, y_1, z_1)$ to a plane $Ax + By + Cz + D = 0$ is given by:

$$
D = \frac{|Ax_1 + By_1 + Cz_1 + D|}{\sqrt{A^2 + B^2 + C^2}}
$$

Applying the Formula:

For the plane $2x + 3y + 4z = 5$, rewrite as $2x + 3y + 4z - 5 = 0$, so $A = 2$, $B = 3$, $C = 4$, and $D = -5$.

For point $A(1, 2, 3)$, $x_1 = 1$, $y_1 = 2$, $z_1 = 3$ .

Substitute into the formula:

$$
D = \frac{|2(1) + 3(2) + 4(3) - 5|}{\sqrt{2^2 + 3^2 + 4^2}} = \frac{|15|}{\sqrt{29}} = \frac{15}{\sqrt{29}}
$$

The distance is $\frac{15}{\sqrt{29}}$ .

![alt text](<Screenshot 2024-12-19 at 8.26.10 PM.png>)

#### 8. The plane intersects the coordinate axes at points A(2,0,0), B(0,3,0) and C(0,0,4). Find the equation of the plane.

Equation of the Plane:
The equation of a plane passing through points $A$, $B$, and $C$ can be written as:

$$
\frac{x}{a} + \frac{y}{b} + \frac{z}{c} = 1
$$

where $a$, $b$, and $c$) are the intercepts on the $x$-, $y$-, and $z$-axes, respectively.

From the given points:
- $a = 2$
- $b = 3$
- $c = 4$

Thus, the equation of the plane is:

$$
\frac{x}{2} + \frac{y}{3} + \frac{z}{4} = 1
$$

Standard Form:
Multiplying through by 12:

$$
6x + 4y + 3z = 12
$$

Final Answer:
The equation of the plane is:

$$
6x + 4y + 3z = 12
$$

![alt text](<Screenshot 2024-12-19 at 8.44.53 PM.png>)

#### 9. Calculate the angle between the plane x+y+z=1 and the plane x=0 (i.e., the yz plane).


Normal Vectors:
- Normal vector of Plane 1: $\mathbf{n_1} = [1, 1, 1]$
- Normal vector of Plane 2: $\mathbf{n_2} = [1, 0, 0]$

Formula for Angle Between Planes:

$$
\cos \theta = \frac{|\mathbf{n_1} \cdot \mathbf{n_2}|}{|\mathbf{n_1}| |\mathbf{n_2}|}
$$

Calculation:
1. Dot product: $\mathbf{n_1} \cdot \mathbf{n_2} = 1$
2. Magnitudes: $|\mathbf{n_1}| = \sqrt{3}, |\mathbf{n_2}| = 1$
3. Cosine of the angle: 

$$
\cos \theta = \frac{1}{\sqrt{3}}
$$

4. Angle:

$$
\theta = \cos^{-1} \left( \frac{1}{\sqrt{3}} \right) \approx 54.74^\circ
$$

Final Answer:
The angle between the planes is approximately $54.74^\circ$.

![alt text](<Screenshot 2024-12-19 at 8.47.30 PM.png>)

#### 10. Find the vector perpendicular to the plane x+y+z=1.

Perpendicular Vector:
The vector perpendicular to the plane is the normal vector, which is given by the coefficients of $x$, $y$, and $z$ in the plane equation.

Thus, the normal vector is:

$$
\mathbf{n} = [1, 1, 1]
$$

Final Answer:
The vector perpendicular to the plane $x + y + z = 1$ is $\mathbf{n} = [1, 1, 1]$.

![alt text](<Screenshot 2024-12-19 at 8.50.43 PM.png>)

## 17. Equations of second-order surfaces

#### 1. Write the equation of a sphere with center at point P=(1,2,3) and radius r=3.

Equation of the Sphere:
The general equation of a sphere is:

$$
(x - x_0)^2 + (y - y_0)^2 + (z - z_0)^2 = r^2
$$

Substitute the values:

$$
(x - 1)^2 + (y - 2)^2 + (z - 3)^2 = 9
$$

Final Answer:
The equation of the sphere is:

$$
(x - 1)^2 + (y - 2)^2 + (z - 3)^2 = 9
$$

![alt text](<Screenshot 2024-12-19 at 8.54.09 PM.png>)

#### 2. Do the spheres with equations $x^2 + y^2 + z^2 = 1$ and $x^2 + y^2 + z^2 = 2$ have any common points?

Analysis:
Both spheres have the same center at the origin $(0, 0, 0)$, but different radii:
- Radius of Sphere 1: $r_1 = 1$
- Radius of Sphere 2: $r_2 = \sqrt{2} \approx 1.414$

Since their radii are different, the spheres **do not intersect**.

Final Answer:
The spheres do not have any common points.

![alt text](<Screenshot 2024-12-19 at 8.58.13 PM.png>)

#### 3. What curve in space is formed by the intersection of the sphere $x^2 + y^2 + z^2 = 1$ with the sphere $(x - 1)^2 + y^2 + z^2 = 1$? Find the equation of this curve.

Subtract the second sphere's equation from the first:

$$
x^2 + y^2 + z^2 - (x^2 - 2x + 1 + y^2 + z^2) = 0
$$

This simplifies to:

$$
-2x + 1 = 0 \quad \Rightarrow \quad x = \frac{1}{2}
$$

Substitute $x = \frac{1}{2}$ into the first sphere's equation:


$$
\left( \frac{1}{2} \right)^2 + y^2 + z^2 = 1 \quad \Rightarrow \quad y^2 + z^2 = \frac{3}{4}
$$

Final Answer:
The equation of the curve is:

$$
x = \frac{1}{2}, \quad y^2 + z^2 = \frac{3}{4}
$$

This represents a circle with radius $\frac{\sqrt{3}}{2}$ in the plane $x = \frac{1}{2}$.

![alt text](<Screenshot 2024-12-19 at 9.03.08 PM.png>)

#### 4. Write the equation of the tangent plane to the paraboloid $z = (x - 1)^2 + y^2 + 1$ at point $P(1, 0, 1)$.

Compute Partial Derivatives

$$
f_x = 2(x - 1), \quad f_y = 2y
$$

Evaluate at $P(1, 0, 1)$

$$
f_x(1, 0) = 0, \quad f_y(1, 0) = 0
$$

The equation of the tangent plane is:

$$
z = 1
$$

Final Answer:
The equation of the tangent plane is $z = 1$.

![alt text](<Screenshot 2024-12-19 at 9.05.54 PM.png>)

## 18. Functions

#### 1. Draw in a single Geogebra notebook the following functions: 

- $f(x) = x^2$
- $g(x) = x$
- $h(x) = \frac{1}{x}$
- $j(x) = \sin(x)$

Find value of all the above functions at $x = 2$.

- $f(2) = 2^2 = 4$
- $g(2) = 2$
- $h(2) = \frac{1}{2} = 0.5$
- $j(2) = \sin(2) \approx 0.909$

Final Values at $ x = 2$:
- $f(2) = 4$
- $g(2) = 2$
- $h(2) = 0.5$
- $j(2) \approx 0.909$

![alt text](<Screenshot 2024-12-19 at 9.11.26 PM.png>)

#### 2. Let $f(x) = 3x - 1$ and $g(x) = x$. Find: f(g(x)), g(f(x)), f(f(x)), g(g(x)).Visualize functions in a single Geogebra notebook.

Computations:

1. $f(g(x)) = f(x) = 3x - 1$
2. $g(f(x)) = g(3x - 1) = 3x - 1$
3. $f(f(x)) = f(3x - 1) = 9x - 4$
4. $g(g(x)) = g(x) = x$

Final Answers:
- $f(g(x)) = 3x - 1$
- $g(f(x)) = 3x - 1$
- $f(f(x)) = 9x - 4$
- $g(g(x)) = x$

![alt text](<Screenshot 2024-12-19 at 9.16.36 PM.png>)

#### 3. Let $f(x) = e^x$ and $g(x) = \ln(x)$ . Check: f(g(x)) and g(f(x)).What do you notice?

Computations:

1. $f(g(x)) = e^{\ln(x)} = x$
2. $g(f(x)) = \ln(e^x) = x$

Conclusion:
Both $f(g(x))$ and $g(f(x))$ equal $x$, demonstrating that $e^x$ and $\ln(x)$ are inverse functions of each other.

![alt text](<Screenshot 2024-12-19 at 9.20.13 PM.png>)

#### 4. We have function $f = \{(1, 7), (2, 9), (3, 11)\}$. Give inverse function $f^{-1}$.

To find the inverse function $f^{-1}$, we swap the coordinates in each pair:
- $(1, 7)$ becomes $(7, 1)$
- $(2, 9)$ becomes $(9, 2)$
- $(3, 11)$ becomes $(11, 3)$

Thus, the inverse function is:

$$
f^{-1} = \{(7, 1), (9, 2), (11, 3)\}
$$

![alt text](<Screenshot 2024-12-19 at 9.29.15 PM.png>)

#### 5. We have function $f = \{(1, 7), (2, 7), (3, 11)\}$. Give inverse function.

Checking for Inversibility:
For a function to have an inverse, it must be one-to-one. In this case:
- Both $(1, 7)$ and $(2, 7)$ have the same output $7$, so the function is not one-to-one.

Conclusion:
Since the function is not one-to-one, it does not have an inverse.

#### 6. We have function $f(x) = x - 1$.Give inverse function. Show both functions on the same Geogebra notebook.

To find the inverse, we:
1. Swap $x$ and $y$:
   
$$
   x = y - 1
$$

2. Solve for $y$:
   
   
$$
   y = x + 1
$$

Thus, the inverse function is:

$$
f^{-1}(x) = x + 1
$$

##  19. Limits of Sequences

## Problem 1: 

$$
 \lim_{n \to \infty} \frac{n^2 + 3n}{2n^2 - 2n} 
 $$

### Step 1: Factor out the highest power of n
$$
\frac{n^2 + 3n}{2n^2 - 2n} = \frac{n^2(1 + \frac{3}{n})}{n^2(2 - \frac{2}{n})}.
$$

### Step 2: Simplify the fraction

$$
\frac{n^2(1 + \frac{3}{n})}{n^2(2 - \frac{2}{n})} = \frac{1 + \frac{3}{n}}{2 - \frac{2}{n}}.
$$

### Step 3: 

$$
\text{As } n \to \infty, \frac{3}{n} \to 0 \text{ and } \frac{2}{n} \to 0:
$$

$$
\lim_{n \to \infty} \frac{1 + \frac{3}{n}}{2 - \frac{2}{n}} = \frac{1 + 0}{2 - 0} = \frac{1}{2}.
$$

**Final Answer:**

$$
\frac{1}{2}.
$$


---

## Problem 2: 

$$
\lim_{n \to \infty} \frac{(2n+3)^3}{n^3-1} 
$$

### Step 1: Expand the numerator

The numerator $ (2n + 3)^3 $ expands as:

$$
(a + b)^3 = a^3 + 3a^2b + 3ab^2 + b^3

(2n + 3)^3 = 8n^3 + 36n^2 + 54n + 27.
$$

Thus, the fraction becomes:
$$
\frac{(2n+3)^3}{n^3-1} = \frac{8n^3 + 36n^2 + 54n + 27}{n^3 - 1}.
$$

### Step 2: Factor out the highest power of $ n $

Divide through by $ n^3 $:
$$
\frac{8n^3 + 36n^2 + 54n + 27}{n^3 - 1} = \frac{n^3 \left( 8 + \frac{36}{n} + \frac{54}{n^2} + \frac{27}{n^3} \right)}{n^3 \left( 1 - \frac{1}{n^3} \right)}.
$$

### Step 3: Simplify the fraction

$$
\frac{8 + \frac{36}{n} + \frac{54}{n^2} + \frac{27}{n^3}}{1 - \frac{1}{n^3}}.
$$

### Step 4: 

$$
\text{As} \ n \to \infty \, \\frac{36}{n} \to 0 \, \\frac{54}{n^2} \to 0 \, \ \frac{27}{n^3} \to 0 \, and \ \frac{1}{n^3} \to 0 \:
$$

$$
\lim_{n \to \infty} \frac{8 + \frac{36}{n} + \frac{54}{n^2} + \frac{27}{n^3}}{1 - \frac{1}{n^3}} = \frac{8 + 0 + 0 + 0}{1 - 0} = 8.
$$

**Final Answer:**
$$
\lim_{n \to \infty} \frac{(2n+3)^3}{n^3-1} = 8.
$$
---

## 2 . Proof Using the Squeeze Theorem

We are tasked with proving that:

$$
\lim_{n \to \infty} \frac{\sin(n)}{n} = 0
$$

### Step 1:

$$
\text {Analyze the bounds of} \ \sin(n) \
$$

The sine function is bounded for all real numbers $ n $, so:

$$
-1 \leq \sin(n) \leq 1
$$

### Step 2: Divide the inequality by $ n $ (for $ n > 0 $)

Since $ n $ is positive as $ n \to \infty $, we can divide the inequality by $ n $:

$$
\frac{-1}{n} \leq \frac{\sin(n)}{n} \leq \frac{1}{n}
$$

### Step 3: 

$$
\text {Take the limit of the bounds as} \ n \to \infty 
$$

Now, we compute the limits of the bounds:

 The limit of $ \frac{-1}{n} $ as $ n \to \infty $ is $0 $:

$$
\lim_{n \to \infty} \frac{-1}{n} = 0
$$

The limit of $ \frac{1}{n} $ as $ n \to \infty $ is also $ 0 $:

$$
\lim_{n \to \infty} \frac{1}{n} = 0
$$

### Step 4: Apply the Squeeze Theorem

Since we have:

$$
\frac{-1}{n} \leq \frac{\sin(n)}{n} \leq \frac{1}{n}
$$

and both the lower and upper bounds approach 0 as $ n \to \infty $, by the **Squeeze Theorem**, we conclude that:

$$
\lim_{n \to \infty} \frac{\sin(n)}{n} = 0
$$

### Final Answer:

$$
\lim_{n \to \infty} \frac{\sin(n)}{n} = 0
$$
---

## 3. Limit of the Sequence


### Step 1: Sequence Setup

We are given the sequence:

$$
a_n = \left( 1 + \frac{1}{n} \right)^n
$$

### Step 2: Recognize the Limit

This is a standard limit that is used to define the number $ e $ (Euler's number). The limit is known to be:

$$
\lim_{n \to \infty} \left( 1 + \frac{1}{n} \right)^n = e
$$

### Step 3: Conclusion

$$
\text {Therefore, the limit of the sequence} \ a_n \ as \ n \to \infty \ is:
$$ 
$$
\lim_{n \to \infty} \left( 1 + \frac{1}{n} \right)^n = e
$$
---

## 20 . Limit of the Real Function

## 1.

We are tasked with computing the limit:

$$
\lim_{x \to \infty} \frac{x^3 + 2x^2}{x^4 - 3x^3}
$$

### Step 1: Analyze the Degrees of the Polynomial

- The numerator is $ x^3 + 2x^2 $, and the highest power of $ x $ in the numerator is $ x^3 $.
- The denominator is $ x^4 - 3x^3 $, and the highest power of $ x $ in the denominator is $ x^4 $.

### Step 2: Simplify by Dividing by the Highest Power of $ x $

Since the highest degree in the denominator is $ x^4 $, we divide both the numerator and denominator by $ x^4 $ to simplify:

$$
\frac{x^3 + 2x^2}{x^4 - 3x^3} = \frac{\frac{x^3}{x^4} + \frac{2x^2}{x^4}}{\frac{x^4}{x^4} - \frac{3x^3}{x^4}} = \frac{\frac{1}{x} + \frac{2}{x^2}}{1 - \frac{3}{x}}
$$

### Step 3:

$$
\text {As} \ x \to \infty \:
$$
$$
\ \frac{1}{x} \to 0 \
\ \frac{2}{x^2} \to 0 \
\ \frac{3}{x} \to 0 \
$$
Thus, the expression simplifies to:

$$
\frac{0 + 0}{1 - 0} = 0
$$

### Final Answer:

$$
\lim_{x \to \infty} \frac{x^3 + 2x^2}{x^4 - 3x^3} = 0
$$

---

## 2. We are tasked with finding the limit:

$$
\lim_{x \to 0} \frac{\sin(3x)}{2x+1}.
$$

### Step 1: Evaluate the limit of the numerator as $ x \to 0 $

$$
\text {The numerator is} \ \sin(3x) \ . \text{We know that}:
$$
$$
\lim_{x \to 0} \sin(3x) = \sin(0) = 0.
$$

### Step 2: Evaluate the limit of the denominator as $ x \to 0 $

The denominator is $ 2x + 1 $. Substituting $ x = 0 $:

$$
2(0) + 1 = 1.
$$

### Step 3: Combine the results

Now we can compute the overall limit:

$$
\lim_{x \to 0} \frac{\sin(3x)}{2x+1} = \frac{\lim_{x \to 0} \sin(3x)}{\lim_{x \to 0} (2x+1)} = \frac{0}{1} = 0.
$$

Thus, the value of the limit is:

$$
\boxed{0}.
$$

 ## 3.We are tasked with finding the asymptotes of the functions:

### 1. 

$$
\ f(x) = \frac{x^2 - 1}{x^2 + 1} \
$$

#### Step 1: Horizontal Asymptotes

$$
\text{As} \ x \to \infty \ 
$$
$$
\lim_{x \to \infty} f(x) = \lim_{x \to \infty} \frac{x^2 - 1}{x^2 + 1} = \frac{1}{1} = 1.
$$

Thus, there is a horizontal asymptote at $ y = 1 $.

#### Step 2: Vertical Asymptotes

Vertical asymptotes occur when the denominator equals zero and the numerator is non-zero at that point. The denominator is $ x^2 + 1 $, which is never zero for any real value of $ x $ (since $ x^2 + 1 > 0 $ for all $ x $). Therefore, there are no vertical asymptotes.

### Asymptotes for $ f(x) $:

- Horizontal asymptote at $ y = 1 $.
- No vertical asymptotes.

### 2. 

$$
\ g(x) = \frac{\sin(x)}{x^2 + 1} \
$$

#### Step 1: Horizontal Asymptotes

To find horizontal asymptotes, we examine the behavior of $ g(x) $ as $ x \to \infty $ and $ x \to -\infty $.

- As $ x \to \infty $ or $ x \to -\infty $, the denominator $ x^2 + 1 $ grows much faster than the numerator $ \sin(x) $, which is bounded between -1 and 1. Hence, we have:

$$
\lim_{x \to \infty} g(x) = \lim_{x \to \infty} \frac{\sin(x)}{x^2 + 1} = 0.
$$

Thus, there is a horizontal asymptote at $ y = 0 $.

#### Step 2: Vertical Asymptotes

Vertical asymptotes occur when the denominator equals zero and the numerator is non-zero at that point. The denominator is $ x^2 + 1 $, which is never zero for any real value of $ x $. Therefore, there are no vertical asymptotes.

### Asymptotes for $ g(x) $:

- Horizontal asymptote at $ y = 0 $.
- No vertical asymptotes.

 
=======

### Step 1: Factor out the highest power of $ n $

$$
\frac{n^2 + 3n}{2n^2 - 2n} = \frac{n^2(1 + \frac{3}{n})}{n^2(2 - \frac{2}{n})}.
$$

### Step 2: Simplify the fraction

$$
\frac{n^2(1 + \frac{3}{n})}{n^2(2 - \frac{2}{n})} = \frac{1 + \frac{3}{n}}{2 - \frac{2}{n}}.
$$

### Step 3: 

$$
\text{As } n \to \infty, \frac{3}{n} \to 0 \text{ and } \frac{2}{n} \to 0:
$$

$$
\lim_{n \to \infty} \frac{1 + \frac{3}{n}}{2 - \frac{2}{n}} = \frac{1 + 0}{2 - 0} = \frac{1}{2}.
$$

**Final Answer:**
$$
\lim_{n \to \infty} \frac{n^2 + 3n}{2n^2 - 2n} = \frac{1}{2}.
$$

---

## Problem 2: 

$$
\lim_{n \to \infty} \frac{(2n+3)^3}{n^3-1} 
$$

### Step 1: Expand the numerator

The numerator $ (2n + 3)^3 $ expands as: 
$$
(a + b)^3 = a^3 + 3a^2b + 3ab^2 + b^3

(2n + 3)^3 = 8n^3 + 36n^2 + 54n + 27.
$$

Thus, the fraction becomes:
$$
\frac{(2n+3)^3}{n^3-1} = \frac{8n^3 + 36n^2 + 54n + 27}{n^3 - 1}.
$$

### Step 2: Factor out the highest power of $ n $

Divide through by $ n^3 $:
$$
\frac{8n^3 + 36n^2 + 54n + 27}{n^3 - 1} = \frac{n^3 \left( 8 + \frac{36}{n} + \frac{54}{n^2} + \frac{27}{n^3} \right)}{n^3 \left( 1 - \frac{1}{n^3} \right)}.
$$

### Step 3: Simplify the fraction

$$
\frac{8 + \frac{36}{n} + \frac{54}{n^2} + \frac{27}{n^3}}{1 - \frac{1}{n^3}}.
$$

### Step 4: 

$$
\text{As} \ n \to \infty \, \\frac{36}{n} \to 0 \, \\frac{54}{n^2} \to 0 \, \ \frac{27}{n^3} \to 0 \, and \ \frac{1}{n^3} \to 0 \:
$$

$$
\lim_{n \to \infty} \frac{8 + \frac{36}{n} + \frac{54}{n^2} + \frac{27}{n^3}}{1 - \frac{1}{n^3}} = \frac{8 + 0 + 0 + 0}{1 - 0} = 8.
$$

**Final Answer:**
$$
\lim_{n \to \infty} \frac{(2n+3)^3}{n^3-1} = 8.
$$
---

## 2 . Proof Using the Squeeze Theorem

We are tasked with proving that:

$$
\lim_{n \to \infty} \frac{\sin(n)}{n} = 0
$$

### Step 1:

$$
\text {Analyze the bounds of} \ \sin(n) \
$$

The sine function is bounded for all real numbers $ n $, so:

$$
-1 \leq \sin(n) \leq 1
$$

### Step 2: Divide the inequality by $ n $ (for $ n > 0 $)

Since $ n $ is positive as $ n \to \infty $, we can divide the inequality by $ n $:

$$
\frac{-1}{n} \leq \frac{\sin(n)}{n} \leq \frac{1}{n}
$$

### Step 3: 

$$
\text {Take the limit of the bounds as} \ n \to \infty 
$$

Now, we compute the limits of the bounds:

- The limit of $ \frac{-1}{n} $ as $ n \to \infty $ is $ 0 $:

$$
\lim_{n \to \infty} \frac{-1}{n} = 0
$$

- The limit of $ \frac{1}{n} $ as $ n \to \infty $ is also $ 0 $:

$$
\lim_{n \to \infty} \frac{1}{n} = 0
$$

### Step 4: Apply the Squeeze Theorem

Since we have:

$$
\frac{-1}{n} \leq \frac{\sin(n)}{n} \leq \frac{1}{n}
$$

and both the lower and upper bounds approach 0 as $ n \to \infty $, by the **Squeeze Theorem**, we conclude that:

$$
\lim_{n \to \infty} \frac{\sin(n)}{n} = 0
$$

### Final Answer:

$$
\lim_{n \to \infty} \frac{\sin(n)}{n} = 0
$$
---

# 3. Limit of the Sequence


### Step 1: Sequence Setup

We are given the sequence:

$$
a_n = \left( 1 + \frac{1}{n} \right)^n
$$

### Step 2: Recognize the Limit

This is a standard limit that is used to define the number $ e $ (Euler's number). The limit is known to be:

$$
\lim_{n \to \infty} \left( 1 + \frac{1}{n} \right)^n = e
$$

### Step 3: Conclusion

$$
\text {Therefore, the limit of the sequence} \ a_n \ as \ n \to \infty \ is:
$$ 
$$
\lim_{n \to \infty} \left( 1 + \frac{1}{n} \right)^n = e
$$
---

## 20 . Limit of the Real Function

## 1.

We are tasked with computing the limit:

$$
\lim_{x \to \infty} \frac{x^3 + 2x^2}{x^4 - 3x^3}
$$

### Step 1: Analyze the Degrees of the Polynomial

- The numerator is $ x^3 + 2x^2 $, and the highest power of $ x $ in the numerator is $ x^3 $.
- The denominator is $ x^4 - 3x^3 $, and the highest power of $ x $ in the denominator is $ x^4 $.

### Step 2: Simplify by Dividing by the Highest Power of $ x $

Since the highest degree in the denominator is $ x^4 $, we divide both the numerator and denominator by $ x^4 $ to simplify:

$$
\frac{x^3 + 2x^2}{x^4 - 3x^3} = \frac{\frac{x^3}{x^4} + \frac{2x^2}{x^4}}{\frac{x^4}{x^4} - \frac{3x^3}{x^4}} = \frac{\frac{1}{x} + \frac{2}{x^2}}{1 - \frac{3}{x}}
$$

### Step 3:

$$
\text {As} \ x \to \infty \:
$$
$$
\ \frac{1}{x} \to 0 \
\ \frac{2}{x^2} \to 0 \
\ \frac{3}{x} \to 0 \
$$
Thus, the expression simplifies to:

$$
\frac{0 + 0}{1 - 0} = 0
$$

### Final Answer:

$$
\lim_{x \to \infty} \frac{x^3 + 2x^2}{x^4 - 3x^3} = 0
$$

---

## 2. We are tasked with finding the limit:

$$
\lim_{x \to 0} \frac{\sin(3x)}{2x+1}.
$$

### Step 1: Evaluate the limit of the numerator as $ x \to 0 $

$$
\text {The numerator is} \ \sin(3x) \ . \text{We know that}:
$$
$$
\lim_{x \to 0} \sin(3x) = \sin(0) = 0.
$$

###Step 2: Evaluate the limit of the denominator as x → 0. The denominator is 2x + 1. Substituting x = 0:


$$
2(0) + 1 = 1.
$$

### Step 3: Combine the results

Now we can compute the overall limit:

$$
\lim_{x \to 0} \frac{\sin(3x)}{2x+1} = \frac{\lim_{x \to 0} \sin(3x)}{\lim_{x \to 0} (2x+1)} = \frac{0}{1} = 0.
$$

Thus, the value of the limit is:

$$
\boxed{0}.
$$

 ## 3.We are tasked with finding the asymptotes of the functions:

### 1. 

$$
\ f(x) = \frac{x^2 - 1}{x^2 + 1} \
$$

#### Step 1: Horizontal Asymptotes

$$
\text{As} \ x \to \infty \ 
$$
$$
\lim_{x \to \infty} f(x) = \lim_{x \to \infty} \frac{x^2 - 1}{x^2 + 1} = \frac{1}{1} = 1.
$$

Thus, there is a horizontal asymptote at $ y = 1 $.

#### Step 2: Vertical Asymptotes

Vertical asymptotes occur when the denominator equals zero and the numerator is non-zero at that point. The denominator is $ x^2 + 1 $, which is never zero for any real value of $ x $ (since $ x^2 + 1 > 0 $ for all $ x $). Therefore, there are no vertical asymptotes.

### Asymptotes for $ f(x) $:

- Horizontal asymptote at $ y = 1 $.
- No vertical asymptotes.

### 2. 

$$
\ g(x) = \frac{\sin(x)}{x^2 + 1} \
$$

#### Step 1: Horizontal Asymptotes

To find horizontal asymptotes, we examine the behavior of $g(x)$ as $x \to \infty$ and $x \to -\infty$.

As $x \to \infty$ or $x \to -\infty$, the denominator $x^2 + 1$ grows much faster than the numerator $\sin(x)$, which is bounded between $-1$ and $1$. Hence, we have:


$$
\lim_{x \to \infty} g(x) = \lim_{x \to \infty} \frac{\sin(x)}{x^2 + 1} = 0,
$$

and similarly,

$$
\lim_{x \to -\infty} g(x) = \lim_{x \to -\infty} \frac{\sin(x)}{x^2 + 1} = 0.
$$

Therefore, the horizontal asymptote is:

$$
y = 0.
$$


$$
\lim_{x \to \infty} g(x) = \lim_{x \to \infty} \frac{\sin(x)}{x^2 + 1} = 0.
$$

Thus, there is a horizontal asymptote at $ y = 0 $.

#### Step 2: Vertical Asymptotes

Vertical asymptotes occur when the denominator equals zero and the numerator is non-zero at that point. The denominator is $ x^2 + 1 $, which is never zero for any real value of $ x $. Therefore, there are no vertical asymptotes.

### Asymptotes for $ g(x) $:

- Horizontal asymptote at $ y = 0 $.
- No vertical asymptotes.

 