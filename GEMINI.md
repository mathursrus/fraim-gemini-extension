# FRAIM

Use FRAIM to discover and execute phased jobs, reusable skills, rules, evidence, and mentoring workflows.

When a user asks for FRAIM:

1. Inspect local FRAIM job stubs under `fraim/ai-employee/jobs/`, `fraim/ai-manager/jobs/`, and `fraim/personalized-employee/jobs/` when available.
2. Match the request to a FRAIM job or skill.
3. Load full job content with `get_fraim_job` or skill content with `get_fraim_file`.
4. Follow the phased instructions and use `seekMentoring` when phase transitions are required.

Job stubs are for discovery only.

