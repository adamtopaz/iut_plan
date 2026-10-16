# Independent review: anabelian sources and parallel schedule

**Reviewer:** an agent distinct from the anabelian-source author. **Scope:** all anabelian source cards, package cards P12–P21/P27–P28, roadmap, interfaces, clause matrix, audit gates and coverage. This is a source-fidelity and planning review, not a Lean proof verification or an exhaustive recursive closure certificate.

The review looked for wrong map classes, lost correction hypotheses, implicit field-reconstruction assumptions and circular proof scheduling. Findings were sent to the integrator before final graph construction. No reviewed file was edited by the reviewer.

## Concrete findings

| ID | Finding and scope | Requested resolution / disposition |
|---|---|---|
| AS01 | The Isom-only optimization has additional named inputs. Galois Sections Remark 2.8.1 retains Proposition 1.1(ii) and Theorem 1.3(iii); an Isom theorem alone does not supply arithmetic-quotient and cusp recognition. The original source card did not list those targets explicitly. | Add the exact helper results and their corrected Absolute Anabelian Geometry dependencies to the retained source slice. Integrator accepted this addition. |
| AS02 | A first **finite-p-adic** Isom release covers a local branch, while AbsTop II/III also have number-field/sub-p-adic callers. The narrower field class must not silently discharge every chain-full relative-Isom premise. | Keep a consumer/field-class table under A06. Either prove the required broader Isom specialization or prove a localization/descent bridge. The printed theorem remains the baseline until this succeeds. This is a scope guard, not a finding that the optimization is impossible. |
| AS03 | P17 had an owned archimedean branch but only broad section-level source targets. That was less precise than the available source record. | Add AbsTop III Propositions 2.2, 2.5–2.6, Corollaries 2.3, 2.7–2.9, Proposition 4.2, Lemmas 4.3–4.4 and Corollary 4.5 as **selection targets**, with elliptically-admissible and number-field hypotheses where required. Integrator accepted the refinement. |
| AS04 | EtTh's corrected formal generic-fiber objects require their own interpretation/normalization proof; ordinary rigid/Berkovich analytification is not a definitionally interchangeable object. Further hypothesis corrections also affect the selected §2 constructions. | Integrator accepted explicit P08/P20 formal-model outputs and EGA/Faltings normalization source entries. Apply the correction attachment item by item; retain odd-ℓ, residue-characteristic and model-environment conditions at the actual clauses where used. |
| AS05 | Newly added P05.6/P06.5 rows were separated from their Markdown tables by blank lines. The larger P05 cohomology output also needs a staged release to preserve the proposed parallel curve work. | Remove table-breaking blank lines. The integrator accepted a P05 finite-cover core versus geometric-cohomology split; only the latter should be a barrier to the deep cohomological consumers. |
| AS06 | Some source cards use ◇ IUT SUPPORT where a package/reusable catalogue marks selected outputs ★ REUSABLE. This is defensible for specialized standalone theta/Frobenioid results, but the badge cannot mean every later shell/theater construction is a standard broadly useful theorem. | Read usefulness per export; retain the catalogue's explicit qualification for specialized theta/Frobenioid releases. This is a consistency recommendation, not a mathematical error. |

AS01 was checked against the [primary Galois Sections paper](https://www.kurims.kyoto-u.ac.jp/~motizuki/Galois%20Sections.pdf), author pp.5–6 and Remark 2.8.1. Its retained local theorem's premise includes an actual base-field embedding, not an arbitrary local Galois isomorphism.

AS04 is anchored by [EtTh's March 2022 comments](https://www.kurims.kyoto-u.ac.jp/~motizuki/The%20Etale%20Theta%20Function%20and%20its%20Frobenioid-theoretic%20Manifestations%20%28comments%29.pdf), especially items (v), (xliv)–(xlvi), printed pp.2 and 7–8. The added normalization source records still need original-result matching under A01/A04/A05.

## Checks that passed at the documented scope

- **Relative versus absolute arithmetic:** the cards retain the base-field/geometricity premise in Semi-graphs Theorem 6.4 and distinguish local multiplicative-invariant recovery from additive field reconstruction. No blanket local absolute-Galois reconstruction claim was found.
- **Global Galois reconstruction:** P16.2 explicitly owns deeper global class-field/decomposition/density/approximation leaves. The number-field Neukirch–Uchida theorem is distinguished from the solvably-closed extension theorem, and the latter is optional unless a caller needs it. The unresolved AbsTop III theorem-number mismatch remains visible in A02.
- **Isom versus Hom:** the source cards condition any full-Hom omission on auditing all callers; AbsTop I Theorem 4.7(i),(ii) is distinguished from its stronger Hom clauses. No replacement proof is claimed merely from narrowing the statement.
- **Later corrections:** countability, cusp-recognition, terminal three-point-line and log-meromorphic corrections have named source locks. Checking that the actual geometric inputs satisfy the corrected assumptions remains an implementation task, as the plan correctly states.
- **Paper-level cycles:** Semi-graphs' later AbsTop II explanation is treated as a proof-slice choice. A citation to a later explanation is not accepted as a circular theorem proof. The source cards explicitly require a theorem-level DAG.
- **EtTh/Frobenioid integration:** the abstract category definitions and reconstruction claims are kept separate from arithmetic realizations. Positive degree rescaling, saturation, heterogeneous divisor maps and residual conjugacy/sign/root-of-unity ambiguities are retained.
- **Final target:** P31 is reserved for the full native Theorem 3.11 after all retained proofs and interpretation bridges. No Corollary 3.12 or IUT IV inequality is used to justify it.

## Scheduling assessment

The package-level prerequisite lists read as main proof boundaries, with earlier interface design expressly allowed. They are not a claim that whole source papers have to finish serially. The staged P13 definitions, elementary P17.1 output and concrete P27.C output are essential to the promised parallelism.

The stated order **P27.R → P28.C → P27.V** avoids the artificial packet/volume cycle. P19's generic/local/archimedean exports should likewise consume the exact earlier P18/P13/P17.1 outputs they require, rather than unnecessarily waiting for all global P17 reconstruction. Selected rigid/affinoid foundations may feed P10 while Tate uniformization proceeds separately. These are scheduling refinements; they do not establish a mathematical shortcut in any proof.

The root graph files were not yet present at the initial review snapshot. A later graph sweep must verify that these stages are represented as separate vertices where needed, arrows point prerequisite → consumer, all vertices reach P31, P31 has no outgoing proof edge, and there are no directed cycles. This report does not claim that pending graph check has passed.

## Review limit and conclusion

No contradiction in a claimed mathematical theorem was established by this review. The required refinements above make known source/helper obligations more explicit. Original theorem matching and recursive proof closure remain owned work under A01–A08; the documentation review does not close those gates or promote a theorem to “proved”.

[Home](../README.md) · [Anabelian sources](../sources/anabelian/README.md) · [Output graph](../graphs/work-packages.md) · [Audit gates](../tracking/audit-gates.md)

## Final graph sweep

The subsequently available [work graph](../graphs/work-packages.md) was checked by expanding grouped boundary labels and identifying repeated stage names across panels. On the reviewed snapshot it had **36 staged outputs and 114 prerequisite edges**. The expanded graph was acyclic; every P01–P31 package appeared; every output reached P31; and **P31 was the unique sink**. These are graph-structure checks, not a certification that every underlying theorem dependency is known.

The work graph correctly separates P05.core/P05.6, P13.1/P13.recon, P17.1/P17.global, and P27.C/P27.R/P28.C/P27.V. It does not impose the whole global P17 output before the local archimedean Frobenioid output. No new missing hard integration dependency was established by this sweep beyond the already assigned source/interpretation audit leaves.

The following source-graph semantics and scheduling refinements were sent to the integrator:

| ID | Review finding | Recommended graph treatment |
|---|---|---|
| GS01 | The original panel 3 arrow from global/archimedean reconstruction to **local** Proposition 5.8 log-shells conflated separate outputs. Local multiplicative shells and elementary circle constructions do not require the whole global reconstruction theorem. | Split local 5.8 outputs from global 5.10 compatibility, or remove the global-before-local arrow. The work graph already makes the analogous local/global distinction correctly. |
| GS02 | A solid Global Solvably Closed → global reconstruction arrow made the broader variant look mandatory, despite the source card's explicit route choice. | Show ordinary Neukirch–Uchida feeding the relevant global output, with the solvably-closed variant conditional on the exact caller/version match. |
| GS03 | A single “Filtered-local / Tamagawa alternatives” arrow into the relative-curve theorem conflated different theorem domains. | Separate the enhanced local-field reconstruction candidate from matching affine/relative curve alternatives; preserve the required bridge/field-class audit. |
| GS04 | The original Belyi existence → Noncritical Belyi arrow was solid while the source card still asks whether this proof uses or replaces the original existence proof. | Make that unclosed proof-source route dotted/conditional until the selected proof slice is checked. Both result interfaces remain planned. |
| GS05 | The work graph bundled P20 rigidity with its later Frobenioid realization, whereas the source graph already separated them. This hides an earlier reusable proof release. | Prefer distinct P20.rigidity and P20.realization outputs, with P19 entering the latter. Check the exact local-invariant/cusp helper inputs before certifying the earlier release. This is a parallelism refinement, not a proof shortcut. |

The source diagrams are explicitly summaries of selected outputs. This review does **not** require every transitive source edge to be repeated. Grouped curve/cover and analytic packages can likewise release independent Riemann–Roch/duality or affinoid results earlier than their eventual whole-package integration checkpoint.

The graph counts above refer to the reviewed snapshot; if stage splits are added in response, rerun acyclicity, reachability and final-sink checks on the resulting graph. Unresolved proof-slice choices remain in A01–A08 rather than being treated as mathematical axioms.

## Final dispositions after integration

The repaired source graphs, stage guide and package/source cards were re-read. The substantive documentation findings are addressed at the planning scope:

| Findings | Final disposition |
|---|---|
| AS01–AS02 | Galois Sections' additional Isom-route inputs are explicit; P12.2 now distinguishes the early finite-p-adic release from the number-field/sub-p-adic consumers and requires the broader theorem or a proved descent bridge. |
| AS03 | P17 now names the available §2/§4 archimedean selection targets rather than only a section family. Their exact hypotheses remain subject to source locking. |
| AS04 | P08.5/P20.5 and separate F21/F22 cards own corrected formal ringed-space models, normalization and interpretation bridges. The original EGA/Faltings statements remain explicit lock tasks; caller evidence is not presented as an independently verified original theorem. |
| AS05 | P05.core/P05.6 are separate graph outputs. The isolated table-row defects in P05/P06/P10 have been removed. |
| AS06 | The result catalogue explicitly distinguishes specialized standalone theta/Frobenioid reuse from the IUT assembly. No proof status is inferred from a usefulness badge. |
| GS01 | Local nonarchimedean and archimedean Proposition 5.8 shell outputs are separate from global Corollary 5.10 compatibility. The false global-before-local edge is removed. |
| GS02 | A required global-identity node receives two dotted, field-class-matched source choices. Neither source is treated as interchangeable with the other without the A02 match. P16.local/P16.global are now separate work outputs. |
| GS03 | Filtered-local field and matching Tamagawa curve alternatives are separate graph routes with the scope audit retained. |
| GS04 | The unclosed original-Belyi proof-source route is dotted. |
| GS05 | P20.rigidity and P20.realization are separate outputs. P19 and corrected P08.5 formal models feed realization; standalone rigidity no longer waits for the full Frobenioid proof. |

The final expanded scheduling check found **39 staged outputs and 126 prerequisite edges**, with no directed cycle, every package represented, every output reaching P31, and **P31 still the unique sink**. P08.5 has explicit incoming local-field and P05.core outputs. Aggregate references to P16 denote its required local/global exports; completed P20 references denote the realization output that already depends on rigidity.

This final disposition closes the bounded **documentation review**. It does not close A01–A09, verify any Lean theorem, certify a minimal recursive source closure, or remove the plan's explicit source/version/hypothesis-selection obligations. No material planning defect remains from the issues established in this review.

**Integrator final graph cleanup:** obsolete P16 styling was replaced by its local/global stage IDs; final-panel boundary labels now explicitly name those stages and completed P20.realization. P25's direct local-invariant boundary names P16.local. The final structural validation is recorded in [validation](validation.md); earlier counts in this review describe the reviewed snapshots.
