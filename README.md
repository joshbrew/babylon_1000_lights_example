# babylon_1000_lights_example

### [Live Link](https://babylon-1000-lights.netlify.app/)

<img width="587" alt="Capture" src="https://github.com/joshbrew/babylon_1000_lights_on_instances_example/assets/18196383/bbcc31ab-297b-4c8d-a5a4-a2440338ba90">

1000 lights on 1000 individual meshes at 60fps, can we get a proper web based forward+ engine now? 

Works about the same in WebGL or WebGPU. Initial compilation time is just slow as you scale up. It starts getting VERY slow after 800 lights due to the recursive compilation process.

Just open the HTML file in browser, it will use cdn links to pull BabylonJS. 
