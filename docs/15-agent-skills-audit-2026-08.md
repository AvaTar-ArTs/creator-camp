# agent-skills Repository Audit

Audit date: 2026-08-16

Repository: https://github.com/AvaTar-ArTs/agent-skills

## Executive finding

agent-skills is the strongest candidate for the canonical reusable-agent and skill runtime. It is not a story repository and should not be merged wholesale into Creator Camp. Creator Camp should consume its capabilities through a documented capability map and selected production-facing adapters.

## Current tree snapshot

The current GitHub tree contains:

| Measure | Observed |
|---|---:|
| Total tracked files | 1,161 |
| SKILL.md files | 186 |
| Top-level skill directories | 96 |
| Agent/config files under agents | 199 |
| Root agent/config files | 102 |
| Root index/manifest/audit artifacts | multiple |
| Special runtime/reference material | .system, dist, skill-porter-examples, histories |

The repository README and INDEX describe the canonical local runtime and its symlink expectations. The current tree is consistent with the documented 186 expanded skills, but runtime counts should be regenerated rather than trusted indefinitely.

## Primary structure

### agents/

The agent catalog has five major organization buckets:

- 1-eng-specialist-pack: engineering specialists
- 2-personal-tooled: personal operating and coordination agents
- 3-contains-studio: creator, growth, social, production, and business agents
- 5-misc-personal: ecosystem, organization, memory, and personal workflow agents
- root agents: runtime-primary definitions
- supporting skill-creator, skill-installer, skill-porter, command, documentation, and Gemini role material

The root agent surface is especially important because the repository states that root agent files are the runtime primary surface while categorized copies are retained for organization.

### skills/

The skill catalog spans:

- narrative and writing
- creative and visual production
- research and documentation
- ecosystem intelligence and navigation
- agents, MCP, plugins, and tool integration
- software, data, DevOps, and ML
- publishing, social, productivity, and platform access
- self-evolution, memory, validation, and governance

## Creator Camp-relevant capability clusters

| Cluster | Relevant skills/agents | Creator Camp use |
|---|---|---|
| Story and narrative | narrative-blueprints, narrative-documentation, writing-skills, visual-storyteller | pitch, prose, manga, world and adaptation documents |
| Research | research, find-docs, workspace-ecosystem-audit, ecosystem-intelligence | source ledger, rights review, repository audit, market research |
| Visual production | creative, media, sora, frontend-design, design-taste-frontend | art direction, storyboards, visual references, launch assets |
| Workflow | workflow-bootstrap, dispatching-parallel-agents, executing-plans, workflow-orchestrator | production scheduling and handoffs |
| Quality | verification-before-completion, red-teaming, receiving-code-review, test-results-analyzer | release gates and artifact review |
| Ecosystem | capability-atlas, ecosystem-clarity, ecosystem-navigation, self-improvement | map skills to projects without duplicating systems |
| Publishing and growth | narrative-blueprints, social-media, growth-hacker, project-launch-manager, studio-producer | launch, audience, platform release, submissions |
| Tool integration | github, mcp, build-mcp-app, build-mcp-server, plugin-structure | future Creator Camp automation and connectors |

## Important risks

### Duplicate active surfaces

Root agents and categorized agent copies can drift. The repository already documents root files as runtime-primary. Any consolidation must update the manifest and preserve the canonical path.

### Mirror ambiguity

.agent-skills and agent-skills share 1,046 tracked paths in the current comparison. agent-skills has additional runtime history, audit reports, system/vendor material, scripts, and skills. Treat .Agent-skills as a mirror or historical snapshot unless proven otherwise.

### Vendored/reference content

.skills/.system, skills/skill-porter-examples, dist, and related files should not be counted as authored project capabilities without classification.

### Stale inventory

Counts in README, INDEX, manifests, and generated audits can disagree after additions. A repeatable tree inventory should be the source of truth.

### Sensitive runtime material

Notebook backups, account documentation, session exports, authentication notes, memory exports, and environment-specific scripts require a non-publicity review before they are copied or exposed through Creator Camp.

### Over-broad skill selection

Creator Camp should use a small production profile rather than loading the entire catalog for every story task.

## Recommended runtime profiles

### Creator Camp authoring profile

- research
- narrative-blueprints
- narrative-documentation
- capability-atlas
- ecosystem-intelligence
- writing-skills
- verification-before-completion

### Comic and manga production profile

- creative
- media
- sora
- visual-storyteller
- design-taste-frontend
- frontend-design
- verification-before-completion

### Release and business profile

- project-launch-manager
- studio-producer
- growth-hacker
- social-media
- github
- project-shipper
- receiving-code-review

### System audit profile

- workspace-ecosystem-audit
- ecosystem-navigation
- ecosystem-analyzer agent
- filesystem-inventory agent
- path-list-analyzer agent
- content-organizer agent
- legal-compliance-checker agent

## Verdict

agent-skills should remain the canonical runtime skill library. Creator Camp should reference it, profile it, and build story-production workflows around selected capabilities. Do not copy the entire repository into Creator Camp.
