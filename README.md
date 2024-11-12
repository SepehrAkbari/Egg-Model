![Frame 5](https://github.com/user-attachments/assets/2363a506-bd27-4b5e-adfb-267a41e6157a)

# Mathematical Modeling Of A Chicken Egg!

This project was part of my Mathematics Internal Assesment for the IB Diploma. It explores the theme of daily oridenry objects being seen and looked at mathematically, I used a chicken egg!

## Project Overview

The project aims to find the volume and surface area of the an ordinary egg:

- Modeling the egg
- Calculating its volume
- Calculating its surface area

## Modeling

Three different ways of modeling was used, and then compared, to find the most suitable and accurate.

- Ellipse Equation

$$
\frac{x^2}{r_x^2} + \frac{y^2}{r_y^2} = 1
$$

- Oviform Curve

$$
y = \pm \frac{B}{2} \times \sqrt{\frac{L^2-4x^2}{L^2+8wx+4w^2}}
$$

- Lagrange Interpolation

$$
T(x) = \sum^{n+1}_{i=1} 
\frac{(x-x_1) \ldots (x-x_{i-1})(x + x_{i+1}) \ldots (x-x_{n+1})}{(x_i-x_1) \ldots (x_i-x_{i-1})(x_i + x_{i+1}) \ldots (x_i-x_{n+1})}
$$

A python program was used to find its axis symmetry

```{bash}
python AxisOfSymmetry.py
```

## Volume




