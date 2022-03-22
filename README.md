# Fractals

> Basic Python Fractal Scripts

Don't expect high-quality images. Math equations didn't work :(

### Packages

Pillow. A PIL fork.

## Mandelbrot sets

A Mandelbrot set is defined by the set of complex numbers c for which the complexm numbers of the sequence $z_{n}$ remain bounded in absolute value. The sequence $z_n$ is defined by:

- $z_{0}$
- $z_{n+1}=z_{n}^2+c$

The modules of a complex number is its distance to 0. In Python, this can be done by using `abs(z)` where $z$ is a complex number. We can also assume that the sequence $z_n$ is not bounded if the modules of one of its terms is greater than 2.

A complex number ($x+iy$) can be represented on a complex plane (argand diagram). The real part of the complex number is represented along the x-axis and the imaginary part on the y-axis.

The visual representation of the mandelbrot set may be created by determining, for each point $c$ of a complex plane, whether $z_n$ is bounded.


## Julia sets

The definition of a Julia set is very similar to the mandelbrot set. As a reminder, the Mandelbrot set is the set of the complex numbers $c$  for which the sequence $z_{n+1}=z_{n}^2+c$ is bounded ($z_0$ is set to $0$). While, the definition of the Julia sets is the numbers $z_0$ for which the sequence is bounded, with $c$ a constant value.
