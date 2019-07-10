---
layout: page
mathjax: true

---

<br>

### Table of Contents
- [Vector](#vector)
- [Dot products](#dot-products)
- [Cross products](#cross-products)
- [Matrix](#matrix)
- [Glossary](#glossary)


### Vector
  * Imagine we have a two dimensional space composed of x and y axis, and their intersection called origin (0).
  * $\begin{bmatrix}1 \\\2 \end{bmatrix}$ : The coordinate of a vector is a pair of numbers which gives instructions to tell the vector how to get from the origin of the vector to the tip of the vector.
  * The first number tells you how far to walk on the x-axis
  * After that, the second number tells you how far to walk parallel to the y-axis
  * To differentiate vectors from points, the convention is to write these two numbers vertically in a square bracket.
  * Every pair of numbers is associated with one and only one vector, vice versa
  * [Vectors, what even are they? 3'- 4'](https://www.youtube.com/watch?v=fNk_zzaMoSs&list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab)

<br>

### Dot products
 * Two vectors of the same dimension
   * $\vec{v}$ =  $\begin{bmatrix}1 \\\2 \end{bmatrix}$

   * $\vec{w}$  = $\begin{bmatrix}3 \\\4 \end{bmatrix}$
 * Order: doesn't matter
 * Numerically
   * Pair the coordinates of multiply them together and add the result
   * $\begin{bmatrix}1 \\\2 \end{bmatrix}$ $\cdot$  $\begin{bmatrix}3 \\\4 \end{bmatrix}$ =  1 $\cdot$  3+ 2 $\cdot$ 4= 11

 * Geometrically
   * Project $\vec{w}$ onto the line passing through the origin on the tip of $\vec{v}$  
   * $\vec{v}$ $\cdot$ $\vec{w}$  =  (length of projected  $\vec{w}$) $\cdot$ (length of projected  $\vec{v}$)
   * Dot product vs Directions
     *  $\vec{v}$ $\cdot$ $\vec{w}$> 0: vectors are pointing to similar directions
     *  $\vec{v}$ $\cdot$ $\vec{w}$< 0: vectors are pointing to opposing direction
     * $\vec{v}$ $\cdot$ $\vec{w}$ = 0: vectors are perpendicular

 * Duality: natural-but-surprising correspondence
   * Matrix vector product:  
     [$u_x$ $u_y$] $\begin{bmatrix}x \\\y \end{bmatrix}$ = $u_x$ $\cdot$ x + $u_y$ $\cdot$ y
   * Dot product:   
     $\begin{bmatrix}u_x \\\u_y \end{bmatrix}$ $\cdot$ $\begin{bmatrix}x \\\y \end{bmatrix}$ = $u_x$ $\cdot$ x + $u_y$ $\cdot$ y

![dot product projection](../src/image/dotproduct.png)  

[Screenshot at 2:19 in video](https://www.youtube.com/watch?v=LyGKycYT2v0&list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab&index=9)
<br>

### Cross products
 * The standard basis vectors $\vec{i}$, $\vec{j}$, and $\vec{k}$
 * Two vectors of the same dimension
   * $\vec{v}$ =  $\begin{bmatrix}v_1 \\\v_2\\\v_3 \end{bmatrix}$

   * $\vec{w}$ = $\begin{bmatrix}w_1 \\\w_2 \\\w_3\end{bmatrix}$
 * Order: matters
 * Cross products
   *  $\vec{p}$ = $\vec{v}$ $\times$ $\vec{w}$
    *  $\vec{p}$ is a vector that is perpendicular to both $\vec{v}$ and $\vec{w}$  and thus normal to the plane containing them

 * $\vec{p}$ directions
   *  $\vec{p}$ > 0: when $\vec{v}$ is on the right side of $\vec{w}$
   *  $\vec{p}$ < 0: when $\vec{v}$ is on the left side of $\vec{w}$

 * Numerically
   * $\begin{bmatrix}v_1 \\\v_2\\\v_3 \end{bmatrix}$  $\times$ $\begin{bmatrix}w_1 \\\w_2 \\\w_3\end{bmatrix}$ = ($v_2w_3 -w_2v_3)\vec{i}$ + ($v_3w_1$ - $v_1w_3)\vec{j}$ + ($v_1w_2$ - $v_3w_1)\vec{k}$

 * Geometrically
   * The positive area of the parallelogram having $\vec{v}$ and $\vec{w}$ as sides
   * The length of $\vec{p}$ = the area of parallelogram defined by $\vec{v}$ and  $\vec{w}$
   * The direction of $\vec{p}$ is defined using the Right Hand Rule
      * index finger: point to the direction of $\vec{v}$
      * middle finger: point to the direction of $\vec{w}$
      * the direction of thumb: points to the direction of $\vec{p}$

![cross product projection](../src/image/crossproduct.png)  

[Screenshot at 6:03 in video](https://www.youtube.com/watch?v=eu6i7WJeinw&list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab&index=10)


<br>

### Matrix
#### How is matrix useful?
 * Computer space
 * Solve system equations: Linear system
#### Matrix multiplication
 * Right to left (die Rechts-vor-links-Regel)

<br>

### Glossary
 * Column space: all the linear combinations of the column vectors [Video by Sal Khan](https://www.khanacademy.org/math/linear-algebra/vectors-and-spaces/null-column-space/v/column-space-of-a-matrix)
 * Determinant:
   * Geometrically: the determinant of matrix A, det(A), it can be viewed as the volume scaling factor of the linear transformation described by the matrix
 * Identity transformation: the transformation that does nothing
 * Gaussian elimination
 * Inverse matrices: the inverse transformation in geometry (clockwise-counterclockwise, rightward shear -- leftward shear)
 $A^{-1}*A^1=\begin{bmatrix}0&1 \\\1&0 \end{bmatrix}$
 * Rank: the number of dimensions in the output of a transformation (e.g. Rank 2: All vectors after a transformation land on a 2-D plain)
 * Null space (kernel): the space of all vectors becoming null  
 * Row echelon form
 * Span: the set of all linear combinations of two vectors.  

 <br>

---
 ### References
  * [Cross product introduction](https://www.khanacademy.org/math/linear-algebra/vectors-and-spaces/dot-cross-products/v/linear-algebra-cross-product-introduction)

  * [Essence of linear algebra](https://www.youtube.com/watch?v=fNk_zzaMoSs&list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab)
