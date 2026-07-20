# Privacy Compression Agent

A small, portable skill for turning private calls, interviews, and conversation transcripts into public-safe communication drafts without pretending that a draft is approved.

The agent is deliberately a compressor, not a publisher. It removes unnecessary private detail, preserves project substance, records only a non-reconstructive privacy-review status, and leaves approval with the human operator and relevant participants.

## Files

- `SKILL.md` — the portable Hermes skill.
- `templates/public-notes.md` — output template.
- `references/output-schema.md` — required output sections and privacy checks.

## Integrate with Hermes

Copy `SKILL.md` into a local skill directory, for example:

```text
~/.hermes/skills/research/privacy-compression-agent/SKILL.md
```

Then start a new Hermes session so the skill index reloads. The skill can also be copied into an in-repo `skills/<category>/<name>/SKILL.md` tree.

## Basic usage

Give the agent:

1. the private source transcript;
2. the intended public audience and project context;
3. any names, topics, or details that must remain private;
4. the desired output path.

Ask it to produce a draft only. It must not publish, post, or change visibility without separate explicit approval.

## Design boundary

The compressor is privacy-preserving but not a consent oracle. It cannot infer that a participant approves publication. It must mark uncertainty, preserve tentative language, and surface review questions instead of resolving them by invention.
