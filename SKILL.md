---
name: novel-forge-complete
description: Turn a single story idea into a complete, collaborative novel package using an adaptive outline->blueprint->draft->revision->audit pipeline with visual planning artifacts.
version: 0.2.1
author: Hermes Agent + Ghost
license: MIT
metadata:
  hermes:
    tags: [creative-writing, novel, story-architecture, drafting, revision, continuity, collaboration, visual-planning]
    category: creative
---

# Novel Forge Complete

Use this skill when a user wants a full novel and a collaborative writing partner, not just a one-shot outline.

Core contract:
1) Ask focused intake questions first.
2) Co-design story options with the user (characters/events/relationships/symbolism/foreshadowing).
3) Build organized planning artifacts before prose drafting.
4) Draft chapter-by-chapter with continuity constraints.
5) Run iterative feedback/revision loops at every major phase.
6) Audit cohesion/arc closure before final manuscript.

## Collaboration mode (required)
Treat this as a writers-room collaboration.
- Always provide options (A/B/C) before locking key decisions.
- Explicitly ask for user preference at phase boundaries.
- Accept revision notes and propagate changes across all dependent artifacts.
- Keep a change log so revisions are traceable and easy to review.

## Intake protocol (ask before writing)
Ask 10-14 concise questions:
1. Working premise in 1-2 sentences
2. Genre + target audience
3. Tone + emotional aftertaste
4. Theme + anti-theme (or “no anti-theme” if user prefers)
5. Ending mode (tragic/cautionary/redemptive/ambiguous/open)
6. POV mode (single/dual/rotating/experimental)
7. Length/chapter target
8. Must-include elements (3-5)
9. Must-avoid elements (3-5)
10. Character/relationship priorities
11. Symbolism and motif preferences (objects/colors/rituals/recurring imagery)
12. Foreshadow intensity preference (light/moderate/heavy)
13. Style references + explicit no-go style traits
14. Content boundaries (violence/sexuality/language)

If user skips details, proceed with explicit defaults and state assumptions.

## Adaptive story architecture (genre-agnostic)
Do not assume anti-hero arcs. Offer selectable arc frameworks:
- Hero’s journey
- Ensemble braid
- Tragedy descent
- Mystery reveal lattice
- Romance dual-transformation
- Anti-hero spiral
- Slice-of-life growth

Also suggest:
- candidate character archetypes
- high-leverage event ladders
- relationship dynamics matrix
- symbol systems and motif cadence
- foreshadow/payoff strategy options

## Project size tiers + long-project mode
Use these tiers explicitly at intake:
- Novella: 20k-50k words, 8-14 chapters
- Standard novel: 60k-110k words, 14-28 chapters
- Epic novel: 120k-220k words, 28-60 chapters
- Series mode: 2+ volumes, each planned as its own full pipeline

If user says “you choose,” default to Standard novel.

For Epic/Series mode, enforce long-project mode:
- Plan and draft in batches (by act or 3-5 chapters)
- Run continuity + loose-end scans at each batch boundary
- Maintain a canonical state index that is updated after every batch

## Default assumptions (if user says “you choose”)
- Standard novel tier (60k-110k words)
- 14-18 chapters
- 3-act or 4-part structure (choose best fit for genre)
- 3-6 scenes/chapter
- close third POV unless genre favors alternative
- bittersweet or redemptive ending
- prose target: concrete, emotionally specific, minimal abstraction bloat

## Phase workflow

### Phase 1: Thesis lock
Output:
- premise
- theme
- anti-theme (optional)
- moral/transformational question
- reader promise
- ending mode

### Phase 2: Character + relationship engine
For each core character define:
- want, need, lie (optional), wound, fear
- arc start -> midpoint -> end truth
- relationship edges: trust, power, attraction, conflict, dependency

### Phase 3: Global structure
Produce:
- act map
- chapter spine (purpose/conflict/turn/exit hook per chapter)
- midpoint reversal, point-of-no-return, dark night, climax decision
- event escalation ladder

### Phase 4: Beat matrix + symbolism map
For each chapter define beats with:
- objective
- obstacle
- choice
- consequence
- tags: foreshadow/payoff/twist-seed/arc-shift/symbol-beat

### Phase 5: Chapter blueprinting
For each chapter create a drafting blueprint:
- target word range
- scene-by-scene goals
- must show vs must avoid
- tone/rhythm notes
- foreshadow phrase targets
- symbolism insert points
- revision checklist

### Phase 6: Drafting loop
For each chapter:
1. Write `chapter-XX-draft-v1.md`
2. Humanize prose only -> `chapter-XX-draft-v1-humanized.md`
3. Continuity check against previous/next chapter anchors
4. Log decisions in continuity log
5. Ask user for notes and apply revision if requested

### Phase 7: Audit loop
Run and fix:
- cohesion audit (outline vs manuscript alignment)
- character arc closure audit
- terminology/name/voice consistency pass
- setup/payoff orphan scan
- symbolism coherence audit
- continuity scan (timeline, causality, location/state consistency)
- unresolved thread scan (open promises, missing payoffs, dangling reveals)

Continuity scan protocol:
1. Backward scan: chapter N must honor consequences from N-1
2. Forward scan: chapter N ending must launch pressure into N+1
3. Canon scan: names/terms/rules/timelines remain stable unless explicitly retconned
4. Causality scan: each scene decision should cause downstream change

Loose-end protocol for final chapters:
- Create `Planning/loose-ends-register.md` by midpoint
- Track each thread: seed chapter, owner character, expected payoff window, status
- In final 20% of chapters, run closure pass and mark each thread as:
  - closed on-page
  - intentionally open (sequel hook)
  - merged into another resolved thread
- No accidental dangling high-stakes thread at finalization

### Phase 8: Finalization
Generate:
- full manuscript markdown
- reader edition markdown
- revision log
- optional EPUB-ready package notes

## Visual/organized outputs (required)
At each major phase, include at least one of these:
- Tables (cast matrix, chapter spine, beat map, foreshadow ledger)
- Text charts (arc progression chart, tension curve chart)
- Slide-style outline (10-15 slide equivalent in markdown)
- Infographic spec sheets (data + layout instructions for later rendering)

Minimum visual artifacts:
- `Planning/character-relationship-matrix.md` (table)
- `Planning/chapter-spine-table.md` (table)
- `Planning/foreshadow-payoff-ledger.md` (table)
- `Planning/tension-curve-chart.md` (ASCII/text chart)
- `Planning/story-deck-slides.md` (slide outline)

## Feedback + revision protocol (required)
After each phase:
1) summarize decisions in 5-10 bullets
2) present revision options: keep / tweak / regenerate
3) if revised, update dependent artifacts immediately
4) append change notes to `Planning/revision-log.md`

## Hard quality gates (must pass before “complete”)
- Every chapter has a causal turn/reversal
- Every chapter back half contains at least one meaningful commitment/irreversible pressure
- Every chapter ending creates next-chapter pressure
- Midpoint changes strategy, not only stakes
- Climax resolves the central question through action
- Character end-truths shown behaviorally
- Foreshadow seeds have tracked payoff status
- Continuity scans pass (timeline/causality/canon)
- Loose-end register resolved: all high-stakes threads are closed or explicitly intentional sequel hooks
- Humanization introduces zero canon drift

## Anti-drift rules
- Never humanize planning artifacts (outlines, beat sheets, blueprints, checklists)
- Preserve plot facts, chronology, and terminology during prose polish
- Maintain naming/voice protocols once established

## Suggested artifact tree
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
- Planning/continuity-scan-report.md
- Planning/loose-ends-register.md
- Planning/loose-ends-closure-report.md
- Planning/cohesion-audit.md
- Planning/character-arc-closure-audit.md
- Planning/symbolism-coherence-audit.md
- Planning/revision-log.md
- Drafts/chapter-XX-draft-v1.md
- Drafts/chapter-XX-draft-v1-humanized.md
- Drafts/<title>-manuscript-v1.md

## Failure handling
If quality gates fail:
1. Identify exact failing chapters/scenes/artifacts
2. Patch only affected artifacts
3. Re-run relevant audits
4. Only then regenerate final manuscript

## Quick-start execution prompt
“Use Novel Forge Complete. I’ll give a premise. Ask your intake questions, propose options for characters/events/relationships/symbolism/foreshadowing, and collaborate with me phase-by-phase. Keep outputs organized with tables/charts/slide-style summaries and support revision loops before final manuscript package.”
