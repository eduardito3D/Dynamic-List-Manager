# Rig Dynamic List Manager

A Blender add-on for intelligently managing rig visibility through organized groups, native keyframes, and performance‑optimized toggling.

## Features

- **Dynamic Rig Detection** – Automatically discovers primary and secondary rigs in complex hierarchies.
- **Bone Collection Tree** – Intuitive expandable/collapsible UI using Blender’s native `layout.panel`.
- **Native Animation** – Control object visibility with simple keyframes on the group index.
- **Performance Optimized** – Uses `bpy.data.user_map` instead of iterating over `bpy.data.objects` for large scenes.
- **Blender 4.0+ Compatible** – Fully leverages the latest Blender Python API.

## Installation

1. Download the latest `.py` release.
2. In Blender, go to `Edit → Preferences → Add-ons`.
3. Click `Install…`, select the file, then enable the add-on.

## Basic Workflow

1. Select an armature or a mesh with an armature modifier.
2. Click **Add Group** to create a new animation state.
3. Use **Assign Selected Meshes** to attach meshes to the group.
4. Configure bone collections and visibility settings per state.
5. Animate the group index to transition visibility changes.

## Version Notes

- **[v1.1.2 – Release Notes](release_1.1.2.txt)** – Includes performance optimizations and UI improvements based on instructor feedback.

## License

Personal/educational use. Commercial use requires explicit permission from the author.

## Contact & Support

- **Developer**: Eduardito_3D
- **Last Updated**: 2026‑04‑22
- **Feedback**: Create an issue on the GitHub repository for bugs, feature requests, or suggestions.