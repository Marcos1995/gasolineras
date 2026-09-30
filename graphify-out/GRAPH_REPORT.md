# Graph Report - gasolineras  (2026-09-30)

## Corpus Check
- 13 files · ~4,741 words
- Verdict: corpus is large enough that graph structure adds value.
- Unclassified: 2 file(s) not represented in the graph (top: .mdc 2)

## Summary
- 50 nodes · 37 edges · 13 communities (9 shown, 4 thin omitted)
- Extraction: 100% EXTRACTED · 0% INFERRED · 0% AMBIGUOUS
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- Debug
- Contexto del proyecto
- Verify (UI)
- Web design
- Agent rules
- Build judgments with Laya
- Laya
- Review
- Project
- DESIGN.md
- DECISIONES.md

## God Nodes (most connected - your core abstractions)
1. `Debug` - 6 edges
2. `Contexto del proyecto` - 6 edges
3. `Verify (UI)` - 4 edges
4. `Web design` - 4 edges
5. `Build judgments with Laya` - 3 edges
6. `Laya` - 3 edges
7. `Review` - 3 edges
8. `Agent rules` - 3 edges
9. `Project` - 3 edges
10. `1. Root cause` - 1 edges

## Surprising Connections (you probably didn't know these)
- None detected - all connections are within the same source files.

## Communities (13 total, 4 thin omitted)

### Community 0 - "Debug"
Cohesion: 0.29
Nodes (6): 1. Root cause, 2. Compare, 3. Hypothesis, 4. Fix, Debug, Red flags → back to step 1

### Community 1 - "Contexto del proyecto"
Cohesion: 0.29
Nodes (6): Comandos utiles, Contexto del proyecto, Estado, Notas para el agente, Produccion, Stack

### Community 2 - "Verify (UI)"
Cohesion: 0.40
Nodes (4): 1. Screenshots, 2. Look, 3. Fix and repeat, Verify (UI)

### Community 3 - "Web design"
Cohesion: 0.40
Nodes (4): Before HECHO, Steps, Style = `DESIGN.md`, Web design

### Community 4 - "Agent rules"
Cohesion: 0.50
Nodes (3): Agent rules, Flujo, Think → Simple → Surgical → Verify (Karpathy)

### Community 5 - "Build judgments with Laya"
Cohesion: 0.50
Nodes (3): Build judgments with Laya, Call, Design

### Community 6 - "Laya"
Cohesion: 0.50
Nodes (3): Laya, Reply (decision-only requests), Steps

### Community 7 - "Review"
Cohesion: 0.50
Nodes (3): Check, Do, Review

### Community 8 - "Project"
Cohesion: 0.50
Nodes (3): Docs, Project, Setup

## Knowledge Gaps
- **28 isolated node(s):** `1. Root cause`, `2. Compare`, `3. Hypothesis`, `4. Fix`, `Red flags → back to step 1` (+23 more)
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 41 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)
- **4 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **What connects `1. Root cause`, `2. Compare`, `3. Hypothesis` to the rest of the system?**
  _28 weakly-connected nodes found - possible documentation gaps or missing edges._