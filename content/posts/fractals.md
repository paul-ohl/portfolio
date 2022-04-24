---
title: "Fractals!"
date: 2021-08-14
draft: false
toc: true
images:
  - images/fractal.png
tags: 
  - C
  - Graphic
---

Here are two projects in which I have worked with fractals.

One in C, the other using [shadertoy](https://shadertoy.com), a website to
create shaders.

## The C fractals

This was a project I had to do for [my school](https://42.fr) called `fract-ol`.

The goal was to use a small C graphics library (created by my school based on)
to generate and display multiple fractals. We then had to be able to navigate
this fractal, and of course, zoom into it!

*Keep in mind that we were not allowed to use multi-threading, and that the code
runs on the CPU (not the GPU), so the performances degrade quickly*

I chose to create a few fractals:
- [Mandelbrot](https://en.wikipedia.org/wiki/Mandelbrot_set)
- [Julia](https://en.wikipedia.org/wiki/Julia_set)
- [Burning ship](https://en.wikipedia.org/wiki/Burning_Ship_fractal)
- Glynn fractal (a Julia set to the power of 1.5)
- Reverse Mandelbrot

## The shadertoy fractal

This one is used as the background of my homepage!

Once I had finished the project for my school, I wanted to experiment a bit with
GPU generated fractals, in order to have better looking fractals, and smoother
transitions, this is where I found [shadertoy](https://shadertoy.com).

{{< shadertoy sdtXzS 4 >}}

Shadertoy is a website where you can create *shaders*, i.e. images that are
generated on the go using your GPU, so anything you see on that website is
**not** a video, but a picture generated using code!

I learned the basics of shader creation in an afternoon with [this handy
tutorial](https://www.shadertoy.com/view/Md23DV) and adapted my code to run
without any math libraries!
