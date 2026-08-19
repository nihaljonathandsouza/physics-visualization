# Prism Deviation & Dispersion

A Manim-based visualization of light passing through a prism, connecting the geometry of refraction with angular deviation, minimum deviation, and dispersion.

## Concepts Visualized

- Refraction through a prism
- Angle of incidence
- Angle of refraction
- Angle of emergence
- Prism angle
- Angle of deviation
- Minimum deviation
- Refractive index
- Dispersion of white light
- Formation of a spectrum

## Overview

The animation begins by constructing the geometry of a triangular prism and tracing a light ray through it.

The ray is refracted at both surfaces of the prism, allowing the relationship between the incident ray, refracted ray, emergent ray, and angle of deviation to be visualized.

The animation then explores how the deviation changes and introduces the condition of minimum deviation.

The final section demonstrates dispersion, showing how different wavelengths of light undergo different amounts of deviation and separate into a spectrum.

## Mathematics

For a prism with angle A, the geometry gives:

$$
A = r_1 + r_2
$$

The angle of deviation is:

$$
\delta = i_1 + i_2 - A
$$

At minimum deviation, the optical path is symmetric:

$$
i_1 = i_2
$$

and

$$
r_1 = r_2 = \frac{A}{2}
$$

The animation connects these relationships to the dependence of refractive index on wavelength, which produces dispersion.

## Teaching Focus

The visualization is designed to make the geometry of prism refraction easier to understand by showing the ray path and angles directly rather than relying only on a static diagram.

## Implementation

**Software:** Python, Manim Community Edition, NumPy

The animation was constructed programmatically using geometric primitives, dynamically calculated ray directions, mathematical expressions, and animated transformations.

## Visualization

[▶ Watch the animation](YOUR_GOOGLE_DRIVE_LINK)
