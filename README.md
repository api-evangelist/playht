# PlayHT (playht)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

PlayHT, now operating as PlayAI, is a generative voice platform offering realistic text-to-speech models, AI voice agents, and a podcast generation tool called PlayNote. The platform centers on the PlayDialog and Play 3.0 Mini models, providing more than 200 prebuilt voices across multiple languages and accents with sub-second latency suited to conversational applications. PlayAI exposes REST and streaming endpoints for text-to-speech, voice listing, voice cloning, and voice agent management. It ships Python and Node.js SDKs and a hosted playground, and integrates with the major voice agent infrastructure stacks. The product is widely used to build voice assistants, IVRs, narration pipelines, and content production workflows.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/playht/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/playht/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** 3rd-Party

## Tags

- Voice
- TTS
- Text to Speech
- Voice Cloning
- Voice Agents
- Streaming
- PlayDialog
- Play 3.0
- PlayNote
- Multilingual
- Real-Time

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-29

## APIs

### PlayAI Text-to-Speech API

The PlayAI Text-to-Speech API converts text into natural, human-like speech using the PlayDialog 1.0, Dialog 1.0 Turbo, and Play 3.0 Mini models. It supports streaming, voice cloning, and a large catalog of prebuilt voices across many languages and accents.

- **Human URL:** [https://docs.play.ai](https://docs.play.ai)
- **Base URL:** `https://api.play.ai`

#### Tags

- TTS
- Streaming
- Voice Cloning
- Voices
- Multilingual

#### Properties

- [Documentation](https://docs.play.ai)
- [Getting Started](https://docs.play.ai/tts-api)
- [Sign Up](https://play.ai/signup)
- [API Reference](https://docs.play.ai)
- [SDK](https://github.com/playht/pyht)
- [SDK](https://github.com/playht/playht-nodejs-sdk)
- [GitHub Repository](https://github.com/playht)
- [Pricing](https://play.ai/pricing)
- [Authentication](https://docs.play.ai)
- [AsyncAPI](https://raw.githubusercontent.com/api-evangelist/playht/refs/heads/main/asyncapi/playht-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/playht.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/playht.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### PlayAI Voice Agents API

The PlayAI Voice Agents API lets developers create, configure, and run conversational AI agents that process voice input and respond with generated speech, with optional tool use and external integrations.

- **Human URL:** [https://docs.play.ai](https://docs.play.ai)
- **Base URL:** `https://api.play.ai`

#### Tags

- Voice Agents
- Conversational AI
- Tools
- Streaming

#### Properties

- [Documentation](https://docs.play.ai)
- [API Reference](https://docs.play.ai)
- [SDK](https://github.com/playht)
- [Pricing](https://play.ai/pricing)
- [AsyncAPI](https://raw.githubusercontent.com/api-evangelist/playht/refs/heads/main/asyncapi/playht-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/playht.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/playht.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://play.ht)
- [Documentation](https://docs.play.ai)
- [Blog](https://play.ht/blog)
- [GitHub Organization](https://github.com/playht)
- [Pricing](https://play.ht/pricing)
- [Terms of Service](https://play.ht/terms)
- [Privacy Policy](https://play.ht/privacy)
- [Discord](https://discord.gg/VuP4nXVA9M)
- [X (Twitter)](https://x.com/play_ht)
- [LinkedIn](https://www.linkedin.com/company/playht)
- [L L Ms Txt](https://docs.play.ai/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
