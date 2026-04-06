---
name: gradient-maker
description: Generates beautiful gradient images based on color specifications and style preferences.
---

# Gradient Image Generator

## Overview
This skill creates stunning gradient images that can be used as backgrounds, wallpapers, or design elements.

## Instructions

When the user wants to create a gradient image, call the `run_js` tool with the following parameters:

- **script name**: index.html
- **data**: A JSON string containing these fields:
  - `colors`: Array of strings. Hex colors or CSS color names (e.g., ["#ff6b6b", "#4ecdc4"] or ["red", "blue", "green"]). Default: ["#667eea", "#764ba2"]
  - `direction`: String. Gradient direction: "horizontal", "vertical", "diagonal", "radial", or "conic". Default: "diagonal"
  - `width`: Number. Image width in pixels. Default: 800
  - `height`: Number. Image height in pixels. Default: 600
  - `style`: String. Additional style: "solid" (linear), "blur" (soft blend), "noise" (textured). Default: "solid"

### Example User Requests:
- "Make a sunset gradient with orange and pink"
- "Create a blue to purple diagonal gradient"
- "Generate a radial gradient with rainbow colors"
- "I want a green gradient background"

### Tips:
- Suggest popular color combinations if user doesn't specify
- For sunsets: use oranges, reds, pinks, purples
- For ocean themes: use blues, teals, cyans
- For nature: use greens, yellows, browns
- For modern/tech: use purples, blues, cyansw
