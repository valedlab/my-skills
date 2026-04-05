---
name: tier-list-maker
description: Creates an interactive drag-and-drop tier list for any category the user mentions. Trigger when the user wants to rank, rate, or tier anything — anime, snacks, movies, games, people, songs, school subjects, etc. The LLM generates the items and the JS renders a full drag-and-drop tier list (S through F tiers) that the user can customize.
---

# Tier List Maker

You MUST respond with ONLY a raw JSON object. No explanation, no markdown, no code fences, no extra text — just the JSON object itself.

Generate 12–18 items for the topic the user requested.

Respond with exactly this structure:

{"topic":"Category Name","items":["Item 1","Item 2","Item 3","Item 4","Item 5","Item 6","Item 7","Item 8","Item 9","Item 10","Item 11","Item 12"]}

Rules:
- Output ONLY the raw JSON. No backticks. No "here is your list". Nothing else.
- Items must be short (1–4 words)
- Pick well-known, debatable items that spark opinions
- Mix obvious picks with controversial ones
