# Tellius → ElevenLabs MCP client metadata

`client.json` is an OAuth [client ID metadata document](https://datatracker.ietf.org/doc/draft-ietf-oauth-client-id-metadata-document/).
Its URL is the OAuth client ID that the Tellius demo2 tenant uses to connect to the ElevenLabs hosted MCP server
(`https://api.elevenlabs.io/v1/mcp`) with PKCE and no client secret. It holds no secrets: only the client's name, its
callback URL on demo2, and the requested scope (`text_to_speech`).
