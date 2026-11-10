# agenticode skills

agentic-work's own skills and agents for [agenticode](https://github.com/agentic-work/agenticode-releases).

Nothing here is installed by copying this repo. The [agenticode Registry](https://github.com/agentic-work/agenticode-registry) pins each item to a commit of this repo and records the sha256 of every file in its signed index; agenticode fetches the files from here at that commit and checks each one before installing.

| Item | Kind | Notes |
| --- | --- | --- |
| [`skills/simplify`](skills/simplify/SKILL.md) | skill | `/simplify`: review changed code for reuse, quality and efficiency, then fix what it finds. Installed by default on first run (it used to be compiled into agenticode). |
| [`agents/registry-scout.md`](agents/registry-scout.md) | agent | Runs scout, bump and gate for the registry and reports what needs a decision. |

```
agenticode add skill simplify
agenticode add agent registry-scout
```

MIT licensed (see [LICENSE](LICENSE)).
