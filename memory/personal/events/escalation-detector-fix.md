---
category: events
title: Escalation Detector Fix
tags: ["escalation", "escalation-detector-fix", "fix", "regex"]
updated: "2026-08-18T04:52:46Z"
source: agent_extract
---

- Fixed over-aggressive detectEscalation regex: broad 'batao' pattern caused normal product queries to trigger owner escalation and pause the customer for 3 hours (2026-08-17).
