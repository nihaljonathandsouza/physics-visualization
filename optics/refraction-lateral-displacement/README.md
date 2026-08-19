# Refraction & Lateral Displacement

A Manim-based visualization of refraction through a parallel-sided transparent slab, demonstrating Snell's law and the resulting lateral displacement of the emergent ray.

## Overview

This animation explores how changing the refractive index of a medium affects the direction and velocity of light inside the medium.

The visualization demonstrates that, for a parallel-sided slab, the emergent ray remains parallel to the incident ray while experiencing a lateral displacement.

## Concepts Visualized

* Snell's law of refraction
* Refractive index and light velocity
* Bending of light at an interface
* Parallel-sided slab geometry
* Lateral displacement
* Relationship between incident and emergent angles
* Dependence of lateral displacement on refractive index

## Mathematical Model

The animation dynamically evaluates the refracted angle using Snell's law:

$$
n_1 \sin\theta_1 = n_2 \sin\theta_2
$$

The lateral displacement is calculated as:

$$
d = \frac{t\sin(\theta_1-\theta_2)}{\cos\theta_2}
$$

The visualization also demonstrates the relationship between refractive index and light velocity:

$$
v = \frac{c}{n}
$$

## Implementation

**Software:** Python, Manim Community Edition

The scene uses dynamic trackers and continuously updated geometric objects to recalculate the ray paths, angles, velocity, and lateral displacement as the refractive index changes.

## Visualization

[▶ Watch the animation](https://drive.google.com/file/d/11RM37APisURD3mA6m3hYun-VM7dP2HPt/view?usp=sharing)

## Note

This is a conceptual physics visualization intended to demonstrate the underlying optical relationships rather than serve as a numerical ray-tracing model.

