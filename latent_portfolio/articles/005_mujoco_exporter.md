# Mujoco to GLTF exporter

Mujoco is an advanced physics simulation engine, frequently used in robotics and embedded AI environments. This project required a flexible conversion system for Mujoco files, enabling jointed structures and their simulated motions to be converted into several common exchange formats.

![exporter scheme](005_exporter_scheme.png)

The output exchange formats included GLTF, BLEND, FBX, BVH, etc. They can also be used the other way around: get data from exchange formats and generate SKN files.


The core functionality consisted in an efficient, production-ready conversion from Mujoco to GLTF, using native `pygltflib`. Advanced functionalities made use of the `blender python module (bpy)` to export in different formats, or parse a variety of format to extract meshes to be combined with the mujoco skeleton.


The module featured an **agnostic skeleton representation**, used as a **common intermediate step for all input/output** formats. The business logic required to perform the conversions was implemented exclusively using numerical operations in `NumPy`, providing a flexible and scalable foundation for the entire module.


This module delivered robust, high-performance data conversion services to a backend system requiring real-time format translation. It was designed for seamless deployment in a distributed infrastructure, supporting containerization and automated orchestration.


<script type="application/json">
{
  "technologies": [
    "Python",
    "Mujoco",
    "GLTF",
    "NumPy",
    "bpy"
  ],
  "description": "Exporters for converting Mujoco files to exchange formats like GLTF, FBX, BLEND and BVH, with bidirectional support for generating SKN files from exchange formats",
  "tags": [
    "production-ready",
    "skeletal-animation",
    "3D-data",
    "mesh-manipulation"
  ]
}
</script>
