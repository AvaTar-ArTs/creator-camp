# AvaTar-ArTs repository audit method

## Purpose

Make the GitHub portfolio legible to collaborators, contest judges, publishers, and production partners: original IP, infrastructure, experiments, and upstream/reference material should be distinguishable.

## Audit layers

| Layer | Checks | Output |
|---|---|---|
| Profile inventory | name, URL, branch, size, archive flag, update signal | one CSV row per repository |
| File-tree audit | top-level directories, README, manifests, skills, schemas, tests, assets, workflows | deep audit notes |
| Content audit | contracts, provenance, licenses, public/private boundary, runnable path, release artifact | risk and action notes |
| Integration audit | upstream/downstream role, handoff format, owner, validation, publication boundary | Creator Camp contract |

## Classification rules

- **creator-ip**: worlds, characters, art, comics, games, music, or production design.
- **agent-ai**: agents, skills, model tooling, research assistants, or AI runtime systems.
- **automation-platform**: personal productivity, integrations, scripts, repository, and developer utilities.
- **business-commerce**: products, marketplaces, analytics, jobs, websites, and monetization.
- **reference-upstream**: forks, copied upstream projects, courses, or external foundations.
- **unclassified**: requires a deliberate status decision.

## Risk labels

Apply these during deeper audits: **rights/provenance**, **canon drift**, **contract gap**, **operational drift**, **public-boundary**, and **production gap**.

## Refresh policy

Refresh the profile index monthly or after a repository creation/rename. Deep-audit P0 repositories whenever their public contract changes, P1 repositories before publication/submission, and P2/P3 repositories during quarterly consolidation. Never infer rights ownership from repository ownership alone; record source and permissions in the provenance register.

A **profile** row is inventory evidence plus a recommended next action. A **deep** row reflects repository inspection performed in the current Creator Camp build cycle.
