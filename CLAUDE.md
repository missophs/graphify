## graphify

This project has a knowledge graph at graphify-out/ with god nodes, community structure, and cross-file relationships.

Rules:
- For codebase questions, when graphify-out/graph.json exists, do NOT run `graphify query`/`path`/`explain` directly in Bash — that dumps the full node list into context. Instead run it through context-mode's `ctx_batch_execute`: pass the graphify command (e.g. `graphify query "<question>"`, `graphify path "<A>" "<B>"`, `graphify explain "<concept>"`) as the command, and the actual question(s) as `queries`, so only the matched, derived answer returns. Fall back to a direct Bash call only if context-mode's tools aren't loaded this session.
- If graphify-out/wiki/index.md exists, use it for broad navigation instead of raw source browsing.
- graphify-out/GRAPH_REPORT.md (192KB) is for broad architecture review or when query/path/explain don't surface enough context — route it through context-mode (`ctx_index` then `ctx_search`) instead of a raw Read.
- After modifying code, run `graphify update .` to keep the graph current (AST-only, no API cost, no context-mode wrapping needed since it produces no output worth indexing).
