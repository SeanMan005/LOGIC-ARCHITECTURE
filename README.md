# The Architectural Axis

A standalone site covering three mechanisms of the move from **logical architecture** (the WHAT) to **physical / design architecture** (the HOW).

The whole subject is one claim: the two directions on that axis are not inverses. Going up is subtraction and costs nothing. Going down is exclusion and can only be paid for with information the abstraction never contained.

---

## The three mechanisms

| # | Theory | What it answers |
|---|---|---|
| 01 | **The Asymmetric Derivation** | Direction — why up is free, why down must be bought, and why merging abstractions only ever widens them. |
| 02 | **The Funded Descent** | Price — why the same evidence is cheap early and expensive late, why the climb back up is refused, and the ratio that separates an earned design from an asserted one. |
| 03 | **The Welded Interior** | Substance — what the layers are made of: tested connections over territory still open, and why counting constraints is not the same as loading them. |

The closing section reads the three as one move: direction, price, substance.

---

## Contents

```
LOGIC ARCHITECTURE/
├── README.md                     this file
├── index.html                    the site — single file, opens offline
└── img/
    ├── axis-hero.png             the axis: subtraction up, exclusion down
    ├── asymmetric-derivation.png Fig. 1 — axis · gap · union law · refused ops
    ├── funded-descent.png        Fig. 2 — staircase · slide · climb-back · ratio
    └── welded-interior.png       Fig. 3 — the metric · both terms · crystal vs warehouse
```

## Viewing it

Open `index.html` in any browser. Everything renders offline; the only external request is the Google Fonts stylesheet, and the page falls back to a system sans without it.

The page is dark-only by design, so it sits with the rendered plates rather than framing them. The figures are dense — each one links to its full-size PNG for reading at 300 dpi.

A published copy lives at <https://claude.ai/artifact/UHEakVbz5RZUG3UH34Hi9L> (private; it has to be shared from the page's Share menu before anyone else can open it).

---

## Where it comes from

Written from three theory documents in the project root:

- `The Asymmetric Derivation — Why Abstraction Is Free and Specification Must Be Paid For… .md`
- `The Funded Descent — Why Every Step From Logical to Physical Architecture Is Priced by the Dimensionality at Which It Is Taken… .md`
- `The Welded Interior — Why Connection Mass Per Unit of Branching Volume Is the Internal Metric of Architecture… .md`

The site keeps each document's section order but drops the corpus vocabulary — *verdict* reads as evidence, *route count* as options, *trade space* as room to move. The theory documents hold the full terminology; this is the plain-language pass.

Three of the four figures are generated, and can be re-rendered from the project root:

```
python asymmetric_derivation_diagram.py
python funded_descent_diagram.py
python welded_interior_diagram.py
```

Each writes a 300 dpi PNG beside its script; copy the result into `img/` under the name above to update the site. The fourth, `axis-hero.png`, is an illustration rather than a generated plate.

## Upstream

Mechanism 03 draws its interior metric from three theories in `CLAUDE ARCHITECTURE/`: **The Resolution Band** (coupling depth), **The Sampling Product** (scope × density across coupled constraints), and **Structural Density, the Generator, and Downward Reorganization** (connection mass per unit of branching volume). Mechanism 02 sits on **Unified Theory of Dimensional Sequencing** and **The Earned Axis**.
