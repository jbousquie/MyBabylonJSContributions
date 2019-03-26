# MyBabylonJSContributions
List of my contributions to BabylonJS since v 2.1

## Features
- Solid Particle System
- Facet Data
- Curve3 : quadratic and Bezier, Hermite and Catmull-Rom splines, Curve3 generic objects
- Path3D
- Per face UVs and colors for many mesh types
- Parametric shape dynamic morphing
- `options` parameter for all mesh types in the class`MeshBuilder`
- Sphere, tube, lathe, etc mesh arc and slice
- Cylinder mesh arc
- `GroundMesh.getNormalsAtCoordinates()`
- `sideOrientation` for all meshes
- `frontUV` and `backUV` for all meshes
- `colorFilter` for height maps


## Mesh types
- Ribbon
- Tube
- Extrusion, simple and custom
- Lathe
- Dashed Lines
- Line System
- Polyhedron
- Disc

## Maths
- `RotationFromAxis()`
- `QuaternionFromAxis()`
- `addRotation()` : accumulative rotations

## Optimizations
- `VertexData.ComputeNormals` : up to 5 times faster
- `Tmp` class
- Cylinder mesh seamless normals
- `GroundMesh.getHeightAtCoordinates()`

## Extensions
- Dynamic Terrain

## API Documentation
