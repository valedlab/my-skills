---
name: gradient-maker
description: Generate gradient images with custom colors and directions.
---

# Gradient Generator

## Instructions
Call `run_js` with:
- script name: index.html  
- data: JSON string with optional fields:
  - colors: array of hex colors (default: ["#667eea","#764ba2"])
  - direction: "horizontal","vertical","diagonal","radial"(default:"diagonal")
  - width: number (default: 400)
  - height: number (default: 300)

Example: {"colors":["#ff6b6b","#4ecdc4"],"direction":"diagonal"}  - `height`: Number. Image height in pixels. Default: 600
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
