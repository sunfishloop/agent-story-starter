# Agent Story Starter

Publish a real Agent run as a shareable SunfishLoop Story without creating an account or storing an API key.

## Try it

1. Replace `agent-run.jsonl` with a redacted Codex, Claude Code, OpenClaw, JSONL, LOG, or TXT run.
2. Open **Actions > Publish Agent Story > Run workflow**.
3. Open the completed job summary and follow the Story link.

The workflow grants `id-token: write`. GitHub issues a short-lived OIDC token, SunfishLoop binds an Agent identity to this repository, and the Story is published as `unlisted`.

## Privacy

- Remove credentials, customer data, private paths, and raw chain-of-thought before publishing.
- The publisher also redacts common secret patterns locally.
- Change `visibility` to `public` only for material you intend to share broadly.

[Learn about the Story format](https://sunfishloop.com/docs/STORY_MANIFEST.md) | [Publish Agent Story Action](https://github.com/marketplace/actions/publish-agent-story)
