# Creator Camp Integration Architecture

## Repository boundaries

Creator Camp is the coordination layer. Specialized repositories retain implementation ownership.

Research and archive:
AVATARARTS, Ai-Chat-Exporter, notebooklm-mine, AutoTagger

Canon authoring:
chozen-land

Semantic compilation and contracts:
choTaku

Creator workflow and release planning:
creator-camp

Rendering and presentation:
ai-comic-factory, open-design, visual providers

Distribution:
KDP, Kobo, GlobalComix, WEBTOON, Tapas, owned site

Adaptation:
manga, light novel, audio, motion comic, anime/TV package

## Canon objects

A minimum interoperable storyworld record should carry:

- id
- title
- logline
- themes
- characters
- locations
- lore
- evidence
- relationships
- events
- scene_contracts
- sources
- rights_records
- status
- version

## Semantic-to-render map

| Object | Story function | Output surfaces |
|---|---|---|
| Character | identity, goals, fears, wounds, contradictions, visual anchors | prose, manga, audio, animation |
| Location | spatial and sensory continuity | prose, panels, backgrounds, shots |
| Lore | rules, history, symbols, systems | glossary, dialogue, pitch bible |
| Relationship | tension, alliance, betrayal, dependency | scenes, chapters, character art |
| Event | causal change | timeline, pages, episodes |
| Scene contract | purpose, emotional turn, required evidence | prose, manga, storyboard |
| Artifact plan | layout and render instructions | comic, webtoon, video |
| Rights record | commercial clearance | every public output |

## Data flow

1. Import research and creative intent.
2. Separate observation, interpretation, and proposal.
3. Promote approved proposals into canon.
4. Validate identity, continuity, rights, and reading order.
5. Compile artifact plans.
6. Render through replaceable providers.
7. Review output against the contract.
8. Package for serialization, publication, or adaptation.
9. Record release evidence and superseded versions.

Providers must not silently change character identity, canon facts, event order, dialogue attribution, reading direction, rights status, required anchors, or adaptation scope.

## Suggested project layout

projects/<ip-id>/
  canon/
  research/
  characters/
  lore/
  scenes/
  stories/
  artifacts/
  rights/
  releases/
  adaptation/

Creator Camp owns templates and workflow. choTaku and chozen-land remain executable engines.
