# Julia set produced with WebGPU

A single-file WebGPU demo that renders a Julia fractal directly in the browser. The fractal updates interactively based on mouse position, using a WGSL fragment shader for GPU rendering.

Notes
- The fractal is computed in a WGSL shader on the GPU.
- If WebGPU is not available, the page will throw an error.
- The canvas automatically fills the entire viewport meaning <span style="color:red;">this may run slowly on larger monitors...</span>}
