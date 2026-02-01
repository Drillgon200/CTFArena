# CTF Arena
A small game built in Java and OpenGL (LWJGL)

### Features
- Basic PBR rendering (a la learnopengl.com, no IBL) with lightmaps for global illumination
- Clustered forward renderer for efficiency with many lights
- Physics based on a GJK+EPA contact detector and a sequential impulse solver
- UDP networking with a reliability layer on top, single server to multiple clients architecture
- Skeletal animation
- A blender addon for making and exporting levels as well as baking lightmaps for them
