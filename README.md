# claude-plugins

Claude Code plugins for working with many AI agents at once.

```sh
claude plugin marketplace add akshaykrishh/claude-plugins
claude plugin install starling@akshaykrishh
claude plugin install magpie@akshaykrishh
```

| Plugin | What it does |
|---|---|
| [starling](https://github.com/akshaykrishh/starling) | Keeps many sessions, accounts and worktrees running safely: guards parallel worktrees (no `git stash`, no destructive git, no polling loops), repairs shared config across accounts, and shows every session that needs you. Needs the `starling` CLI (`npm install -g @akshaykrishh/starling`). |
| [magpie](https://github.com/akshaykrishh/magpie) | Hands queued work to your agents: registers magpie's MCP server and teaches agents to take, finish and hand back items. Needs the magpie app or CLI. |

Each works alone. Installed together, new sessions start with what magpie has queued for their
repo and branch, and magpie shows which agents are waiting for you.
