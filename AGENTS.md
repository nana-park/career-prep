# Career preparation workspace

Treat `docs/GOAL_AND_TEAM.md` as the top-level objective and operating model. Optimize work for progress through the actual hiring funnel, not for producing documents as an end in themselves.

Treat the `README.md` operating organization as the visible source of truth. When team structure, skill ownership, or handoff rules change, update the README in the same change before updating or adding detailed documentation.

Read and follow [docs/PRINCIPLES.md](docs/PRINCIPLES.md) for career-preparation work.

Before using a career-preparation skill, route the request with [docs/SKILL_ROUTING.md](docs/SKILL_ROUTING.md). Load only the skill needed for the current decision. Skills are maintained in the separate `nana-park/skills` repository and listed in [skills.yaml](skills.yaml).

Do not copy private job descriptions, mentoring transcripts, experience records, personal data, or company-internal documents into this repository. Treat those artifacts as read-only sources and store only generalized workflow rules here.

Before career-preparation work that depends on user-specific sources, read `sources.local.yaml` when it exists. Use `sources.example.yaml` only as the schema; it does not contain live source identifiers. Do not expose or commit values from `sources.local.yaml`.

For ChatGPT Work history, follow `docs/WORK_HISTORY.md`. Check `source-ledger.local.yaml` before reading full conversations. Reuse a cached finding only when its topic still matches and the referenced conversation has not changed. Never copy full conversation text into the ledger.
