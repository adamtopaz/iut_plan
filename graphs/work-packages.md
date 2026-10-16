# Dependency graph for parallel work

Arrows mean **proved prerequisite output → consuming output**. Nodes split a few packages into early definitions/concrete mathematics and later reconstruction/compatibility results. This is the scheduling graph; a source book or paper is never a single all-or-nothing barrier.

**★** marks useful mathematics beyond IUT. **◇** marks specialized support. Colored IUT nodes are source-specific assembly; **P31 is the unique final sink**. Nodes represent planned deliverables, not completed proofs.

## From existing mathlib to reusable geometry

```mermaid
flowchart TD
  P01["P01 Shared interfaces / mathlib ★"] --> P02["P02 Local and global fields / logs ★"]
  P01 --> P03["P03 Continuous cohomology / Kummer ★"]
  P01 --> P05C["P05.core Covers and pi1 ★"]
  P01 --> P11["P11 Trees / profinite groups ★"]
  P01 --> P17L["P17.1 Circle and measure models ★"]
  P01 --> P18["P18 Frobenioid definitions ◇"]
  P02 --> P08F["P08.5 Formal models / normalization ★"]
  P05C --> P08F
  P02 --> P04["P04 Local CFT and duality ★"]
  P03 --> P04
  P05C --> P06["P06 Curves / duality / Belyi ★"]
  P05C --> P07["P07 Elliptic geometry / torsion ★"]
  P06 --> P07
  P05C --> P05H["P05.6 Geometric cohomology ★"]
  P03 --> P05H
  P06 --> P05H
  P02 --> P08["P08 Analytic curves / Tate ★"]
  P05C --> P08
  P07 --> P08
  P03 --> P09["P09 Abelian degeneration / weights ★"]
  P05H --> P09
  P06 --> P09
  P07 --> P09
  P02 --> P10["P10 Selected p-adic comparisons ★"]
  P03 --> P10
  P04 --> P10
  P05H --> P10
  P06 --> P10
  P08 --> P10
  P09 --> P10
  classDef reusable fill:#e8f5e9,stroke:#2e7d32,color:#16351b;
  classDef support fill:#fff8e1,stroke:#9a6700,color:#493500;
  class P01,P02,P03,P04,P05C,P05H,P06,P07,P08,P08F,P09,P10,P11,P17L reusable;
  class P18 support;
```

P05.core releases without the later cohomology output. Curve/coherent work in P06 and generic sheaf/cohomology work can develop in parallel; the geometric curve comparison P05.6 joins them only when its consumers need it.

## Anabelian and categorical reconstruction

```mermaid
flowchart TD
  C["P04 / P05.core / P06 / P09 / P10"] --> P12["P12 Relative p-adic Isom / Hom ★"]
  A["P05.core / P08 / P11"] --> P13D["P13.1 Tempered covering types ★"]
  P13D --> P13R["P13.recon Graph / cusp / torsion ★"]
  P12 --> P13R
  B["P04 / P05.core / P06 / P09 / P11"] --> P14["P14 Cuspidalization and chains ★"]
  P12 --> P14
  G["P02 / P03 / P04 / P05.core"] --> P16L["P16.local Multiplicative invariants ★"]
  G --> P16G["P16.global Field-class-matched global reconstruction ★"]
  P14 --> P15["P15 Function-field reconstruction ★"]
  P12 --> P15
  P16L --> P15
  P16G --> P15
  P15 --> P17G["P17.global Aut-holomorphic reconstruction ★"]
  L["P17.1 Local circle / measure"] --> P17G
  P18["P18 Abstract Frobenioids ◇"] --> P19["P19 Frobenioid reconstruction ◇"]
  P13R --> P19
  L --> P19
  F["P02 / P04 / P11"] --> P19
  P13R --> P20R["P20.rigidity EtTh sections1-2 ★"]
  T["P03 / P08"] --> P20R
  P16L --> P20R
  P20R --> P20C["P20.realization EtTh sections3-5 ◇"]
  P19 --> P20C
  FM["P08.5 Corrected formal models"] --> P20C
  classDef reusable fill:#e8f5e9,stroke:#2e7d32,color:#16351b;
  classDef support fill:#fff8e1,stroke:#9a6700,color:#493500;
  class P12,P13D,P13R,P14,P15,P16L,P16G,P17G reusable;
  class P18,P19,P20C support;
  class P20R reusable;
```

P16's global branch owns the additional global class-field/cohomological/density leaves selected by its proof audit. P19 needs local archimedean models from P17.1, not completion of P17.global. Within P19/P20, abstract reconstruction, analytic theta and their eventual realization can be worked on by separate teams.

## IUT assembly and the last theorem

```mermaid
flowchart TD
  E["P05.core / P06 / P07 / P13.1 / P18"] --> P21["P21 Native IUT input / theater types"]
  R["P15 / P16.local / P16.global / P17.global / P19 / P20.realization"] --> P22["P22 IUT I construction and symmetries"]
  P21 --> P22
  P22 --> P23["P23 IUT II local evaluation"]
  P20C["P20.realization EtTh"] --> P23
  P23 --> P24["P24 IUT II global gluing / links"]
  J["P15 / P17.global / P19 / P22"] --> P24
  P24 --> P25["P25 III log-links and coricity"]
  K["P02 / P16.local / P17.global / P22"] --> P25
  P25 --> P26["P26 III theta monoids"]
  P20C --> P26
  P24 --> P26
  N["P02 / P17.1"] --> P27C["P27.C Concrete measured packets ★"]
  P27C --> P27R["P27.R Reconstructed packets ★ / IUT"]
  P25 --> P27R
  P21 --> P27R
  P27R --> P28C["P28.C III LGP objects and pilots"]
  P26 --> P28C
  P24 --> P28C
  Q["P19 / P25"] --> P28C
  P28C --> P27V["P27.V / P28.4 Final volume compatibility"]
  P27R --> P27V
  P27V --> P29["P29 III global Kummer"]
  P28C --> P29
  S["P15 / P24 / P25"] --> P29
  P29 --> P30["P30 Native statement and all compatibility"]
  P26 --> P30
  P27V --> P30
  U["P22 / P24 / P25 / P28.C"] --> P30
  P30 --> P31["P31 THEOREM 3.11 — LAST"]
  classDef reusable fill:#e8f5e9,stroke:#2e7d32,color:#16351b;
  classDef iut fill:#e3f2fd,stroke:#1565c0,color:#102d4a;
  classDef final fill:#ede7f6,stroke:#512da8,stroke-width:3px,color:#291349;
  class P27C reusable;
  class P21,P22,P23,P24,P25,P26,P27R,P28C,P27V,P29,P30 iut;
  class P31 final;
```

This graph separates **P27.C → P27.R → P28.C → P27.V**. It does not put the complete later log-volume compatibility theorem upstream of its own LGP input. The output types and earlier concrete lemmas can be shared long before this final join.

## Read the graphs as contracts

Grouped boundary nodes name imported outputs already shown in another panel; they are not new mathematical tasks. The [package directory](../work-packages/README.md) and [interface guide](../plan/interfaces.md) define their exact scope. The [audit gates](../tracking/audit-gates.md) are required before acceptance but do not insert new axioms into the graph.

[Home](../README.md) · [Parallel assignments](../plan/roadmap.md#first-parallel-assignments) · [Papers/books graph](sources.md)
