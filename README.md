# n8n skill sync test

Test fixtures for importing skills from GitHub into the n8n skills hub. Each folder under `skills/` is one skill.

| Skill | Expected check result |
| --- | --- |
| `pdf-summary` | Passed |
| `release-notes` | Review: external links |
| `support-triage` | Review: instructions that send data out, and a script that n8n does not import |
| `hidden-text` | Blocked: hidden characters |
