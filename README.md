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

## Skill Installer Usage (openai/skills)

Use `skill-installer` directly in Codex chat (no project Python dependency).

List curated skills from `openai/skills`:

```text
Use skill-installer to list curated skills from openai/skills.
```

Install one curated skill from `openai/skills`:

```text
Use skill-installer to install <skill-name> from openai/skills (path: skills/.curated/<skill-name>).
```

Install from a GitHub URL path:

```text
Use skill-installer to install from:
https://github.com/openai/skills/tree/main/skills/.curated/<skill-name>
```

## Manual (Short)

1. Codex 채팅에서 `skill-installer` 호출
2. `openai/skills` 기준으로 원하는 스킬 설치 요청
3. Codex 재시작
