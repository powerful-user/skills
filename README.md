# skills

Agent skills. Each one lives in `skills/<name>/` and installs with the [skills](https://skills.sh) CLI.

| Skill | What it does |
|---|---|
| [makeready](skills/makeready/) | Builds InDesign documents and print layouts with [makeready](https://github.com/powerful-user/makeready), which compiles layout files into native InDesign IDML, with no InDesign needed to build: asks about missing measurements, previews before building, and reads the build back to check it against the brief. |

## Install

```
npx skills add powerful-user/skills --skill makeready
```

Leave out `--skill` to choose from a list.
