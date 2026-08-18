---
category: decisions
title: Config Source Of Truth
tags: ["config", "config-source-of-truth", "mongodb", "settings"]
updated: "2026-08-17T04:47:20Z"
source: agent_extract
---

- MongoDB is the single source of truth for configuration.
- A /settings page (no login required) allows editing config values.
- Persisted fields: owner number, shop name, product API URL, AI provider/key.
- Changes take effect without redeploying the app.
