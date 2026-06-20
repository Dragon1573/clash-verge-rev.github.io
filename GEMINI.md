# GEMINI.md

> [!NOTE]
> 本项目使用 `CLAUDE.md` 作为 AI 助手（包括 Claude Code 和 Gemini CLI）的主要说明和规范文档。
> This project uses `CLAUDE.md` as the primary configuration and instruction file for AI agents (including Claude Code and Gemini CLI).

请直接阅读并遵循 [CLAUDE.md](./CLAUDE.md) 中定义的项目规范、开发命令和内容准则。

Please refer to and follow the project guidelines, development commands, and content patterns defined in [CLAUDE.md](./CLAUDE.md).

<!-- CODEGRAPH_START -->
## CodeGraph

In repositories indexed by CodeGraph (a `.codegraph/` directory exists at the repo root), reach for it BEFORE grep/find or reading files when you need to understand or locate code:

- **MCP tools** (when available): `codegraph_explore` answers most code questions in one call — the relevant symbols' verbatim source plus the call paths between them. `codegraph_node` returns one symbol's source + callers, or reads a whole file with line numbers. If the tools are listed but deferred, load them by name via tool search.
- **Shell** (always works): `codegraph explore "<symbol names or question>"` and `codegraph node <symbol-or-file>` print the same output.

If there is no `.codegraph/` directory, skip CodeGraph entirely — indexing is the user's decision.
<!-- CODEGRAPH_END -->
