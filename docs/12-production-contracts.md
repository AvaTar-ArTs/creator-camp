# Production Contract Adoption

This translates the strongest choTaku contracts into Creator Camp requirements.

## Identity memory

Every recurring character needs approved visual anchors and negative anchors.

Example:
id: char-crimson-curse-master-v1
character_id: crimson-curse-master
status: approved
visual_anchors: scarlet sigil scars; blackened fingertips; one eye reflecting ritual light
negative_anchors: modern school uniform; unrelated franchise symbols; inconsistent eye color

## Reader state

Each scene records:

- What the reader already knows
- What the scene newly reveals
- What remains unresolved

This protects mystery pacing across prose, manga, and animation.

## Rights record

Every storyworld entity and output carries:

- Ownership basis
- Source references
- Restrictions
- Commercial status
- Review notes

## Layout contract

A page or webtoon episode declares:

- Dimensions
- Reading direction
- Panels or slots
- Cell roles
- Reading order
- Gutter rhythm
- Typography
- Balloon styles
- SFX
- Safe margins
- Overflow policy
- Prompt manifest

## Render checkpoint

Long jobs should be resumable through:

- Stage
- Total units
- Completed units
- Remaining units
- Output IDs
- Attempt number
- Last error

A failed provider call must not require rebuilding the entire book.

## Validation gates

1. Required entities exist.
2. Reading order is unique and contiguous.
3. Dialogue has speaker and target anchor where required.
4. Text fits its region.
5. Focal cells are intentional.
6. Visual anchors match approved identity memory.
7. Rights records are clear or explicitly unresolved.
8. Provenance links sources, prompts, provider, and outputs.
9. Release metadata matches the actual edition.

These contracts make the system suitable for a serialized IP rather than disconnected prompt outputs.
