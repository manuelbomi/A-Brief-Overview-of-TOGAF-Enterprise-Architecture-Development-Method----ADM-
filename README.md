# A Brief Overview of TOGAF Enterprise Architecture Development Method (ADM)-- ADM + Capabilities

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


---

## ADM Phases 
### 🟣 Preliminary Phase – Set the Rules

#### <ins>Purpose</ins>:

- Establish EA governance

- Define principles, standards, tooling

- Align EA with business and IT governance

#### <ins>Outputs</ins>:

- Architecture principles

- EA operating model

- Architecture repository

---

### 🔵 Phase A: Architecture Vision – Why We Are Doing This

#### <ins>Purpose</ins>:

- Align stakeholders

- Define scope and value

- Link strategy to architecture work

#### <ins>Outputs</ins>:

- Architecture Vision

- Business outcomes & OKRs

- High-level capability view

---

### 🟢 Phase B: Business Architecture – What the Business Must Be Able to Do


#### <ins>Purpose</ins>:

- Define business capabilities

- Model value streams and domains

- Identify organizational impacts


#### <ins>Outputs</ins>:

- Business Capability Model

- Value Streams

- Business Information Map

> [!TIP]
> Capabilities live here
>

---

### 🟡 Phase C: Information Systems Architecture – Data & Applications

#### Split into:

- Data Architecture

- Application Architecture

#### <ins>Purpose</ins>:

- Define how data, AI, and applications support capabilities


#### <ins>Outputs</ins>:

- Data domains, data products

- Application services

- AI/ML capability enablement

---

### 🟠 Phase D: Technology Architecture – How It Runs

#### <ins>Purpose</ins>:

- Define infrastructure, cloud, GPU, MLOps, platforms


#### <ins>Outputs</ins>:

- Platform architectures

- Cloud/GPU stacks

- DevOps & MLOps tooling

---

### 🔴 Phase E: Opportunities & Solutions – What We Will Build

#### <ins>Purpose</ins>:

- Identify solution options

- Package capabilities into initiatives

#### <ins>Outputs</ins>:

- Solution architectures

- Transition architectures

- Roadmaps

---

### ⚫ Phase F: Migration Planning – When & In What Order

#### <ins>Purpose</ins>:

- Prioritize initiatives

- Align with funding and delivery

#### <ins>Outputs</ins>:

- Migration roadmap

- Work packages

- Investment sequencing

---

### 🟤 Phase G: Implementation Governance – Build It Right

#### <ins>Purpose</ins>:

- Ensure delivery aligns with architecture

#### <ins>Outputs</ins>:

- Architecture compliance assessments

- Governance checkpoints

---

### 🟤 Phase H: Architecture Change Management – Keep It Relevant

#### <ins>Purpose</ins>:

- Respond to change

- Trigger new ADM cycles

#### <ins>Outputs</ins>:

- Architecture updates

- Change requests

---

## Why ADM Matters for Data / AI / ML / Digital Transformation

#### ADM ensures that:

- AI initiatives are capability-driven, not tech experiments

- Data platforms are enterprise assets, not project silos

- MLOps and GPU investments are justified by business outcomes

- Architecture evolves with strategy, not after delivery

---

## ADM + Business Capability Modeling (Key Insight)


| ADM Phase | Role of Capabilities |
|-----------|----------------------|
| A | Communicate value |
| B | Define what the business needs |
| C | Map data & apps to capabilities |
| D | Map platforms & infrastructure |
| E–F | Prioritize investments |
| G | Govern delivery |
| H | Adapt to change |

---

#### Capabilities are the stable anchor across all ADM phases

| TOGAF ADM Phase | Role of Business Capabilities | Example Activities |
|-----------------|-------------------------------|---------------------|
| **A: Architecture Vision** | Communicate value of architecture initiatives | • Map capabilities to strategic goals<br>• Show capability gaps to stakeholders |
| **B: Business Architecture** | Define what the business needs to operate | • Create capability maps<br>• Assess capability maturity |
| **C: Information Systems Architecture** | Map data and applications to capabilities | • Link applications to capabilities they support<br>• Define data requirements per capability |
| **D: Technology Architecture** | Map platforms and infrastructure to capabilities | • Align technology stacks to capability needs<br>• Define infrastructure requirements |
| **E: Opportunities & Solutions** | Prioritize investments based on capability impact | • Analyze capability gaps<br>• Prioritize projects by capability improvement |
| **F: Migration Planning** | Plan capability evolution over time | • Create capability-based migration plan<br>• Define interim capability states |
| **G: Implementation Governance** | Govern delivery of capability improvements | • Monitor capability delivery<br>• Ensure architectural compliance |
| **H: Architecture Change Management** | Adapt capabilities to changing business needs | • Update capability models<br>• Manage capability lifecycle |


### Benefits of Capability-Centric ADM:
1. **Alignment:** Ensures technology investments support business needs
2. **Stability:** Capabilities change slower than technologies
3. **Traceability:** Clear line from strategy to implementation
4. **Governance:** Consistent framework for decision-making
5. **Communication:** Common language for business and IT



**Capabilities are the stable anchor across all ADM phases**


---



### Thank you for reading
---

### **AUTHOR'S BACKGROUND**
### Author's Name:  Emmanuel Oyekanlu
```
Skillset:   I have experience spanning several years in data science, developing scalable enterprise data pipelines,
enterprise solution architecture, architecting enterprise systems data and AI applications,
software and AI solution design and deployments, data engineering, high performance computing (GPU, CUDA), machine learning,
NLP, Agentic-AI and LLM applications as well as deploying scalable solutions (apps) on-prem and in the cloud.

I can be reached through: manuelbomi@yahoo.com

Website:  http://emmanueloyekanlu.com/
Publications:  https://scholar.google.com/citations?user=S-jTMfkAAAAJ&hl=en
LinkedIn:  https://www.linkedin.com/in/emmanuel-oyekanlu-6ba98616
Github:  https://github.com/manuelbomi

```
[![Icons](https://skillicons.dev/icons?i=aws,azure,gcp,scala,mongodb,redis,cassandra,kafka,anaconda,matlab,nodejs,django,py,c,anaconda,git,github,mysql,docker,kubernetes&theme=dark)](https://skillicons.dev)













