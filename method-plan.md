# Hermes Skill Plan — Novel Forge (derived from wish novel workflow)

## Goal
Create a hackathon-ready Hermes skill that takes a user idea, asks a focused intake questionnaire, collaborates through iterative feedback, and produces a complete novel package with planning artifacts, chapter drafts, continuity checks, visual summaries, and final compiled manuscript.

## Source method extracted from this folder
Observed pipeline in this project:
1) Core concept docs (`book-bible`, `series-outline`, `beat-sheet`)
2) Per-chapter prep (`chapter-XX-scene-outline`, `chapter-XX-drafting-blueprint`)
3) Drafting outputs (`chapter-XX-draft-vN`)
4) Humanization pass (`chapter-XX-draft-vN-humanized`)
5) Continuity protocol + transition logging (`continuity-log`, `chapter-cohesion-protocol`)
6) Global audits (cohesion audit, character arc closure, cast/name/dialogue consistency)
7) Polish waves (v2 line-level, v2.1 micro-pass, naming/motif passes)
8) Final packaging (full manuscript, reader file, epub)

## Distinctive creative method to preserve in skill
- Engineering-first story architecture (theme -> structure -> scenes -> prose)
- Hard canon constraints and naming protocols
- Backward + forward chapter cohesion requirements
- Scene causality test and irreversible-pressure rule per chapter
- Separate prose-quality pass (humanization) from planning artifacts
- Audit-driven iteration before final compile

## Required upgrades (from user feedback)
- Genre-agnostic and arc-agnostic (not anti-hero-specific)
- Suggestive co-creation mode:
  - character options
  - event ladders
  - relationship dynamics
  - symbolism systems
  - foreshadow/payoff strategies
- Built-in revision loops after each phase
- Organized outputs that are easy to follow
- Visual planning artifacts (tables/charts/slide/infographic specs)

## Skill product shape
Skill name candidate: `novel-forge-complete`
Category: `creative`

Primary promise:
- User gives idea
- Hermes asks 10-14 high-impact questions
- Hermes proposes options and co-designs decisions
- Hermes generates full novel package end-to-end
- User can revise at phase boundaries before lock

## Intake questions (quality-focused)
1. Premise (1-2 lines)
2. Genre + audience
3. Tone + emotional aftertaste
4. Theme + optional anti-theme
5. Ending mode
6. POV strategy
7. Length/chapter target
8. Must-include elements
9. Must-avoid elements
10. Character + relationship priorities
11. Symbolism/motif preferences
12. Foreshadowing intensity
13. Style references + style no-go list
14. Content boundaries

## Skill workflow design (phased)
Phase 1: Thesis lock
- Premise, theme, anti-theme(optional), central question, reader promise

Phase 2: Character + relationship engine
- Want/need/wound/fear + arc path + relationship matrix

Phase 3: Global structure
- Act map + chapter spine + event escalation ladder

Phase 4: Beat + symbolism matrix
- Beat cards and symbol/foreshadow placement map

Phase 5: Chapter blueprinting
- Scene outline + word budget + must show/avoid + foreshadow/symbol targets

Phase 6: Drafting loop
- Write chapter draft
- Humanization pass (prose only)
- Continuity pass against previous/next anchors
- Log transition outcomes
- User feedback + revision integration

Phase 7: Audit loop
- Cohesion audit
- Arc closure audit
- Terminology/name/style consistency audit
- Symbolism coherence + setup/payoff closure audit
- Fixes propagated to affected chapters

Phase 8: Finalize
- Full manuscript
- Reader edition
- Optional EPUB-ready markdown package

## Deliverable files the skill should emit
- Planning/book-bible.md
- Planning/series-outline.md
- Planning/beat-sheet.md
- Planning/character-relationship-matrix.md
- Planning/chapter-spine-table.md
- Planning/foreshadow-payoff-ledger.md
- Planning/tension-curve-chart.md
- Planning/story-deck-slides.md
- Planning/chapter-XX-scene-outline.md
- Planning/chapter-XX-drafting-blueprint.md
- Planning/continuity-log.md
- Planning/cohesion-audit.md
- Planning/character-arc-closure-audit.md
- Planning/symbolism-coherence-audit.md
- Planning/revision-log.md
- Drafts/chapter-XX-draft-v1.md
- Drafts/chapter-XX-draft-v1-humanized.md
- Drafts/<title>-manuscript-v1.md

## Visual output standards
At each major phase, include one or more:
- table
- ascii/text chart
- slide-style outline
- infographic spec (content/layout instructions)

## Quality gates (must pass)
- Every chapter has causal turn/reversal
- Every chapter ending creates pressure for next chapter
- Midpoint changes strategy, not just stakes
- Character end-truths are shown in behavior
- Foreshadow seeds have payoff status
- No canon drift introduced by prose polishing

## Hackathon submission structure
1) Skill file (`SKILL.md`) with trigger, workflow, prompts, pitfalls
2) Example transcript (idea -> intake -> collaboration -> revisions -> output)
3) Visual artifact pack (tables/charts/slides)
4) Before/after chapter sample (raw vs humanized)
5) Quality-gate checklist + audit evidence

## Next step
Run one complete demo project with this revised skill and package outputs as the official submission bundle.