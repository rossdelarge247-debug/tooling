# Repository conventions

- This repo holds several independent tools. Each one lives in `tools/<tool-name>/` (lowercase, hyphenated) and is self-contained, with its own dependency manifest, lockfile, tests and README. Don't add shared root-level dependencies.
- Start a new tool by copying `tools/_template/`.
- When adding a tool, renaming one or changing its status, update the Tools table in the root `README.md`.
- Keep each commit to one tool where possible, and prefix the commit subject with the tool name, e.g. `my-tool: add CSV export`.
