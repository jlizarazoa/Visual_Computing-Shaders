# Shaders — Visual Computing exercises

**Academic project** · Visual Computing course, Universidad Nacional de Colombia, 2022

Three exercises with GLSL fragment shaders in p5.js (WEBGL mode), using the p5.treegl library:

1. **ex1 — Color blending:** two colors picked by the user are multiplied in the shader, with a brightness slider passed as a uniform.
2. **ex2 — Texture coordinates:** maps each pixel's texture coordinates to a color.
3. **ex3 — Uniforms from the sketch:** opacity and the blue channel are controlled from JavaScript.

**Related:** [Inside the Backrooms](https://sansanchezmo.github.io/SHADERS/BACKROOMS/index.html), a team 3D browser experience from the same course, built with p5.js and GLSL shaders. I came up with the game concept and built the shadows and visual details.

## Run locally
Serve the folder with any static server (for example `npx serve .`) and open `index.html`. To switch exercises, change the script in `index.html` (`ex1.js`, `ex2.js` or `ex3.js`).
