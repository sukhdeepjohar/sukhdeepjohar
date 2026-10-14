# Hi, I'm Sukhdeep 👋

I build practical AI agents and systems, automation tools, API integrations and reliability.

## Open-source contributions

### OpenClaw

- **LiteLLM image editing:** Fixed image-edit failures through LiteLLM proxies by
  replacing an incompatible JSON request with multipart image uploads. Merged in
  [PR #118562](https://github.com/openclaw/openclaw/pull/118562), shipped in
  [OpenClaw v2026.8.1](https://github.com/openclaw/openclaw/releases/tag/v2026.8.1),
  and listed in the
  [release contribution record](https://github.com/openclaw/openclaw/blob/v2026.8.1/CHANGELOG.md#L9149).

- **Browser startup reliability:** Prevented concurrent lazy browser starts from
  producing `PortInUseError` by sharing the in-flight startup operation. Merged in
  [PR #61772](https://github.com/openclaw/openclaw/pull/61772), shipped in
  [OpenClaw v2026.4.24](https://github.com/openclaw/openclaw/releases/tag/v2026.4.24),
  and listed in the
  [release contribution record](https://github.com/openclaw/openclaw/blob/bb0cafde4f23b2ad98ccc8db5328c430177d249a/CHANGELOG/2026.4.24.md#L116).

### LiteLLM

- **Gemini 3 sampling defaults:** Stopped LiteLLM from injecting `temperature: 1.0`
  into Gemini 3+ requests that did not set one, on both the Gemini API and Vertex AI
  routes. Merged in [PR #45107](https://github.com/BerriAI/litellm/pull/45107).

[All my merged open-source PRs →](https://github.com/search?q=is%3Apr+is%3Amerged+author%3Asukhdeepjohar+-org%3Amyluigi+-user%3Asukhdeepjohar&type=pullrequests)

## Interests

AI agent infrastructure · Local LLMs and RAG · API automation · TypeScript · Python
