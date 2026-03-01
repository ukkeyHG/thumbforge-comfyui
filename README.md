# ThumbForge ComfyUI

YouTube thumbnails generation workflow for ComfyUI.
This workflow is optimized for 1280x720 (720p) resolution.

## Workflow Overview
- **Resolution**: 1280x720
- **Model**: SDXL (Inpainting optimized recommended)
- **Features**: YouTube thumbnail layout, Highres Fix, Inpainting support.

## Prerequisites
- [ComfyUI](https://github.com/comfyanonymous/ComfyUI)

### Required Custom Nodes
To use this workflow, you need to install the following custom nodes:
- **kikotools** (specifically `ImageScaleDownBy` node)
  - You can install it via [ComfyUI-Manager](https://github.com/ltdrdata/ComfyUI-Manager) by searching for "kikotools".

## Installation
1. Install ComfyUI and the required custom nodes.
2. Download the `.json` workflow file from this repository.
3. Drag and drop the `.json` file into ComfyUI.

## Usage
- **LoadImage**: Upload your base image or character.
- **CLIPTextEncode**: Enter your prompt for the background/details.
- **KSampler**: Adjust seed and steps as needed to generate the final thumbnail.

---
Created by Antigravity.
