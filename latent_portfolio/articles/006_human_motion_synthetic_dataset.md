# Human motion synthetic dataset

This project produced a dataset of video clips featuring digital humans with a wide range of body shapes and sizes performing various actions. Using rigged characters and a mocap dataset. The resulting video dataset is intended for training computer vision models.

![Synthetic dataset stills](006_synthetic_dataset_stills.jpg)

**Ensuring broad diversity was essential.** The videos were carefully generated to cover important differences such as lighting, background, clothing, gender, body proportions, and types of motion.

The software was **designed to use computer resources efficiently**, running only when there was spare capacity available.

It ran as a `daemon background service`, managed by `systemd`, periodically checking resource usage and pausing itself whenever the computer was busy with other tasks.

The development work included designing the background service, monitoring system resources and managing the video diversity, along with building flexible Blender scenes using adjustable 3D human models, customizable materials, and different lighting setups.



<script type="application/json">
{
  "technologies": [
    "Python",
    "Bash",
    "bpy",
    "blender",
    "EEVEE"
  ],
  "description": "Synthetic dataset of diverse human motions for computer vision, rendered with Blender and resource-aware automation.",
  "tags": [
    "resource-optimization",
    "skeletal-animation",
    "3D-data",
    "mesh-manipulation"
    "mocap"
  ]
}
</script>
