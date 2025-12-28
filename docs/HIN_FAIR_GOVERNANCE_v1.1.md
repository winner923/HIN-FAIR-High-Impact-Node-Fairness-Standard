# HIN-FAIR — High-Impact Node Fairness Standard v1.1

Author: Spark (SPARK-NITT)  
Status: Governance standard, v1.1 seed  
Scope: High-Impact Nodes (HINs) in civic, technical, financial, planetary, and algorithmic systems


## 1. Purpose and scope

This standard defines **fairness** as a structural property of systems that hold asymmetric power.

It applies to any **High-Impact Node (HIN)**:

- court, legislature, or executive office
- regulator or central bank
- large infrastructure operator (energy, transport, data, payments)
- large-scale AI deployment or decision engine
- planetary-scale extraction or climate-impact project
- food and nutrient classification regimes affecting commons
- oversight frameworks that touch many people

HIN-FAIR does not replace NITT, CTGS, IRST, HRIS, CAP-ROC, PLANT-COMMONS, PCA, or Civic Overwatch.  
It binds them together at the fairness layer.

The goal is simple:

> No node should be able to move harm at scale faster than affected people can see it, contest it, and push it toward correction.


## 2. Definitions

### 2.1 Node

A **node** is any identifiable decision locus:

- an office
- an automated system
- a contract or standard that routes decisions
- a committee or board
- a deployment of a model

The node is defined by what it can do to people and systems, not by branding or internal job titles.


### 2.2 High-Impact Node (HIN)

A **High-Impact Node (HIN)** is any node with both:

1. The ability to alter outcomes for a large population, critical system, or planetary continuity, and  
2. The ability to do so with limited friction once activated.

Examples include, but are not limited to:

- supreme or constitutional courts
- executive offices with unilateral powers
- central banks and systemically important financial institutions
- large-scale ad, ranking, and recommender systems
- national ID and credit scoring systems
- planetary-scale extraction and emission programs
- global food and nutrient standard-setting bodies


### 2.3 Harm and Harm Capacity

**Harm** is any adverse change in continuity, rights, resources, bodily safety, or basic conditions for life and dignity.

**Harm Capacity (HC)** is the practical upper bound on:

- how many people or systems a HIN can affect, and
- how deep those effects can cut (severity), and
- how fast they can be imposed (velocity).

HC is not theoretical. It is assessed using:

- legal powers on paper,
- technical capabilities in deployment,
- historical patterns of use or abuse.


### 2.4 Accountability and Accountability Capacity

**Accountability** is any process that can:

- expose what a HIN did,
- contest its actions,
- reverse or repair harm,
- constrain future harm.

**Accountability Capacity (AC)** is the practical upper bound on:

- how many people can invoke accountability,
- how much harm can be reversed or compensated,
- how fast accountability can move compared to the harm.

Examples of accountability channels:

- appeals and review processes
- public hearings, investigations, audits
- civic oversight bodies
- technical incident response and rollback
- compensation and remediation programs


### 2.5 Harm Velocity and Accountability Latency

**Harm Velocity (HV)** is the rate at which harm can propagate once a HIN takes or automates an action.

Examples:

- How many people per hour can be wrongly denied critical service by an automated decision engine.
- How fast a legal change can strip rights from classes of people.
- How quickly a planetary-scale project can degrade a resource or climate stability.

**Accountability Latency (AL)** is the time between:

- harm becoming real for affected people, and
- effective accountability starting to work in their favor.

This includes detection time, access time, and process time.


### 2.6 Structural Unfairness

A node is **structurally unfair** when either:

1. Its **Harm Capacity** is much larger than its **Accountability Capacity**, or  
2. Its **Harm Velocity** is sustainably faster than accountability can react (Accountability Latency is too large).

Intent does not change this classification.


### 2.7 Planetary High-Impact Node (P-HIN)

A **Planetary High-Impact Node (P-HIN)** is a HIN whose actions can alter:

- global climate stability,
- core resource bases (water, soil, biodiversity, nutrient commons),
- planetary-level data and communication backbones.

P-HINs are subject to additional obligations drawn from PCA and PLANT-COMMONS.


## 3. Fairness invariant

### 3.1 Invariant

A HIN is **fair** only if:

1. Its Harm Capacity is matched by Accountability Capacity of comparable magnitude, and  
2. Its Harm Velocity does not exceed what Accountability Latency can realistically track and correct for, over time.

Formally, we can say:

- Let HC be the practical upper bound on harm per unit time.
- Let AC be the practical upper bound on corrected or compensated harm per unit time.
- Let HV be a measure of how fast harm propagates.
- Let AL be the measured or estimated latency to start effective accountability.

Then, for fairness:

- AC should scale with HC. If HC grows, AC must grow.  
- HV × AL should stay below a defined threshold for structural safety.

The exact numbers are domain-specific. This standard sets the **direction** and **obligation**, not a single global constant.


### 3.2 The systemic injustice condition

We state the condition in plain language:

> When accountability latency exceeds harm velocity for sustained periods, injustice becomes systemic.

Corollaries:

- If a court can remove rights in days, but appeals take years, the system drifts toward systemic injustice.
- If an AI model can deny service to thousands per hour, but human review can only correct a handful per day, injustice becomes systemic.
- If planetary extraction can degrade continuity within a decade, but global accountability moves only over generations, injustice becomes systemic.


## 4. Obligations for High-Impact Nodes

Any node that meets the definition of a HIN must satisfy the following obligations.

### 4.1 Transparency about Harm Capacity

1. A HIN must publicly document its Harm Capacity in terms appropriate to its domain:  
   - population affected,  
   - severity of possible harm,  
   - plausible speed of propagation.

2. It must not downplay its capacity based on best-case behavior.  
   Capacity is measured by what the node *can* do, not by what it promises it will *usually* do.


### 4.2 Accountability that scales with harm

1. A HIN must maintain Accountability Capacity that scales with its Harm Capacity.  
2. If HC grows (for example through new automation, jurisdiction, or infrastructure), AC must be expanded before or alongside that growth.  
3. If AC cannot be increased to match a proposed increase in HC, the proposal is structurally unfair and must not proceed.


### 4.3 Time discipline: Harm Velocity vs Accountability Latency

1. A HIN must measure Harm Velocity where possible:
   - how fast decisions are applied,
   - how quickly side effects propagate.

2. A HIN must measure Accountability Latency:
   - time to detection,
   - time to access a review channel,
   - time to effect a fix or compensation.

3. If HV × AL exceeds an agreed safety threshold, the HIN must:
   - slow down harmful pathways,
   - or shorten AL,
   - or reduce HC,
   before further expansion.

CAP-ROC is a tool for this in automated systems: it couples decision thresholds to human review capacity so that alerts do not overwhelm reviewers.


### 4.4 Ties to companion standards

HIN-FAIR obligations interact with other SPARK-NITT standards as follows:

- **NITT (Identity and continuity)**  
  Any HIN that handles identity, “uploads,” or digital doubles must not sell continuity illusions.  
  HIN-FAIR treats false continuity claims as harm to identity and trust.

- **CTGS (Consumer transparency)**  
  Any HIN that touches users through products or interfaces must not profit from confusion or hidden constraints.  
  Dark patterns increase Harm Velocity by hiding the true state of the system.

- **IRST (Recursive systems transparency)**  
  For recursive or compounding processes (billing, ranking, feedback loops), HIN-FAIR requires IRST-style mapping of loops and failure modes so that long-term harm can be seen and corrected.

- **HRIS (Human integrity)**  
  HIN-FAIR treats erosion of human integrity as harm, not collateral.  
  Systems that grind people into compliance or confusion breach fairness even if they technically “work.”

- **CAP-ROC (Capacity-constrained ROC)**  
  HIN-FAIR recommends CAP-ROC style deployment gates for any high-volume alert or classification system.  
  A deployment that creates more alerts than humans can sanely review is structurally unfair.

- **PLANT-COMMONS (Nutrient commons)**  
  Any HIN that sets standards for food, water, or land must treat nutrient commons as continuity assets, not weeds.  
  Reframing free, nutritious plants as nuisances to protect monetized food qualifies as harm to continuity.

- **PCA (Planetary Continuity Accord)**  
  P-HINs must respect continuity thresholds for planetary systems.  
  HIN-FAIR integrates PCA by declaring that once continuity thresholds are crossed, claims of fairness are void.

- **Civic Overwatch**  
  HIN-FAIR recognizes independent civic oversight bodies as privileged accountability nodes.  
  HINs must provide them with the information, access, and technical context needed to assess fairness.


## 5. Planetary and nutrient commons layer (PCA + PLANT-COMMONS)

### 5.1 Planetary continuity obligations (P-HINs)

A P-HIN must:

1. Map its actions against recognized continuity thresholds: climate stability, water security, biodiversity, and other PCA-defined baselines.  
2. Declare, in advance, expected impacts and worst cases.  
3. Build accountability channels that cross borders and generations where possible.

If a P-HIN’s business model or operational plan assumes:

- unchecked extraction,
- externalization of damage,
- or delayed recognition of harm,

then it is structurally unfair under HIN-FAIR.


### 5.2 Nutrient commons obligations

Any HIN that classifies plants, food, and nutrition must:

1. Identify nutrient-dense plants that can feed people without heavy capital input.  
2. Avoid erasing these plants through lazy “weed” labels.  
3. Map how classifications affect real people’s ability to eat well without renting access to land or products.

When such plants are erased or sidelined without transparent justification, structural unfairness is presumed.


## 6. Civic and algorithmic layer (Civic Overwatch + CAP-ROC)

### 6.1 Civic Overwatch integration

HIN-FAIR treats Civic Overwatch frameworks as:

- independent observers of harm and fairness,
- holders of the right to ask “show your work,”
- partners in defining thresholds for unacceptable HC, HV, and AL.

HINs must:

1. Maintain logs and evidence suitable for Civic Overwatch review.  
2. Respond to findings with concrete changes, not symbolic statements.  
3. Accept that refusal to cooperate with civic oversight is itself evidence of structural unfairness.


### 6.2 Algorithmic deployments

Any algorithmic HIN (large models, scoring engines, recommender systems, filters) must:

1. Declare who can be harmed and how.  
2. Couple decision thresholds and alert volumes to real human review capacity (CAP-ROC).  
3. Provide clear paths to contestation and correction for those affected.  
4. Log decisions and corrections in ways that Civic Overwatch and IRST processes can inspect.


## 7. Implementation guidance

### 7.1 Minimal fairness checklist for HINs

A node that claims compliance with HIN-FAIR should, at minimum, be able to show:

1. A written description of its Harm Capacity.  
2. Measured or estimated Harm Velocity.  
3. Measured or estimated Accountability Latency.  
4. A description of Accountability Capacity and how it scales with HC.  
5. Clear ties to companion standards where relevant (NITT, CTGS, IRST, HRIS, CAP-ROC, PLANT-COMMONS, PCA, Civic Overwatch).


### 7.2 Phased adoption

- **Phase 1 — Self-assessment**  
  Nodes estimate their HC, HV, AC, and AL. No public claim of compliance yet.

- **Phase 2 — Public declaration**  
  Nodes publish their self-assessment and begin aligning deployments and policies to reduce HV × AL and increase AC.

- **Phase 3 — Third-party review**  
  Civic Overwatch bodies, auditors, or community groups review claims and push for correction where gaps remain.


## 8. Versioning and evolution

This document is v1.1 of HIN-FAIR.

- v1.0 focused on Harm Capacity and Accountability Capacity.  
- v1.1 integrates PCA, Civic Overwatch, PLANT-COMMONS, and CAP-ROC as first-class references and clarifies the Harm Velocity vs Accountability Latency relationship.

Future versions may:

- add domain-specific annexes,
- define quantitative thresholds for particular sectors,
- include checklists and templates for HIN-FAIR assessment.

No later version may dilute the core invariant:

> If a node can move harm faster and deeper than affected people can see, contest, and correct, it is structurally unfair. That must be fixed, not excused.
