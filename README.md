# OctaneRender® ORBX File Repository

ORBX file repository for Octane Render, a spectral GPU renderer
Not associated with OTOY Inc.  

<details>
<summary> ORBX File Format</summary>

  ## ORBX
  
> OTOY releases OctaneRender™ 1.5 and introduces .ORBX (20, 2014) 
The new .ORBX file format improves considerably on traditional 3D formats such as .OBJ, .CAD, or .STL, going beyond storing simple geometry to include all aspects of a 3D scene, such as materials, properties, textures, lighting, transform hierarchies and cameras, all in a self-contained file format. Unlike the Alembic file format, .ORBX was designed in close collaboration with Autodesk and Mozilla to be a flexible container for a wide range of uses beyond computer graphics, including video, 3D printing, holography, design and engineering.  

> The .ORBX format allows for incredible granularity, supporting the modeling of physical properties of a scene or object down to two hundredths of a nanometer, or a quarter of the size of a hydrogen atom. OctaneRender™ 1.5 and related plugins allow artists and animators to perfectly import and export extraordinarily complex 3D scenes in .ORBX format across 15 modeling programs, appearing in the same final render quality as the program they were originally created in. The flexibility of the .ORBX format has implications for media and entertainment companies who can now effectively use their computer-generated assets and IP across a variety of mediums, from feature film and television development, to video games, web sites, and toy production for example.
> The ORBX file format is the best way to transfer scene files from 3D Authoring software programs that use the Octane Plug-in such as Octane for Maya, Octane for Cinema 4D, or OctaneRender Standalone. This format is more efficient than FBX when working with Octane specific data as it provides a flexible, application independent format. ORBX is a container format that includes all animation data, models, textures etc. that is needed to transfer an Octane scene from one application to another.
</details>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://images.squarespace-cdn.com/content/v1/608815d80fda1f2c79e48753/b5b55060-e5a1-4e98-aea0-23e54469c5e0/octane_spectral_rendering.jpg">
  <source media="(prefers-color-scheme: light)" srcset="https://images.squarespace-cdn.com/content/v1/608815d80fda1f2c79e48753/6939c512-12d2-4368-a8ad-91704d72dcdf/octane_spectral_irradiance_mode.jpeg">
  <img alt="Octane Render Thumbnail" src="https://images.squarespace-cdn.com/content/v1/608815d80fda1f2c79e48753/b5b55060-e5a1-4e98-aea0-23e54469c5e0/octane_spectral_rendering.jpg">
</picture>

## Overview

The ORBX file repository is an easy way to quickly access, copy and paste modified Octane's items / objects or "nodes", in other words, custom presets.
Two approaches to this workflow:
1. Copy of the raw code, for instance, to direcly paste in Octane Standalone
2. Download of the .orbx file for a direct copy into the ORBX folder default directory known as the "LocalDb".

| Category | Description |
| :---   | :---   |
| `Lights` | e.g. improved defaults and custom lights (filters, effects and more) |
| `Kernels` | e.g. improved defaults and custom kernels tailored to more specific situations (like caustics) |
| `Materials` | e.g. fully procedural textures to material-groups for more complex surfaces |
| `Project files` | complete "scene files" data set including geometry (assets), textures, cameras and more |

## Wiki
Dedicated [Wiki page](https://github.com/skientia/ORBX/wiki).

### System Requirements
Recommended version: `Octane 2024` (Standalone or plug-in) and onwards.
Cross-platform (Windows, Linux, macOS).
> [!NOTE]
> OctaneRender® is available for free via the free tier, e.g. Octane for Blender.

> [!TIP]
> Copying `Raw` code to pasting in Standalone will identically add the ORBX content, without downloading the .orbx as nodes in Standalone are XML formatted data. 
Doing so does not substitute to download and placing the .orbx files or folders into the LocalDb directory.

> [!IMPORTANT]
> Plug-in users must refer to the dedcated Octane [plug-in host e.g. Octane for Blender] documentation for ORBX import information.

##  Legal

Permissions
* Commercial use
* Modification
* Distribution
* Private use

Limitations
* Liability
* Warranty
