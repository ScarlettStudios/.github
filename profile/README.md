# Scarlett Studios

Scarlett Studios builds creative tools for artists, developers, and technical creators.

We combine **AI, 3D workflows, and creative production pipelines** to help creators turn ideas into usable assets faster.

[Available Tools](#available-tools) · [Upcoming Tools](#upcoming-tools) · [Support & Feedback](#support--feedback)

## Available Tools

| Tool | Platform | Get started | YouTube demo / tutorial |
| --- | --- | --- | --- |
| PlaneToPBR | Blender 4.2+ | [Repository & installation](https://github.com/ScarlettStudios/PlaneToPBR#installation) | [Watch the demo](https://youtu.be/AtydKv722z8) |
| PlaneToPBR_unreal | Unreal Engine 5.7 & 5.8; MCP extension for 5.8 | [Downloads](https://github.com/ScarlettStudios/PlanetoPBR_Unreal/releases) · [Setup](https://github.com/ScarlettStudios/PlanetoPBR_Unreal#installation) | [Watch the demo](https://youtu.be/Cuf8gHKDcQE) |

### PlaneToPBR — Blender Extension

Generate a **fully textured PBR plane from a single image in one click.**

PlaneToPBR automatically generates and applies diffuse, normal, roughness, depth, and segmentation maps, then builds the material for you.

**Compatible with Blender 4.2 and newer.**

[Get started with PlaneToPBR](https://github.com/ScarlettStudios/PlaneToPBR#installation) · [Watch the YouTube demo](https://youtu.be/AtydKv722z8)

#### Planned Blender Update & MCP Extension

A PlaneToPBR update targeting the **latest Blender release** and a **Model Context Protocol (MCP) extension for Blender** are planned. Release dates and setup details will be announced as development progresses.

### PlaneToPBR_unreal — Unreal Engine Plugin

Bring the **PlaneToPBR workflow directly into Unreal Engine**: import a reference image, generate PBR textures, and create a ready-to-use textured plane.

**Released plugin builds are available for Unreal Engine 5.7 and 5.8.** Choose the build that matches your engine version.

[Download the Unreal plugin](https://github.com/ScarlettStudios/PlanetoPBR_Unreal/releases) · [Installation guide](https://github.com/ScarlettStudios/PlanetoPBR_Unreal#installation)

[Get started with PlaneToPBR Unreal](https://github.com/ScarlettStudios/PlanetoPBR_Unreal#readme) · [Watch the YouTube demo](https://youtu.be/Cuf8gHKDcQE)

#### Released MCP Extension — Unreal Engine 5.8

PlaneToPBR_unreal also includes a released **Model Context Protocol (MCP) extension for Unreal Engine 5.8**, available in the same repository.

## Upcoming Tools

| Tool | Platform / focus | Target release |
| --- | --- | --- |
| BuildingUV_blender | Building UV workflows in Blender | October 2026 |
| PlanetoPBR_Cinema_4D | Image-to-PBR workflows in Cinema 4D | Nov 2026 |
| buildinguv_unreal | Building UV workflows in Unreal Engine | December 2026 |
| Buildinguv_Cinema_4D | Building UV workflows in Cinema 4D | Jan 2027 |
| PlaneToPBR Pro | GPU-powered PBR generation | February 2027 |

These are planned release windows and may change as development progresses.

### BuildingUV_blender — Building UV Atlas for Blender

Generate a **cube-cross building UV atlas from a single front-facing building image** inside Blender.

The add-on generates side, back, and top views through Hugging Face, reuses the side view for both left and right walls, and adds a solid gray bottom tile. Blender composes the six faces into one atlas, saves the generated images, and applies the cube-cross UV layout to a mesh.

### PlanetoPBR_Cinema_4D — Image-to-PBR for Cinema 4D

Bring the **PlaneToPBR image-to-PBR workflow into Cinema 4D**. The planned extension will turn a reference image into a textured plane using generated diffuse, normal, roughness, depth, and segmentation maps.

### buildinguv_unreal — Building UV Atlas for Unreal Engine

Bring the **single-image building UV atlas workflow into Unreal Engine**.

The planned plugin will generate side, back, and top views through Hugging Face, reuse the side view for both walls, and include a solid gray bottom tile. It will compose the cube-cross atlas for use on building meshes in Unreal Engine, with the generated views and final atlas saved for reuse.

### Buildinguv_Cinema_4D — Building UV Atlas for Cinema 4D

Create a **cube-cross building UV atlas from one front-facing building image** in Cinema 4D.

The planned extension will generate side, back, and top views through Hugging Face, use the same side image for both walls, and add a solid gray bottom tile. It will compose the atlas for use on building meshes in Cinema 4D and save the generated views and final atlas for reuse.

### PlaneToPBR Pro — GPU Generation

A high-quality version of PlaneToPBR powered by **GPU inference**, targeting higher fidelity normal maps, improved depth maps, better segmentation masks, and higher quality PBR outputs.

The planned service will run on GPU infrastructure, with access through an API and web interface.

More tools coming soon.

## What We're Building

Our focus is on AI-assisted content generation, 3D production workflows, and automation for creative pipelines.

Our goal is to make complex technical workflows **simple, fast, and accessible to creators.**

## Support & Feedback

For PlaneToPBR, [report a bug](https://github.com/ScarlettStudios/PlaneToPBR/issues) or [ask a question and share ideas](https://github.com/ScarlettStudios/PlaneToPBR/discussions).

For PlaneToPBR Unreal, [report a bug or request a feature](https://github.com/ScarlettStudios/PlanetoPBR_Unreal/issues).

[Explore all Scarlett Studios repositories](https://github.com/orgs/ScarlettStudios/repositories) to follow development and discover new tools.
