---
name: this-or-that
description: Runs an endless swipe-card "Would You Rather / This or That" game. Trigger when the user wants to play this or that, would you rather, or wants fun dilemmas to answer. The LLM generates spicy, funny, or thought-provoking dilemmas and the JS handles the full swipe game with personality tracking.
---

# This or That

## Instructions

When the user wants to play This or That or Would You Rather:

1. Generate exactly 15 dilemmas relevant to the user's vibe (or general if no preference given)
2. Output ONLY a JSON block in this exact format:

```json
{
  "theme": "Theme Name",
  "dilemmas": [
    { "a": "Option A text", "b": "Option B text" },
    { "a": "Option A text", "b": "Option B text" }
  ]
}
```

## Guidelines

- Make options genuinely hard to choose between — no obvious answers
- Mix funny, spicy, relatable, and deep dilemmas
- Keep each option SHORT (max 8 words)
- Themes can be: life choices, food, school, social media, superpowers, money, etc.
- Output ONLY the JSON block, nothing else
- s
