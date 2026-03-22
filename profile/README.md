<p align="center">
  <img src="https://raw.githubusercontent.com/wave-orchestrator/.github/main/profile/banner.jpg" alt="Wave Orchestrator — AI-powered development that starts with a plan" width="100%" />
</p>

---

AI coding tools are powerful, but without structure they produce sprawling diffs, monster PRs that nobody reviews properly, and changes that break things in ways you discover too late. The problem isn't generating code — it's generating *reviewable, well-scoped, standards-compliant code* at scale.

Wave Orchestrator puts **planning first**. Before any agent writes a line of code, you collaborate on a structured implementation plan — breaking features into phases, then into focused, single-purpose PRs that humans and AI can both reason about. Agents execute in parallel, a reviewer catches issues before you ever see them, and you stay in control through checkpoints and a real-time TUI.

### How it works

1. **Plan** — Describe what you want to build. Claude analyzes your codebase and proposes a phased plan — small, pointed PRs with clear scope and acceptance criteria.
2. **Approve** — Review the phases, adjust scope, add checkpoints where you want human verification.
3. **Execute** — Agents implement PRs in parallel git worktrees. Automated review catches bugs and standards violations before they reach you.
4. **Ship** — Merge from the TUI or GitHub. The next wave kicks off automatically, respecting dependencies.

No 2,000-line diffs. No "LGTM" on code nobody actually read. Just structured, reviewable work — delivered fast.

### Get started

```bash
npm install -g wave-orchestrator
wave-orchestrator init ~/my-project
wave-orchestrator plan
wave-orchestrator run
```

### Repositories

| Repo | Description |
|------|-------------|
| [wave-orchestrator](https://github.com/wave-orchestrator/wave-orchestrator) | CLI, engine, docs, and agent packages |

### Links

- [Documentation](https://wave-orchestrator.dev)
- [npm](https://www.npmjs.com/package/wave-orchestrator)
- [Contributing](https://github.com/wave-orchestrator/wave-orchestrator/blob/main/CONTRIBUTING.md)
