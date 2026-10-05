# GAME_PROGRAM-EX--1
## EXP:1 Implementing various effects in a material such as emissive, roughness and metallic properties in Unreal Engine

## NAME: HARESH R
## REG NO: 212224040097

# Aim:
To create and demonstrate different material properties in Unreal Engine, including emissive lighting, surface roughness, and metallic effects, using the Material Editor.

# Procedure
1. Create a Material
Launch Unreal Engine.
In the Content Browser, right-click and choose Material.
Rename the material as M_EffectsDemo.
3. Set the Base Color
Open the newly created material.
Add a Vector Parameter or Constant3Vector node.
Connect this node to the Base Color input to define the material's main color.
4. Add an Emissive Effect
Insert a Multiply node into the graph.
Connect a Constant3Vector node to specify the glow color.
Add a Scalar Parameter node to control the glow intensity.
Connect the output of the Multiply node to the Emissive Color input.
5. Adjust Surface Roughness
Add a Scalar Parameter node.
Connect it to the Roughness input.
Smaller values produce a smoother and shinier surface, while larger values create a rougher appearance.
6. Configure Metallic Properties
Add another Scalar Parameter node.
Connect it to the Metallic input.
A value of 0 represents a non-metallic surface, whereas 1 creates a fully metallic look.
7. Save and Test the Material
Save the material.
Apply it to a mesh such as a sphere, cube, or any object in the scene to observe the material effects.

# Output:
<img width="1037" height="581" alt="Screenshot 2026-10-05 201647" src="https://github.com/user-attachments/assets/794b25aa-99d4-4017-b5f9-d2fcfdfd310b" />

# Result:
The material was successfully created in Unreal Engine with the following features.A glowing emissive effect controlled through color and intensity parameters.Adjustable roughness levels to represent different surface textures.Metallic controls that simulate the reflective characteristics of metal surfaces.
