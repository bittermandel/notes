# [Bitter Engine](https://github.com/bittermandel/bitter-engine)
Bitter Engine is my personal engine to explore the Game Dev space and learn more about rendering.

The plan is to make it as simple as possible using techniques that are know to be simplistic while performant.


## Features
*In order of implementation*

1. WGPU with GLSL ✔️
	1. Generate Spir-V from GLSL with [naga](https://github.com/gfx-rs/naga)
2. Window with Winit ✔️
3. Winit event loop with render, resize and update
4. Render triangle
6. Cube
	1. Texture
7. Cube entity
9. Sphere entity
10. Shader per entity support
11. Camera uniform buffer
12. Directional light
13. Shadow map
14. Point light
15. Cube map
16. Point shadow
17. ECS
18. Debug lines
19. Imgui/Egui
20. Ambient Occlusion
21. Frustrum Culling
22. Cascaded Shadow Mapping