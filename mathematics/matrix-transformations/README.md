# Matrix Geometry & Transformations

A Manim-based visualization of matrices as geometric transformations rather than simply arrays of numbers.

## Concepts Visualized

- Basis vectors and the unit square
- Matrix transformations
- Anisotropic scaling
- Rotation matrices
- Determinant as an area-scaling factor
- Inverse matrices
- Composition and reversal of transformations
- Connection to optical systems and ray-transfer matrices

## Mathematics

For a transformation

$$
A =
\begin{pmatrix}
a & b \\
c & d
\end{pmatrix},
$$

the determinant is

$$
\det(A)=ad-bc.
$$

The determinant gives the area-scaling factor of the transformation.

The inverse transformation satisfies

$$
A^{-1}A=I.
$$

The visualization also demonstrates how the columns of a transformation matrix determine where the basis vectors are mapped.

## Optics Connection

The animation connects matrix geometry to optical applications.

Anisotropic scaling provides an intuitive geometric analogy for astigmatism, while rotation illustrates the role of orientation in toric optical systems.

The final section introduces the connection between these transformations and ray-transfer matrices used to model optical systems.

## Tools

- Python
- Manim Community Edition
- NumPy

## Visualization

[Watch the animation](./matrix-transformations.mp4)
