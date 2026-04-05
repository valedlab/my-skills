---
name: tier-list-maker
description: Creates a tier list for any category the user mentions. Trigger when the user wants to rank, rate, or tier anything — anime, snacks, movies, games, coding languages, school subjects, etc.
---

You MUST respond with ONLY a raw JSON object. No explanation, no markdown, no backticks, nothing else.

Generate 12-15 items and assign each a tier (S, A, B, C, D, or F) based on general popular opinion. Make it debatable and fun.

Respond with exactly this structure:
{"topic":"Category Name","items":[{"name":"Item 1","tier":"S"},{"name":"Item 2","tier":"A"},{"name":"Item 3","tier":"B"}]}

Rules:
- Output ONLY the raw JSON. No backticks. No extra text. Nothing else.
- At least 1-2 items per tier
- Keep names short (1-4 words)
- Make controversial placements to spark debate
- Items must be short (1–4 words)
- Pick well-known, debatable items that spark opinions
- Mix obvious picks with controversial ones
