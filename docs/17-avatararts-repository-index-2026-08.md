# AvaTar-ArTs repository index

_Last inventory refresh: 2026-08-16._

This index covers all 101 repositories visible on the AvaTar-ArTs profile, including Creator Camp. The complete row-level inventory is in [avatararts-repository-index.csv](../templates/avatararts-repository-index.csv).

## Portfolio shape

| Area | Count |
|---|---:|
| Creator/IP and production | 19 |
| Agent/AI infrastructure | 35 |
| Automation/platform tools | 26 |
| Business/commerce | 12 |
| Reference/upstream | 5 |
| Unclassified/archive candidates | 4 |
| **Total** | **101** |

Priority distribution: **P3** 31 · **P1** 10 · **P2** 53 · **P0** 7

## Canonical creator/IP spine

`AVATARARTS` archive → `chozen-land` meaning/canon → `choTaku` structured storyworld → `creator-camp` publishing/production ops → `ai-comic-factory` comic realization → `open-design` visual production → `nocTurneMeLoDieS` audio/distribution.

Supporting governance and automation come from `my-supremepowers`, `agent-skills`, `.Agent-skills`, and the surrounding tool repositories.

## Audit interpretation

- **Profile** means inventory-level evidence: name, URL, branch, size signal, archive flag, and classification.
- **Deep** means file-tree/content inspection performed for repositories directly affecting the creator/IP, storyworld, comics, media, agents, or publishing system.
- A classification is an operating hypothesis, not a rights determination. Repository ownership alone does not prove ownership of contained art, text, music, models, datasets, or upstream code.

## Key findings

1. The profile is a portfolio: original IP, archives, prototypes, upstream projects, agent runtimes, personal tooling, and commerce infrastructure are mixed together.
2. `creator-camp` should stay the public orchestration layer and link to other repositories through explicit contracts rather than absorbing their codebases.
3. `agent-skills` is the canonical reusable skill/runtime layer; treat `.Agent-skills` as a mirror/snapshot until proven otherwise.
4. `AVATARARTS` is the major archive source and needs project, canon, rights, and provenance triage before public reuse.
5. Empty/tiny repositories need explicit statuses—active, incubating, reference, archived, or superseded—so they do not imply production readiness.
6. Forks and upstream-derived projects need visible attribution boundaries from authored IP.

## P0 focus

- **creator-camp** — maintain the operating system, index, contracts, trackers, and launch plans.
- **AVATARARTS** — begin archive triage and provenance extraction.
- **chozen-land** — formalize ontology → canon → graph → narrative exports.
- **choTaku** — stabilize typed storyworld and production contracts.
- **ai-comic-factory** — define comic-generation and QA handoffs.
- **agent-skills** — keep reusable agent workflows canonical.
- **my-supremepowers** — extract governance patterns without coupling internal orchestration to public IP.

See [the audit method](18-avatararts-repository-audit-method.md) and [the action queue](19-repository-action-queue.md).
