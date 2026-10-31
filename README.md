# PlayHT

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

> **No longer operating.** This company or product has shut down, been discontinued, or been deprecated. This profile is kept as a historical record and is not maintained or rated.

PlayHT, now operating as PlayAI, is a generative voice platform offering realistic text-to-speech models, AI voice agents, and a podcast generation tool called PlayNote. The platform centers on the PlayDialog and Play 3.0 Mini models, providing more than 200 prebuilt voices across multiple languages and accents with sub-second latency suited to conversational applications. PlayAI exposes REST and streaming endpoints for text-to-speech, voice listing, voice cloning, and voice agent management. It ships Python and Node.js SDKs and a hosted playground, and integrates with the major voice agent infrastructure stacks. The product is widely used to build voice assistants, IVRs, narration pipelines, and content production workflows.

**Areas:** Voice · TTS · Text-to-Speech · Voice Cloning · Voice Agents · Streaming · PlayDialog · Play 3.0 · PlayNote · Multilingual · Real-Time · Defunct

## PlayHT on APIs.io (historical record)

Everything profiled for PlayHT is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/playht/](https://apis.io/providers/playht/)** — or go straight to one of the APIs or properties below.

### APIs (8)

- [PlayAI Text-to-Speech API](https://apis.io/apis/playht/tts-api/) — The PlayAI Text-to-Speech API converts text into natural, human-like speech using the PlayDialog 1.0, Dialog 1.0 Turbo, and Play 3.0 Mini models. It…
- [PlayAI Voice Agents API](https://apis.io/apis/playht/agents-api/) — The PlayAI Voice Agents API lets developers create, configure, and run conversational AI agents that process voice input and respond with generated speech,…
- [PlayHT Agents API](https://apis.io/apis/playht/playht-agents-api/) — Voice agent management.
- [PlayHT Conversations API](https://apis.io/apis/playht/playht-conversations-api/) — Agent conversation retrieval.
- [PlayHT External Functions API](https://apis.io/apis/playht/playht-external-functions-api/) — Tool definitions for voice agents.
- [PlayHT PlayNote API](https://apis.io/apis/playht/playht-playnote-api/) — Document-to-audio PlayNote jobs.
- [PlayHT TTS API](https://apis.io/apis/playht/playht-tts-api/) — Text-to-speech generation, streaming, and async jobs.
- [PlayHT Voices API](https://apis.io/apis/playht/playht-voices-api/) — Prebuilt voice catalog.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [PlayAI Realtime WebSocket APIs](https://apis.io/asyncapis/playht/playht-asyncapi/)

#### Event channels (2)

Individual events and webhooks the provider emits.

- [/playht-tts/stream](https://apis.io/channels/playht/playht-tts-stream/)
- [/v1/talk/{agentId}](https://apis.io/channels/playht/v1-talk-agentid/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Playht Agentic Access](https://apis.io/agentic-access/playht/playht-agentic-access/)

#### Collections (7)

Postman and Open Collection request collections.

- [PlayAI API](https://apis.io/collections/playht/open-playht/)
- [PlayAI Agents API](https://apis.io/collections/playht/open-playht-agents-api/)
- [PlayAI Agents Conversations API](https://apis.io/collections/playht/open-playht-conversations-api/)
- [PlayAI Agents External Functions API](https://apis.io/collections/playht/open-playht-external-functions-api/)
- [PlayAI Agents PlayNote API](https://apis.io/collections/playht/open-playht-playnote-api/)
- [PlayAI Agents TTS API](https://apis.io/collections/playht/open-playht-tts-api/)
- [PlayAI Agents Voices API](https://apis.io/collections/playht/open-playht-voices-api/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [PlayHT — asyncapi rules](https://apis.io/rules/playht/playht-asyncapi-spectral-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Playht Authentication](https://apis.io/security/playht/playht-authentication/)
- [Playht Domain Security](https://apis.io/security/playht/playht-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Playht Plans Pricing](https://apis.io/plans/playht/playht-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Playht Rate Limits](https://apis.io/rate-limits/playht/playht-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Playht Finops](https://apis.io/finops/playht/playht-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://play.ht)
- [Documentation](https://docs.play.ai)
- [Pricing](https://play.ht/pricing)
- [Blog](https://play.ht/blog)
- [Terms of service](https://play.ht/terms)
- [Privacy policy](https://play.ht/privacy)
- [GitHub](https://github.com/playht)

## API Evangelist rating

**Not rated** — this company is recorded as no longer operating, so no score is published. If it is in fact operating, say so on this repository and it will be re-profiled.

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for PlayHT: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/playht/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
