# Julia set produced with WebGPU

Demo can be found [here](https://laurencewilkes.github.io/JuliaSetWeb/).

A single-file WebGPU demo that renders a Julia fractal directly in the browser. 
The fractal updates interactively based on the position of the mouse and uses a WGSL fragment shader for GPU rendering.
This is based off the ["Your first WebGPU app"](https://codelabs.developers.google.com/your-first-webgpu-app) tutorial.

Notes
- The fractal is computed by a fragment shader on the GPU.
- If WebGPU is not available, the page will throw an error.
- The canvas automatically fills the entire viewport meaning <code style="color : orangered;">this may run slowly on larger monitors...</code>.
