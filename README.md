# 3D Raytracing Engine
A 3D Raytracing Engine, built as a project in CS 1230 (Computer Graphics) at Brown University. Read more about the course and the individual projects [here](https://cs1230.graphics/projects).

Notable components of the projects:
* **Scene Parsing** - Loading and parsing a scene (JSON file). Scene files include global lighting constants, global camera settings, and 3D objects (location, size, material properties).
* **Camera** - A camera module with location and direction settings. Finds 3D objects intersected for a per-pixel camera ray.
* **3D Objects** - Various shape classes (Cube, Sphere, Cylinder, Cone). Calculates intersection positions for incoming camera rays.
* **Phong Illumination Model** - Phong Model for illumination on surfaces, incorporating ambient, diffuse, and specular light. Also factors in attenuation and material properties.
* **Light Sources** - Three types of light sources: directional lights, spot lights, and point lights.
* **Shadows** - Object shadows for all light sources.
* **Reflections** - Object reflections for objects with reflective material properties. Also includes recursive reflections up to a maximum recursion depth.
* **Texture Mapping / Filtering** - Nearest neighbor texture filtering for rendering texture maps over 3D objects using the UV coordinate system. Also allows a blending factor for blending a texture map with the underlying material texture.

NOTE: This is a placeholder repo with no code to respect Brown's Academic Code. If you are a potential employer and would like to look at the code, please send me an email.
