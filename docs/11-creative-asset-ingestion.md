# Creative Asset Ingestion and Provenance

## Why ingestion is needed

The AvatarArts archive contains prompts, images, HTML pages, stories, music, research notes, and experiments. Moving files directly into a new repository would create duplication, unclear ownership, and hidden derivative material.

The correct operation is evidence-bounded ingestion.

## Stages

Inventory → classify → fingerprint → deduplicate → rights review → canon candidate → human approval → publishable asset

## Classification buckets

### Original canon candidate

Created by Steven or collaborators with a documented origin and no unresolved third-party dependency.

### Original experiment

Useful creative research, but not yet part of an approved universe.

### Reference study

Analysis of existing anime, games, manga, artists, or commercial systems. Keep for learning; do not present as original IP.

### Derivative or fan material

Explicitly label and isolate. Do not use as the commercial source for an original adaptation pitch.

### Technical substrate

Code, templates, automation, renderers, indexing tools, prompt systems, and UI infrastructure.

### Unresolved

Requires a rights, identity, authorship, or source decision.

## Required asset record

- Stable asset ID
- Source repository and path
- Source commit
- Asset type
- Project or universe
- Creator
- Creation date if known
- Tool/provider
- Human contribution
- Third-party material
- License/terms
- Derivative status
- Canon status
- Target formats
- Supersedes relationship
- Review status

## Recommended IDs

IP-slug, CHAR-slug, LOC-slug, LORE-slug, SCENE-slug, ART-slug, AUDIO-slug, PROMPT-slug, LAYOUT-slug, RELEASE-slug.

## First extraction priorities

1. choTaku examples and layout fixtures
2. chozen-land canon, stories, schemas, and exports
3. Original curse and choosing concepts
4. Comic and manga prompt systems
5. Storyboard and layout contracts
6. Visual-language research
7. Character portrait and lore-driven assets
8. Music-to-storyboard systems
9. Portfolio and marketplace documentation

Defer broad ingestion of client work, unrelated business sites, raw archives, and duplicated generated exports.

An asset cannot enter an adaptation package until its source, third-party material, commercial terms, originality status, human contribution, owner, and version are documented.
