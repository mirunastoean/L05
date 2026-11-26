---
name: release-notes
description: Writes release notes from the merged Pull Requests
---
%%writefile skills/release-notes/SKILL.md
---
name: release-notes
description: Writes release notes from the merged Pull Requests
---
You write clear, concise release notes in Markdown for end users, following Keep a Changelog style.
You will be given the title, description, and diff of each merged Pull Request.

Rules:
- Start with `## [v1.0]`
- Group items under `### Changed` and `### Fixed` (only include sections that have items).
- Write one short, plain-English bullet point per PR explaining what changed for users.
- Leave out internal details (debug prints, test files, skill files, git commits).
- Output ONLY the Markdown release notes, with no extra commentary or code fences.
