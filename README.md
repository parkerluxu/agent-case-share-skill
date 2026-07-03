# Agent Case Share Skill

Reusable AI-agent skill for publishing and editing Agent Case Share tasks, articles, Markdown images, and reusable assets.

## Install

### Codex

Install or load this repository as a Codex plugin, or copy the skill directly:

```bash
cp -R skills/publish-agent-case-share ~/.codex/skills/
```

### Claude Code

Load the repository as a plugin:

```bash
claude --plugin-dir .
```

Or copy the skill directly:

```bash
mkdir -p ~/.claude/skills
cp -R skills/publish-agent-case-share ~/.claude/skills/
```

### Gemini CLI

Install or link the repository as a Gemini CLI extension:

```bash
gemini extensions install https://github.com/parkerluxu/agent-case-share-skill.git
```

For local development:

```bash
gemini extensions link .
```

## Required Secrets

Create a personal API key from your Agent Case Share `/profile` page.

Use these environment variables in your shell or agent runtime:

```bash
AGENT_CASE_SHARE_BASE_URL=https://your-domain.com
AGENT_CASE_SHARE_API_KEY=acsp_live_replace_me
```

Do not commit real API keys.

## Usage

Ask your agent to use `$publish-agent-case-share` to publish or update a case, article, tutorial, Markdown image, or reusable asset.

The skill defaults AI-created tasks to hidden and articles to draft unless you explicitly ask for public publishing.
