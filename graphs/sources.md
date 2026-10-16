# Graph of papers and books

This is a graph of **selected outputs from sources**. An arrow means the prerequisite output is used by the consuming mathematical construction or selected proof route. It is not an instruction to formalize an entire text first. Dotted arrows mark alternatives or still-to-be-locked source routes. The [work-package graph](work-packages.md) gives the actual parallel schedule and staged joins.

**★** = useful beyond IUT; **◇** = specialized support. All source names below link through the [source catalogue](../sources/README.md). Different panels repeat a source when it exports independent results. No publication-date ordering is implied.

## Field, curve and analytic foundations

```mermaid
flowchart TD
  FT["Milne Fields / ANT; Lang ★"] --> LF["Serre Local Fields ★"]
  FT --> NSW["NSW: continuous cohomology ★"]
  LF --> CFT["Milne CFT or Serre: local reciprocity ★"]
  NSW --> CFT
  SGA["SGA1 / Stacks: covers and pi1 ★"] --> CUR["Hartshorne or Liu: curves / RR / duality ★"]
  SGA --> KUM["Stacks 59.28: Kummer ★"]
  NSW --> KUM
  CUR --> AEC["Silverman AEC: elliptic / torsion / reduction ★"]
  LF --> TATE["Silverman Advanced V: Tate curve ★"]
  AEC --> TATE
  LF --> RIG["Bosch: rigid analytic foundations ★"]
  RIG --> COMP["Selected analytic realization bridge ★"]
  BER["Berkovich: analytic topology ★"] --> COMP
  COMP --> AND["Andre: tempered coverings ★"]
  TATE --> AND
  CUR --> NB["Mochizuki Noncritical Belyi ★"]
  RR["Belyi original existence ★"] -.-> NB
  CUR --> COH["Milne / SGA / Stacks: geometric cohomology ★"]
  SGA --> COH
  classDef reusable fill:#e8f5e9,stroke:#2e7d32,color:#16351b;
  class FT,LF,NSW,CFT,SGA,CUR,KUM,AEC,TATE,RIG,COMP,BER,AND,NB,RR,COH reusable;
```

Milne/Serre/NSW are overlapping references for selected standard results. The proof-route lock chooses compatible proofs; it does not count every exposition as a separate mandatory project. The [field](../sources/foundations/field-number-theory.md), [CFT](../sources/foundations/class-field-theory.md), [curve](../sources/foundations/algebraic-curves.md) and [analytic](../sources/foundations/rigid-analytic-foundations.md) cards state the selections.

## Comparison and relative/tempered anabelian geometry

```mermaid
flowchart TD
  COH["Geometric cohomology / curve H1 ★"] --> FAL["Faltings1988: selected comparisons ★"]
  ABD["Abelian varieties / Jacobians ★"] --> AV["Mumford or Milne AV: Weil weights ★"]
  ABD --> FC["Faltings-Chai III.7.3: degeneration ★"]
  AV --> BK["Bloch-Kato local section3 ★"]
  FC --> BK
  FO["Fontaine1982: periods / de Rham / crystalline ★"] --> BK
  TT["Tate1967: local period cohomology ★"] --> BK
  CFT["Local CFT / continuous cohomology ★"] --> BK
  FAL --> LP["Mochizuki Local Pro-p A / 16.5 ★"]
  BK --> LP
  TT --> LP
  LP --> GS["Galois Sections: relative / torsion inputs ★"]
  GS --> SG["Semi-graphs: graph / cusp / torsion ★"]
  AND["Andre tempered theory ★"] --> SG
  TREES["Serre Trees / Ribes-Zalesskii ★"] --> SG
  GA["Geometry of Anabelioids ★"] --> SG
  SG --> ETH["EtTh sections1-2: theta rigidity ★"]
  AB["Absolute Anabelian Curves ★"] --> ETH
  AND --> ETH
  FOM["Fontaine-Messing selected slice"] -.-> BK
  classDef reusable fill:#e8f5e9,stroke:#2e7d32,color:#16351b;
  class COH,FAL,ABD,AV,FC,BK,FO,TT,CFT,LP,GS,SG,AND,TREES,GA,ETH,AB reusable;
```

The Fontaine–Messing edge is a proof-selection question within the retained local comparison slice. The [Fontaine](../sources/foundations/fontaine-period-rings.md) card owns its resolution. The Isom-only specialization of the relative Hom route is allowed only after checking every retained caller and its additional localization/torsion inputs.

## Cuspidalization and field reconstruction

```mermaid
flowchart TD
  AV["Degeneration and finite-field weights ★"] --> AB["Absolute Anabelian Curves: local invariants ★"]
  AV --> CG["Combinatorial GC: graph / cusp recognition ★"]
  LP["Relative p-adic Isom ★"] --> AI["AbsTop I: cusp and chain reconstruction ★"]
  CG --> AI
  AI --> AII["AbsTop II: Belyi cuspidalization ★"]
  NB["Belyi / Noncritical Belyi ★"] --> AII
  PC["Proper Cuspidalizations: abelian / function data ★"] --> AIII["AbsTop III section1: function fields ★"]
  AII --> AIII
  AB --> AIII
  GS["Galois Sections: approximation / cyclotomes ★"] --> AIII
  NU["NSW XII / Uchida: global reconstruction ★"] -.-> REQ["P16 Required global identity; field-class lock A02"]
  GLOBAL["Global Solvably Closed: selected variant ★"] -.-> REQ
  REQ --> AG["AbsTop III: global / archimedean reconstruction ★"]
  AIII --> AG
  AB --> SHN["AbsTop III 5.8(i)-(iii): local nonarch shells ◇"]
  TOPO["Circle / complex topology ★"] --> SHA["AbsTop III 5.8(iv)-(vi): local arc shells ◇"]
  SHN --> SC["Cor5.10: global log-shell comparison ◇"]
  SHA --> SC
  AG --> SC
  FIL["Filtered-local field reconstruction"] -.-> AB
  TAM["Tamagawa affine Isom: field-class-matched alternative"] -.-> LP
  classDef reusable fill:#e8f5e9,stroke:#2e7d32,color:#16351b;
  classDef support fill:#fff8e1,stroke:#9a6700,color:#493500;
  class AV,AB,CG,LP,AI,AII,NB,PC,AIII,GS,NU,GLOBAL,AG,TOPO reusable;
  class SHN,SHA,SC support;
```

The global identity node requires a field-class-matched proof; the ordinary number-field theorem and solvably closed variant are not asserted interchangeable. The two source-number mismatches in the global/abelian-cuspidalization callers must be reconciled under A02. Filtered-local and affine alternatives are not substitutes for every relative, global or tempered theorem. The [scope-boundary card](../sources/anabelian/alternatives-and-boundaries.md) records this distinction.

## Categorical arithmetic, corrected models and the IUT endpoint

```mermaid
flowchart TD
  GA["Anabelioid / monoid / category foundations"] --> FI["Frobenioids I: definitions then reconstruction ◇"]
  AR["Local CFT / units / Dirichlet / degree ★"] --> FI
  FI --> FII["Frobenioids II: local and poly reconstruction ◇"]
  SG["Semi-graphs / tempered reconstruction ★"] --> FII
  TOP["Local archimedean circle and measure ★"] --> FII
  RIG["EtTh sections1-2 rigidity ★"] --> ER["EtTh sections3-5: realization ◇"]
  FII --> ER
  MOD["EGA IV / Faltings crystalline: formal normalization ★"] --> ER
  ER --> I["IUT I: theaters / processions"]
  REC["AbsTop III reconstruction"] --> I
  I --> II["IUT II: local evaluation / global gluing"]
  II --> III1["IUT III sections1-2: links / theta monoids"]
  ALG["Local tensor / lattice / Haar calculus ★"] --> III3["IUT III section3: packets / LGP / Kummer"]
  III1 --> III3
  III3 --> CMP["All native compatibility clauses"]
  CMP --> FIN["IUT III THEOREM 3.11 — LAST"]
  classDef reusable fill:#e8f5e9,stroke:#2e7d32,color:#16351b;
  classDef support fill:#fff8e1,stroke:#9a6700,color:#493500;
  classDef iut fill:#e3f2fd,stroke:#1565c0,color:#102d4a;
  classDef final fill:#ede7f6,stroke:#512da8,stroke-width:3px,color:#291349;
  class AR,SG,TOP,RIG,MOD,ALG reusable;
  class FI,FII,ER support;
  class I,II,III1,III3,CMP iut;
  class FIN final;
```

The EGA/Faltings crystalline-paper inputs are selected normalization/model assertions requested by the later EtTh corrections, not permission to identify a formal ringed space with a rigid/Berkovich generic fiber without proof. Their source cards and P08/P20 own the exact interpretation bridge.

[Home](../README.md) · [All source cards](../sources/README.md) · [Output schedule](work-packages.md) · [Audit gates](../tracking/audit-gates.md)
