---
category: decisions
title: Model Priority Order
tags: ["active-ai-model", "ai", "ai-model", "configuration", "decision", "model", "model-priority-order", "models", "openrouter", "priority", "speed"]
updated: "2026-08-18T05:35:06Z"
source: agent_extract
---

- Active provider: OpenRouter (2026-08-17)
- Active model: `google/gemma-4-31b-it:free` — currently rate-limited (429) (2026-08-17)
- Fallback providers: Groq, Gemini (2026-08-17)
- Fallback model (within OpenRouter): `nvidia/nemotron-3-nano-30b-a3b:free` (2026-08-17)
- Priority order (fastest first):
  1. `nvidia/nemotron-3-nano-30b-a3b:free` (~600ms)
  2. `google/gemma-4-26b-a4b-it:free` (~950ms)
  3. `google/gemma-4-31b-it:free` — last, currently rate-limited (429) (2026-08-17)
