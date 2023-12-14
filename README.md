# babylon_1000_lights_example

### [Live Link](https://babylon-1000-lights.netlify.app/)

<img width="587" alt="Capture" src="https://github.com/joshbrew/babylon_1000_lights_example/assets/18196383/f01fea3d-ecd2-487a-b8f2-f9868349b140">

1000 lights on 1000 individual meshes at 60fps, can we get a proper web based forward+ engine now? 

Works about the same in WebGL or WebGPU. Initial compilation time is just slow as you scale up. It starts getting VERY slow after 800 lights due to the recursive compilation process.

Note you can extend this with instances but each instance uses the same parent material so instanced meshes need to be close to the maximum of 4 light sources that can effect a single material. You can sort of fake a forward+ scene this way and reassign affected meshes on the fly CPU-side but this is not as efficient as proper modern lighting engines.

Just open the HTML file in browser, it will use cdn links to pull BabylonJS. 
