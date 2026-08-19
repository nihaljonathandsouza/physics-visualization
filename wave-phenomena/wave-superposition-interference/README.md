# Wave Superposition & Interference

A Manim-based visualization connecting the mathematical principle of superposition with physical wave interference and Young's double-slit experiment.

## Overview

The animation begins with the mathematical description of two travelling waves and their resultant displacement. The phase difference is then varied to demonstrate constructive, destructive, and intermediate interference.

The visualization subsequently connects this mathematical treatment to Young's double-slit experiment, showing how waves emerging from two slits produce an interference pattern.

## Concepts Visualized

* Principle of superposition
* Travelling wave equations
* Phase difference
* Constructive interference
* Destructive interference
* Resultant wave displacement
* Young's double-slit experiment
* Wavefront propagation from two coherent sources
* Interference pattern formation

## Mathematical Model

The two waves are represented as:

$$
y_1 = A\sin(kx-\omega t)
$$

$$
y_2 = A\sin(kx-\omega t+\phi)
$$

Their resultant displacement is:

$$
y_R = y_1+y_2
$$

The animation dynamically varies the phase difference $\phi$ to demonstrate the transition between constructive and destructive interference.

## Implementation

**Software:** Python, Manim Community Edition

The visualization uses dynamic mathematical plots, `ValueTracker` objects, continuously updated waveforms, vector arrows, mathematical labels, and animated transformations to connect the mathematical and physical descriptions of interference.

## Preview

The rendered animation is included in this directory.

## Note

This is a conceptual visualization intended to illustrate the mathematical and physical principles of wave interference.

