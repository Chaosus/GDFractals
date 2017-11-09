# GDFractals
Fractal shaders for Godot 3.0

# Contains
* Julia fractal shader
* Mandelbrot fractal shader
* Sierpinski carpet shader

# How to setup
* Create ColorRect and lay ShaderMaterial on it
* Drag&drop the required shader to ShaderMaterial slot
* Create gradient texture, if you dont want to create it yourself use fire_gradient.tres
* Set parameters :

# for Julia:
Gradient - gradient texture
Scale = 4, 4
Offset = 0, 0
MaxIter = from 100 to 1000
Speed = 1
 
# for Mandelbrot:
Gradient - gradient texture
Scale = 1, 1
Offset = 0, 0
MaxIter = from 100 to 1000
 
# for Serpinski carpet:
Scale = 81, 81
Offset = 0, 0
