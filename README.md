# sending-codex-to-figma-sample

Sample skill repository focused on Codex workflows.

## Structure

Local development copy (root):
- `SKILL.md`
- `scripts/capture.mjs`
- `references/capture-views-spec.md`
- `agents/openai.yaml`
- `LICENSE.txt`

Installable catalog copy (`openai/skills` style):
- `skills/.curated/sending-codex-to-figma-sample/`

## Use in Codex

1. Local auto-discovery in a target project:

```text
<project>/.agents/skills/sending-codex-to-figma-sample
```

2. Installer/catalog style path:

```text
skills/.curated/sending-codex-to-figma-sample
```

## Notes

- This is a sample/learning skill, not a production-certified workflow.
- Claude-only directives were removed and replaced with Codex-compatible instructions.
