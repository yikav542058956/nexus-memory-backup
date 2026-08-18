---
category: decisions
title: QR Token Value
tags: ["access", "config", "env-var", "protection", "qr", "qr-token-value", "railway", "security", "token"]
updated: "2026-08-17T06:54:07Z"
source: agent_extract
---

- QR connection page is protected with a token/password.
- Token: `zaro-wa-bot-2026` (2026-01-01)
- Stored in Railway environment variable; code default fallback is `'dev'`.
- User wants token changed to `'dev'`; manual change pending due to Railway OAuth 401 (2026-01-01).
