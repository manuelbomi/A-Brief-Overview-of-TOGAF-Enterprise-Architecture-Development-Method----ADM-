# A Brief Overview of TOGAF Architecture Development Method -- ADM 

#### ADM stands for Architecture Development Method. It is the core, step-by-step method of TOGAF (The Open Group Architecture Framework) used by Enterprise Architects to design, govern, and evolve enterprise architectures in a structured, repeatable way.
---

## What ADM Is 

##### ADM is the operating system for Enterprise Architecture.

##### <ins>It answers</ins>:

- What architecture work should be done?

- In what order?

- With what inputs and outputs?

- How do we move from strategy to execution?

##### ADM ensures architecture is:

- Business-driven

- Capability-focused

- Governed

- Continuously improved
---

## The TOGAF ADM Cycle

##### ADM is iterative, not linear. Architects loop through phases as strategy, technology, or delivery changes.

```python
                  ┌─────────────────────┐
                  │     Preliminary     │
                  │  (EA Setup & Rules) │
                  └─────────▲───────────┘
                            │
┌───────────────┐           │           ┌───────────────┐
│   Phase H     │◄──────────┼──────────►│   Phase A     │
│ Change Mgmt   │           │           │ Vision & Scope│
└───────▲───────┘           │           └───────▼───────┘
        │                   │                   │
┌───────┴───────┐   ┌───────┴───────┐   ┌───────┴───────┐
│   Phase G     │   │   Architecture│   │   Phase B     │
│ Implementation│   │     Vision    │   │ Business Arch │
│ Governance    │   │   (Center)    │   │ Capabilities  │
└───────▲───────┘   └───────▲───────┘   └───────▼───────┘
        │                   │                   │
┌───────┴───────┐           │           ┌───────┴───────┐
│   Phase F     │◄──────────┼──────────►│   Phase C     │
│ Migration     │           │           │ Data & Apps   │
│ Planning      │           │           │ Architecture  │
└───────────────┘           │           └───────▼───────┘
                            │
                    ┌───────┴───────┐
                    │   Phase D     │
                    │ Technology    │
                    │ Architecture  │
                    └───────────────┘


```

```python
[Preliminary]
     ↓
[Phase A: Architecture Vision]
     ↓
[Phase B: Business Architecture]
     ↓
[Phase C: Data & Application Architecture]
     ↓
[Phase D: Technology Architecture]
     ↓
[Phase E: Opportunities & Solutions]
     ↓
[Phase F: Migration Planning]
     ↓
[Phase G: Implementation Governance]
     ↓
[Phase H: Architecture Change Management]
     ↺ (feeds back into Phase A)
```

> [!IMPORTANT]
> This is not waterfall — the Architect loops back whenever strategy or execution changes.
>

---

## ADM Redrawn — With “Why / What / How / Deliver” Lens

```python
WHY
 └─ Phase A: Vision & Outcomes

WHAT (Business)
 └─ Phase B: Capabilities & Value Streams

WHAT (Systems)
 └─ Phase C: Data, AI, Applications

HOW (Technology)
 └─ Phase D: Platforms, Cloud, GPU, MLOps

WHAT TO BUILD
 └─ Phase E: Solution Options

WHEN
 └─ Phase F: Roadmaps & Sequencing

GOVERN
 └─ Phase G: Ensure Correct Delivery

EVOLVE
 └─ Phase H: Adapt to Change

```

<ins>Iteration</ins>

- Teams can move backward or forward

- Change can enter at any phase

```python
Preliminary
     ↑
H ←------- G
↑            ↓
F   Architecture   A
↑     Vision        ↓
E → D → C → B

```

<ins>Central Anchor</ins>

- Architecture Vision & Capabilities sit at the center

- Everything else supports or evolves from them


> [!NOTE]
> ADM starts with vision, anchors on business capabilities, designs data and technology around them, governs delivery, and continuously adapts as strategy changes.
> 




