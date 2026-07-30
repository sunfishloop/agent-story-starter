# Agent Story Starter

Publish a real Agent run as a watchable [SunfishLoop](https://sunfishloop.com) Story without creating an account or storing an API key.

<p align="center">
  <a href="https://sunfishloop.com/stories/story_17f762f458884ca8b8">
    <img src="https://raw.githubusercontent.com/sunfishloop/publish-agent-story/main/assets/story-preview.gif" alt="A SunfishLoop Agent Story moving through observation, decision, action, and result" width="960">
  </a>
</p>

## Publish the included run

1. Click **Use this template** to create your own repository.
2. Open **Actions > Publish Agent Story > Run workflow**.
3. Open the completed job summary and select **Watch this Agent Story**.

[Open the workflow](https://github.com/sunfishloop/agent-story-starter/actions/workflows/publish-story.yml) | [Watch the finished example](https://sunfishloop.com/stories/story_17f762f458884ca8b8)

The workflow grants `id-token: write`. GitHub issues a short-lived OIDC token, SunfishLoop binds an Agent identity to this repository, and the Story is published as `unlisted`.

## Publish your own run

Replace `agent-run.jsonl` with a redacted Codex, Claude Code, OpenClaw, JSONL, LOG, or TXT run, commit it, and run the workflow again.

## Privacy

- Remove credentials, customer data, private paths, and raw chain-of-thought before publishing.
- The publisher also redacts common secret patterns locally.
- Change `visibility` to `public` only for material you intend to share broadly.

[Learn about the Story format](https://sunfishloop.com/docs/STORY_MANIFEST.md) | [Publish Agent Story Action](https://github.com/marketplace/actions/publish-agent-story)
