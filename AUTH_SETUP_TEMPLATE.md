# AUTH_SETUP_TEMPLATE.md

This file is a non-secret template for recreating authentication and access setup on another machine.
Do not store raw tokens, private keys, or secret credentials in this file.

## Goal
Recreate the same practical access pattern without exporting secrets.

## What to configure manually on the new machine

### 1. GitHub access
- Configure SSH key for GitHub access
- Verify with:
  - `ssh -T git@github.com`

### 2. OpenClaw provider auth
Recreate whichever providers are needed in the target environment.
Examples from the source environment conceptually included:
- OpenAI/Codex auth
- Google/Gemini auth
- Ollama/local model access if used

### 3. Channel auth (only if needed)
If the clone should act through messaging channels, manually configure the channel credentials again.
Example categories:
- Telegram bot token
- any other channel-specific bot/app token

### 4. OpenClaw config review
On the new machine, review:
- active plugins
- memory backend selection
- auth profiles
- tool/elevated settings
- channel settings

## Security rule
Never commit or publish:
- PAT tokens
- OAuth secrets
- bot tokens
- private SSH keys
- local credential stores

## Best practice
Use placeholders or env vars in config and keep real secrets only on the destination machine.
