# AvatarArts Repository Ecosystem Audit

Audit date: 2026-08-16

## Executive finding

The AvatarArts repositories already contain the foundations of a creator-to-IP studio. The missing layer was a public, rights-aware orchestration model explaining how the systems relate and how a story moves from canon to publishable formats.

Creator Camp is now that public operating layer. It should not duplicate every implementation repository.

## High-value repositories

| Repository | Observed role | Reusable capability | Creator Camp action |
|---|---|---|---|
| choTaku | Provider-neutral storyworld compiler | Typed entities, graphs, timelines, scene contracts, provenance, layout, reader state, rights records | Semantic and production-contract reference implementation |
| chozen-land | Narrative reality engine | Context to meaning to canon to graph to narrative to artifacts; YAML schemas; exports | Authoring ontology and format projection reference |
| ai-comic-factory | AI comic renderer | Story continuation, panel instructions, speech/caption fields, layout selection, degraded fallback | Rendering adapter pattern; never the canon source |
| AVATARARTS | Large creative archive | Research, prompts, visual assets, indexing, websites, experiments | Mine through inventories and provenance; do not copy wholesale |
| open-design | Visual production environment | Storytelling design system, prompt templates, media contracts, visual QA, publishing workflows | Borrow design-system and template concepts |
| nocTurneMeLoDieS | Music and cross-media catalog | Audio organization, metadata, distribution, monetization, content pipelines | Soundtracks, opening themes, audiobooks, trailers |
| my-supremepowers | Agent and ecosystem OS | Roles, governance, capability atlas, handoffs, consolidation, validation | Governance source, not direct story dependency |

## Supporting repositories

- AvaTar-ArTs.github.io, AvaTarArTs.org, and tehSite: public presentation and portfolio surfaces.
- ESO and ESO-Build-Alley: reference or derivative material; isolate from original commercial canon.
- xEo-Empire, adventure_guild, and related lore repositories: candidate world seeds requiring canon and rights classification.
- gumroad, PYTHON_MARKETPLACE_MASTER, and PYTHON_MARKET: productization and direct-sales references.
- AutoTagger, obsidian-image-upload-toolkit, notebooklm-mine, and Ai-Chat-Exporter: asset intelligence and ingestion substrates.

## Findings

1. choTaku has the strongest semantic and production-contract foundation.
2. chozen-land already models universe, characters, relationships, lore, scenes, stories, shots, and artifacts.
3. ai-comic-factory demonstrates that rendering needs a provider boundary and a degraded mode.
4. AVATARARTS is a source reservoir, not one publishable product.
5. Originality boundaries must separate original IP, research studies, fan material, and technical substrates.
6. Cross-media outputs should be projections from one approved canon, not disconnected prompt sessions.

## Priority integration order

1. choTaku contracts and validators
2. chozen-land ontology and story workflow
3. Creator Camp publishing and submission workflow
4. AVATARARTS inventory and provenance ingestion
5. ai-comic-factory rendering adapter
6. open-design visual templates and QA
7. nocTurneMeLoDieS audio projection
8. agent and governance automation from my-supremepowers

## Non-goals

- Copying entire repositories into Creator Camp
- Treating generated images as canon without approval
- Treating a prompt as a complete rights record
- Replacing specialized implementations with documentation alone
- Publishing derivative or ambiguous material as original IP
