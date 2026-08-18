---
category: events
title: Slow Reply Fix
tags: ["fix", "performance", "slow-reply-fix"]
updated: "2026-08-18T04:52:41Z"
source: agent_extract
---

- Fixed slow reply issue: reduced gap from ~1 min to ~1 sec (2026-08-17)
- Added 15-second per-request timeout
- Ordered free models by speed (fastest first)
- Treat empty replies as failures
