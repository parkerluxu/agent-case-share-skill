# Agent Case Share Skill

Reusable AI-agent skill for publishing and editing Agent Case Share tasks, articles, Markdown images, and reusable assets.

## Install

Copy the skill folder into your agent skills directory:

```bash
cp -R skills/publish-agent-case-share ~/.codex/skills/
```

For Claude Code or Gemini CLI, import or reference the same `skills/publish-agent-case-share` folder if your setup supports file-based skills/instructions.

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

