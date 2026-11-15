# skills

[![skills.sh](https://skills.sh/b/anhthang/skills)](https://skills.sh/anhthang/skills)

Agent skills I use across my projects, installable with the [skills CLI](https://github.com/vercel-labs/skills).

| Skill                                                | What it does                                                                                                                                                                                     |
| :--------------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [`raycast-publish`](skills/raycast-publish/SKILL.md) | Publish a Raycast extension kept in its own repository to the Raycast Store, keep its store pull request free of development files, and pull store changes back without merge commits on `main`. |

## Install

```bash
npx skills add anhthang/skills --skill raycast-publish -g
```

`-g` installs it for your user, so every project can use it; add `-a claude-code` (or another agent) to skip the agent prompt. Update it later with:

```bash
npx skills update raycast-publish -g
```

## License

[MIT](LICENSE)
