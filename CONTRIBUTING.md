# Contributing to the formalization plan

The goal is a faithful Lean proof of IUT III, Theorem 3.11, built on libraries that are useful independently. This repository currently contains the plan. A checked box is a documented milestone, not evidence that the corresponding Lean theorem already exists.

## Choose an output, not a whole book

Start with the [parallel roadmap](plan/roadmap.md) and choose a numbered deliverable in a [work package](work-packages/README.md). Identify the source result, required hypotheses, exported types, theorem signature, consumers and relevant mathlib imports. Small general-purpose results should be contributed upstream where appropriate; specialized reconstruction and IUT layers can remain separate libraries.

**★ REUSABLE** means a result/API has concrete uses beyond IUT. **◇ IUT SUPPORT** means specialized categorical or reconstruction infrastructure with possible wider use. **IUT SPECIFIC** means a construction or compatibility assertion belonging to the IUT assembly. These are value labels, not proof-status labels.

## Dependency discipline

Every graph arrow is **prerequisite → consumer**. A source card selects parts of a paper/book; it does not require completing the whole text first. Canonical replacement sources are alternatives, not additional mandatory proofs. The [interface guide](plan/interfaces.md) distinguishes early definitions, theorem statements and completed proofs.

Keep three different records:

1. **Evidence:** an exact source statement, caller reference, background implementation need or proposed alternative.
2. **Scheduling:** the output a consumer needs, rather than every result in the source paper.
3. **Proof status:** source selected → precise Lean statement → proof complete → independent review → integrated.

An earlier paper may contain several independent outputs, and a later exposition may provide a better proof of an earlier standard result. Publication order is not the formalization order. Source-level diagrams are summaries; the [output graph](graphs/work-packages.md) resolves staged exports and apparent cycles.

## What counts as complete

A result is integrated only when:

- Its genuine mathematical objects and hypotheses are defined and matched to the chosen source version, including corrections.
- Its Lean proof compiles in a reproducible pinned environment without `sorry`, extra mathematical axioms, or unproved interface laws in the final dependency closure. Ordinary Lean foundations such as choice/propositional extensionality/quotient soundness are recorded separately from added mathematical assumptions.
- Any abstract interface has a proved interpretation in the geometric, arithmetic or categorical objects it claims to model.
- Conjugacy, basepoint, automorphism, topology, saturation, inverse-limit and normalization choices are tracked explicitly.
- Its downstream examples exercise the actual exported statement; an independent reviewer checks scope and source fidelity.

Consumers may develop conditionally against an agreed theorem signature while another team proves it. Such branches remain conditional until the hypotheses are discharged by the actual package output. Do not make a desired reconstruction or compatibility assertion a structure field and then report its projection as the theorem's proof.

## Keep the plan coherent

For a new or changed target, update its source card, package card, relevant graph/table, [coverage checklist](tracking/coverage.md) and [audit gates](tracking/audit-gates.md). Name the exact result and edition rather than writing “standard” or “all of SGA.” Resolve source-number mismatches by matching statements and proofs, not by silently renumbering the caller.

Markdown links must work on GitHub. Mermaid labels should be short and quoted; split large graphs into readable panels. Do not add local filesystem links, private research paths, copied copyrighted papers, or generated build directories. The plan is maintained in Markdown; future Lean implementations may live in linked repositories.

[Home](README.md) · [First assignments](plan/roadmap.md#first-parallel-assignments) · [Reusable results](plan/reusable-results.md)
