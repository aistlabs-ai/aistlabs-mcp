# AISTLabs MCP server

Generate video, images and audio on top AI models from your agent — with an AI director built in.

AISTLabs is an AI creative studio for agents. Connect it to Claude, ChatGPT, Codex or any MCP client and create video, images and audio right from the chat — short films, social content, music videos, ads or anything you imagine.

- **Top models in one place.** Seedance 2.5, Wan 3.0, MiniMax, Nano Banana, GPT Image, Seedream, ElevenLabs voices and music. Drafts in 480p, finals in 1080p; references, first and last frames, video editing.
- **AI director.** Describe an idea or share a photo. AISTLabs writes the script, directs and renders a finished video.
- **Price before you spend.** Every generation is quoted in credits first; your agent asks before spending.
- **Your library.** Projects, history, favourites and reusable elements: characters, locations, props.
- **For brands.** Brand Brain remembers your style and products; performance ads turn a winning creative into variations to test.

**Built for agents:** clear tool descriptions, idempotent creation, live status, confirmation before deleting, and errors that say what to do next.

**Connect:** one-click OAuth 2.1 sign-in, or an API key from aistlabs.ai/connect-agent. Connecting is free; generations use AISTLabs credits, and new accounts get 20 free credits.

## Connect

**Endpoint:** `https://aistlabs.ai/mcp` (Streamable HTTP, OAuth 2.1)

- **Claude:** Settings → Connectors → Add custom connector → paste `https://aistlabs.ai/mcp` → sign in.
- **Cursor and other MCP clients:**
  ```json
  { "mcpServers": { "aistlabs": { "url": "https://aistlabs.ai/mcp" } } }
  ```
- **API key instead of OAuth:** create one at https://aistlabs.ai/connect-agent and send `Authorization: Bearer <key>`.

## Example prompts

1. Make a 10-second cinematic shot of a dragon flying over a neon city at night, 16:9.
2. Turn my photo into a Pixar-style character and animate a 5-second clip.
3. Write and voice a 20-second intro for my YouTube channel.
4. Turn this product photo into a 15-second vertical ad for TikTok.
5. How much would a 10-second Seedance 2.5 video in 1080p cost?

## Docs

https://aistlabs.ai/docs/index.md · Privacy: https://aistlabs.ai/privacy · Terms: https://aistlabs.ai/terms · Support: support@aistlabs.ai
