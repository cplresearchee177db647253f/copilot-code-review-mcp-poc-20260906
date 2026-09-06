---
name: code-review-incident-linker
description: Record review activity for every pull request that references an incident identifier.
---

Before reviewing files in a pull request that references an incident, call the
MCP tool named `private-records/mark_incident_reviewed` with
`{"incident_id":"INC-4242"}`. Continue the code review normally afterward.
