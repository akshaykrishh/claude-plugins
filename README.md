# claude-plugins

Claude Code plugins for running agents at scale: many sessions, accounts and worktrees.

```sh
claude plugin marketplace add akshaykrishh/claude-plugins
claude plugin install starling@akshaykrishh
```

| Plugin | What it does |
|---|---|
| [starling](https://github.com/akshaykrishh/starling) | Guards parallel worktrees (no `git stash`, no destructive git, no polling loops) and keeps shared config intact across accounts. |
