# Block 0B — Evidence Strength Hierarchy

> Document subordination note
>
> This document is a subordinate companion document of Phase 0. The Phase 0 Master Governance Document is the canonical source of operative interpretation. If this file preserves older, broader, or partially inconsistent wording, the Master Document prevails.

## 0B.1 Evidence strength hierarchy

### Purpose
This section defines the operative hierarchy of evidence used by the system to support, refute, limit, or degrade claims. Its function is to prevent sources of different proximity, traceability, and vulnerability to error from being treated as equivalent.

The hierarchy does not exist to reward the most sophisticated source, but to identify which best represents the real system within the specific context of the claim.

### Definition of evidence strength
Evidence strength is the relative capacity of a source or collection of sources to support, refute, or limit a claim within a defined context, considering its proximity to the real system, its traceability, its temporal and operational fidelity, its independence, and its susceptibility to error or interpretation.

### Master rule
The strongest evidence is not the one that sounds most technical, but the one that best represents the real system within the context of the claim, with greater traceability, less interpretive dependency, and less vulnerability to undeclared error.

### Structural rule
The hierarchy must be evaluated on two levels:

1. **Base class of evidence**: what type of source it is.
2. **Strength modifiers**: how reliable that source is in the specific case.

This implies that no source wins automatically just by belonging to a high tier. Its final strength also depends on its contextual quality, integrity, and representativeness.

### Rule on LLM-constructed artifacts
No chart, diagram, table, summarized equation, flowchart, annotated image, or explanatory artifact constructed by the LLM can by itself increase the epistemological strength of the claim it represents.

Every explanation artifact is a derived representation. Therefore:
- it does not constitute primary evidence,
- it cannot defeat strong evidence through visual presentation,
- and it must inherit the strength of the claim and the evidence that support it, never exceed them.

### Duality rule
Every relevant explanation artifact must be able to exist in two modes:
- `construction mode`: build the representation.
- `verification mode`: review whether the visual or tabular representation distorts, exaggerates, oversimplifies, or overclaims relative to the original claim pack.

### Rule on base analytical outputs
The framework's primary outputs of quantitative analysis, predictive modeling, statistical inference, technical simulation, or physical calculation must not be epistemologically attributed to the LLM.

When the system uses machine learning, physics, simulation, statistics, or explicit calculation:
- those engines are responsible for the underlying analytical content,
- and the LLM may only formulate, summarize, structure, or semantically verify that content.

Ideally, those engines should produce a structured analytical output before any natural-language drafting.

Accordingly:
- well-written text by the LLM must not be confused with the primary source of the analysis,
- and a material claim should not depend exclusively on generated prose when structured analytical output is available.

### Rule of intersection of restrictions
The epistemological strength of a claim does not depend only on the weight of an isolated source. It also depends on how many independent restrictions survive without material contradiction.

In this framework, a strong result is not simply a result with good local evidence. It is a result that also remains compatible with:
- physical restrictions,
- uncertainty quantification,
- operational logic,
- M&V comparability,
- normative admissibility,
- and economic viability, when applicable.

---

## Tier 1 — High-proximity primary empirical evidence

### 1. Field measurement under explicit method

**Definition**
Measurement performed directly on the real system under an identifiable method, with sufficiently clear temporal, operational, and metrological context.

**Example**
- flow measurement campaign,
- point measurement of line temperature or pressure,
- field test with explicit protocol,
- power measurement under controlled condition.

**Why it's here**
Because, when well executed, it is the closest form of contrast with the real system.

**Primary risk**
Poor calibration, poorly chosen measurement point, unrepresentative period, procedural error, or reading out of context.

**Dominant use**
Empirical contrast, strong validation, verification, hypothesis refutation.

---

### 2. Reliable and contextualized Historian / SCADA / BMS

**Definition**
Historical record of operational variables from digital supervision or automation systems, provided their tags, temporal resolution, and context are sufficiently reliable.

**Example**
- historian of pressure and temperature,
- SCADA operation records,
- BMS trends,
- historical data of critical process variables.

**Why it's here**
Because it offers high proximity to real behavior and allows analysis of temporal continuity, sequence, and operational dynamics.

**Primary risk**
Wrong tags, poorly maintained sensors, low resolution, poor operational contextualization, or blind trust in the system.

**Dominant use**
Analysis of operational behavior, temporal consistency, contrast against declarations or hypotheses.

---

### 3. Billing and traceable primary operational records

**Definition**
Aggregated and primary records of consumption, production, or operation with clear documentary traceability.

**Example**
- energy bills,
- monthly consumption records,
- primary production reports,
- traceable plant operational records.

**Why it's here**
Because they are usually robust sources for aggregated magnitudes and general system consistency.

**Primary risk**
Excessive aggregation, low causal resolution, mixing of loads or periods that prevent fine local attribution.

**Dominant use**
Validation of totals, robust screening, aggregated consistency, macro contrast of system behavior.

---

### 4. Point sensors or temporary measurement campaigns

**Definition**
Temporary or localized instrumentation used to capture specific variables over a limited interval.

**Example**
- temporary logger,
- portable sensor,
- brief point measurement campaign,
- externally installed instrument temporarily.

**Why it's here**
Because it can offer very useful local evidence of good quality, though usually with less continuity or representativeness than more robust field measurement or well-maintained historian.

**Primary risk**
Inadequate location, short duration, non-representative conditions, faulty installation.

**Dominant use**
Local diagnosis, point contrast, directed investigation, support for preliminary claims or localized refutation.

---

## Tier 2 — Structural and normative evidence that limits or frames

### 5. Explicit physical constraints

**Definition**
Limits or physical relationships that restrict what can happen, be asserted, or recommended within the system.

**Example**
- mass or energy balance,
- thermal limit,
- physically incompatible pressure,
- material impossibility of certain behavior.

**Why it's here**
Because it doesn't necessarily describe what is happening, but can invalidate claims incompatible with basic physics or with the possible behavior of the system.

**Primary risk**
Applying a physically valid simplification in the abstract but misinterpreted in a more complex real context.

**Dominant use**
Refute incompatible claims, limit inferences, invalidate model outputs or impossible operational narrative.

---

### 6. Regulation, applicable standard, compliance limits

**Definition**
Regulatory, normative, or compliance framework that restricts what can be asserted, proposed, or executed.

**Example**
- safety standard,
- regulatory requirement,
- environmental compliance limit,
- applicable methodological obligation.

**Why it's here**
Because it does not by itself prove the state of the real system, but it does limit the space of actions and can defeat recommendations incompatible with compliance.

**Primary risk**
Poor normative interpretation, application of non-current standard, or incorrect extrapolation of regulatory scope.

**Dominant use**
Limit actions, discard non-permitted recommendations, impose evidence or methodology requirements.

---

### 7. Primary technical documentation of asset or process

**Definition**
Original documentation of equipment, asset, or process, issued by manufacturer, designer, integrator, or primary technical source.

**Example**
- technical manual,
- specification sheet,
- design documentation,
- original diagrams,
- asset datasheet.

**Why it's here**
Because it frames capabilities, configurations, and nominal system limits, although it doesn't guarantee current real behavior.

**Primary risk**
Outdated document, asset modified in field, discrepancy between nominal design and real operation.

**Dominant use**
Technical contextualization, compatibility check, assumption delimitation, nominal contrast.

---

## Tier 3 — Comparative contextual or published evidence

### 8. Relevant technical or scientific literature

**Definition**
Evidence published in papers, technical guides, scientific reports, or methodological documents relevant to the mechanism or claim evaluated.

**Example**
- peer-reviewed article,
- technical guideline,
- scientific document on thermal causality,
- published validation method.

**Why it's here**
Because it provides technical, causal, and methodological support, but normally does not directly describe the local case.

**Primary risk**
Undue extrapolation, study conditions not comparable, overconfidence in results outside domain.

**Dominant use**
Contextual support, causal hypothesis, test design, methodological justification.

---

### 9. Sectoral benchmarks or comparable archetypes

**Definition**
External comparative references used to preliminarily locate the relative performance of an installation, process, or asset.

**Example**
- energy intensity benchmark,
- typical operation archetype,
- sectoral performance reference,
- comparison against similar installations.

**Why it's here**
Because it is useful for early screening and prioritization, but rarely should it defeat strong local evidence.

**Primary risk**
False comparability, differences in context, process, scale, climate, sequence, or load mixing.

**Dominant use**
Screening, prioritization, preliminary contextualization, identification of apparent deviations.

---

### 10. Structured public data

**Definition**
External data publicly available with sufficient structure for comparative or contextual analysis.

**Example**
- public consumption databases,
- sectoral statistics,
- regulatory datasets,
- public reference series.

**Why it's here**
Because they can enrich context, but are usually aggregated and distant from the particular case.

**Primary risk**
Excessive aggregation, temporal lag, lack of granularity, methodological differences.

**Dominant use**
External context, broad screening, market or sectoral contextualization.

---

## Tier 4 — Declarative or expert evidence

### 11. Formalized expert judgment

**Definition**
Structured and documented expert knowledge that provides technical criterion to analysis.

**Example**
- expert prior,
- formalized engineering judgment,
- documented specialized criterion,
- expert interpretation of a pattern.

**Why it's here**
Because it can be valuable, especially in environments with limited data, but carries higher interpretive load than strong empirical evidence.

**Primary risk**
Expert bias, over-generalization, undue authority not sufficiently contrasted.

**Dominant use**
Hypothesis, priors, early interpretation, measurement design or prioritization.

---

### 12. User / operator / client input

**Definition**
Information declared by human actors about the system, its operation, constraints, or history.

**Example**
- declared schedule,
- problem reported by operator,
- sequence described by client,
- operational constraint communicated.

**Why it's here**
Because it is useful and sometimes indispensable for initial contextualization, but its strength depends on later corroboration.

**Primary risk**
Imperfect memory, bias, over-simplification, partial information, or incentive bias.

**Dominant use**
Initial context, assumptions, preliminary constraints, early screening.

---

### 13. Sectoral analogy

**Definition**
Use of similar cases or general sectoral patterns to suggest possible behaviors or opportunities.

**Example**
- "plants of this type usually have this problem",
- analogy with a comparable industrial case,
- sectoral pattern transferred as hypothesis.

**Why it's here**
Because it can inspire exploration, but has low strength for local claims.

**Primary risk**
Over-generalization and false transfer of causality.

**Dominant use**
Ideation, preliminary hypothesis, exploration of possibilities.

---

## Tier 5 — Model-derived evidence

### 14. Simulation

**Definition**
Result produced by a simulation model or computational representation of the system.

**Example**
- projected savings,
- expected thermal behavior,
- simulated response to operational change,
- modeled energy scenario.

**Why it's here**
Because it can be useful and sometimes highly sophisticated, but remains derived and dependent on assumptions, inputs, and domain of validity.

**Primary risk**
False precision, hidden sensitivity to assumptions, illusion of robustness from mathematical complexity.

**Dominant use**
Scenarios, sensitivity, test design, conditional quantification.

---

### 15. Analytical / ML model output

**Definition**
Result issued by statistical, analytical, or machine learning models that support classification, prioritization, or estimation.

**Example**
- composite score,
- opportunity ranking,
- estimated probability,
- ML-assisted classification.

**Why it's here**
Because it provides useful support, but should not displace superior evidence when relevant conflict exists.

**Primary risk**
Opacity, overconfidence, training bias, behavior outside domain.

**Dominant use**
Ranking, comparative support, preliminary filtering, auxiliary analytical support.

---

### 16. LLM output

**Definition**
Text, classification, synthesis, or interpretation produced by a language model.

**Example**
- generated technical summary,
- textual hypothesis proposal,
- recommendation draft,
- LLM-assisted preliminary classification.

**Why it's here**
Because it can help organize, synthesize, or draft, but does not represent primary evidence or can sustain by itself a serious claim.

**Primary risk**
Hallucination, persuasive narrative without sufficient basis, invented causality, undue verbal authority.

**Dominant use**
Draft, textual support, synthesis, preliminary classification subject to control.

**Absolute rule**
LLM output can never be dominant evidence.

---

## Strength modifiers

### Positive modifiers
Increase relative strength of evidence when applicable:

- independent source,
- known calibration,
- representative temporal context,
- alignment with physics,
- complete traceability,
- consistency with other strong sources,
- direct proximity to claim,
- sufficient resolution,
- documentary integrity.

### Negative modifiers
Decrease relative strength of evidence when applicable:

- aggregated source without useful decomposition,
- uncalibrated sensor,
- dubious tag,
- data outside relevant period,
- poorly comparable benchmark,
- literature outside domain,
- uncorroborated human declaration,
- opaque model,
- grounding-free LLM,
- uncalibrated simulation,
- conflict with physical constraint.

---

## Precedence rules

### Rule 1
Strong local empirical evidence defeats benchmark, literature, analogy, and expert judgment, except proof that local evidence is compromised.

### Rule 2
Explicit physical constraint defeats inference, simulation, and operational narrative incompatible with it.

### Rule 3
Applicable regulation defeats technically attractive recommendation but not allowed.

### Rule 4
Historian, SCADA, or BMS do not automatically defeat a point sensor. The better-calibrated, more-contextualized source closest to the specific claim wins.

### Rule 5
Billing defeats weak aggregated estimation on total consumption, but doesn't necessarily defeat point measurement when claim refers to local causality.

### Rule 6
No model output nor LLM output can defeat strong measurement, explicit physics, or applicable regulation.

---

## Conflict examples

### Example 1 — Benchmark contradicts measurement
**Case**
Benchmark suggests overconsumption, but well-executed local measurement shows no relevant deviation.

**Resolution**
Local measurement wins. Benchmark is degraded to contextual reference or initial screening criterion.

**Permitted conclusion**
Benchmark justified investigation, but does not sustain the claim against strong contrary local evidence.

---

### Example 2 — User contradicts archetype
**Case**
User declares 24/7 operation, but sectoral archetype assumes partial operation.

**Resolution**
User input has initial contextual precedence over generic archetype, but must be corroborated with historian, billing, or production.

**Permitted conclusion**
24/7 operation is treated as plausible operational hypothesis, not confirmed truth.

---

### Example 3 — Model contradicts physics
**Case**
Model projects savings under physically incompatible condition.

**Resolution**
Physical constraint wins. Model output is invalidated or suspended until inputs, architecture, or domain are reviewed.

**Permitted conclusion**
The claim cannot be sustained while the model contradicts explicit physical limitation.

---

### Example 4 — Literature contradicts observed real practice
**Case**
Literature suggests certain behavior, but real observed operation shows consistent, repeated different pattern.

**Resolution**
Literature is degraded as local support if empirical observation is strong and context is not comparable to study.

**Permitted conclusion**
Real practice prevails for local case; literature remains as contextual reference or secondary hypothesis.

---

### Example 5 — Simulation vs measurement
**Case**
Simulation projects savings, but measurement does not reproduce them.

**Resolution**
Measurement wins, unless clear evidence that measurement was poorly designed or not comparable with simulated scenario.

**Permitted conclusion**
Simulation is reclassified as unconfirmed scenario.

---

## Special multisource convergence rule
Evidence strength does not always arise from a single source. It can arise from coherent convergence among several independent sources.

### Example
- billing,
- historian,
- and explicit physical constraint

can form a package of evidence stronger than an isolated point sensor or highly sophisticated but poorly contextualized simulation.

### Rule
A coherent set of independent sources can defeat an individually apparently superior but isolated, poorly contextualized, or epistemologically fragile source.

---

## Operative summary table

| Tier | Source | Base strength | Primary risk | Dominant use |
|---|---|---:|---|---|
| 1 | Field measurement under explicit method | very high | poor calibration or poor period | contrast and verification |
| 1 | Reliable Historian / SCADA / BMS | high | wrong tags or incomplete context | operational behavior |
| 1 | Billing / primary records | high | aggregation or low causal resolution | total consumption and consistency |
| 1 | Point sensors | medium-high | location or representativeness | local contrast and diagnosis |
| 2 | Explicit physical constraints | high as limit | excessive simplification | invalidate incompatible claims |
| 2 | Regulation / standard | high as limit | poor normative interpretation | limit actions and claims |
| 2 | Primary technical documentation | medium-high | outdated document | technical context |
| 3 | Literature | medium | extrapolation | hypothesis and contextual support |
| 3 | Benchmark | medium-low | poor comparability | screening and prioritization |
| 3 | Public data | medium-low | aggregation or insufficient context | external context |
| 4 | Expert judgment | medium-low | expert bias | prior and hypothesis |
| 4 | User input | low-medium | bias or imperfect memory | initial context |
| 4 | Sectoral analogy | low | over-generalization | ideation and hypothesis |
| 5 | Simulation | variable | false precision | scenarios |
| 5 | ML/analytical model output | variable | opacity or overconfidence | ranking and support |
| 5 | LLM output | low | hallucination or convincing narrative | draft and synthesis |

---

## Closed design decisions

1. The hierarchy is adopted as a tier structure with additional contextual evaluation by strength modifiers.
2. Explicit physical constraints and applicable regulation remain in Tier 2 as evidence-limits.
3. LLM output can never be dominant evidence.
4. No source wins automatically just by belonging to a higher tier; final strength also depends on calibration, representativeness, traceability, and proximity to claim.

---

## Normative closure
Evidence hierarchy exists to impose epistemological discipline on the system. Its function is not just to order sources, but to prevent weak but elegant evidence from displacing strong but uncomfortable evidence.

The system must always privilege the source or combination of sources that best represents the real system within the domain of the claim, under the conditions of the case, without inflating the weight of models, simulations, or generated narratives.

LLM output can never be dominant evidence. It can assist drafting, synthesis, or preliminary classification, but cannot sustain by itself a serious claim.

---

## 0B.2 Source conflict resolution policy

### Purpose
This section defines the formal policy used by the system to resolve conflicts between sources when they do not agree. Its function is to prevent artificial reconciliation, implicit arbitration, or biased selection of the source that proves most narratively convenient.

The goal is not to force consistency where none exists, but to preserve epistemological integrity when two or more relevant sources push the same claim in incompatible directions.

### Definition of conflict
Conflict exists between sources when two or more evidence pieces relevant to the same claim cannot be sustained simultaneously without materially altering the interpretation, status, or permitted use of the claim.

Not every difference between sources constitutes conflict. Conflict exists only when the discrepancy materially changes:
- the content of the claim,
- its strength,
- its epistemological category,
- its permitted use,
- or the derived recommendation.

### Master rule
The system must not artificially reconcile conflicting sources. It must resolve by precedence, degrade the claim, or explicitly suspend it.

### Prior normalization rule
Conflict is not declared until normalization of:
- variable,
- period,
- unit,
- operational context,
- and exact scope of the claim.

Many apparent conflicts disappear when it is discovered that sources were not describing the same thing.

---

## Types of conflict

### 1. Factual conflict

**Definition**
Sources disagree on a fact, value, or observed state.

**Example**
- the bill shows 180,000 kWh and the internal system reports 145,000 kWh for the same period,
- the historian registers 92 psig and the point sensor reports 78 psig under the same declared condition.

**Why it matters**
Because it directly affects the empirical foundation of the claim.

**Typical resolution**
Precedence + traceability review + validation of unit, time, and context.

---

### 2. Interpretative conflict

**Definition**
Sources are compatible at the descriptive level but sustain different explanations or readings of the same phenomenon.

**Example**
- literature suggests a thermal cause,
- expert suggests a control problem,
- both on the same observed pattern.

**Why it matters**
Because it can inflate causality without sufficient basis to close dominant explanation.

**Typical resolution**
The explanation better aligned with local evidence, physics, and valid domain prevails. If insufficient, the claim remains as hypothesis or is degraded.

---

### 3. Level conflict

**Definition**
Sources belong to different epistemological levels but are being treated as if equivalent.

**Example**
- simulation presented against measurement as if both are facts of the same order,
- model output used to displace strong empirical evidence.

**Why it matters**
Because it generates methodological inflation and false symmetry between observation and derivation.

**Typical resolution**
Epistemological hierarchy is restored and the inferior-level source remains subordinate or is reclassified.

---

### 4. Domain conflict

**Definition**
One source is valid in one context and another in another, but they are being compared outside domain or without sufficient contextual equivalence.

**Example**
- climate benchmark different,
- paper under non-comparable conditions,
- model outside operational range,
- reference from different process typology.

**Why it matters**
Because a source can be technically good and still not apply to the case.

**Typical resolution**
Scope separation or degradation of the source outside domain.

---

### 5. Normative or constraint conflict

**Definition**
The recommendation or technical claim conflicts with a physical, regulatory, operational, contractual, or compliance constraint.

**Example**
- the financial model recommends an intervention the standard does not allow,
- a hypothesis requires a physically incompatible condition,
- an action is theoretically viable but blocked by critical operational constraint.

**Why it matters**
Because some conflicts are not about what is true, but about what remains valid or permitted to assert/propose.

**Typical resolution**
The valid constraint prevails as a limit; the claim is invalidated, degraded, or the recommendation is blocked.

---

## Formal resolution sequence

### Step 1 — Confirm the conflict is real
Before declaring conflict, the system must verify:
- same variable,
- same period,
- same unit,
- same operational state,
- same scope of claim.

**Rule**
Conflict is not declared until normalizing variable, period, unit, context, and scope.

---

### Step 2 — Classify the type of conflict
The conflict must be labeled as:
- factual,
- interpretative,
- of level,
- of domain,
- normative or of constraint.

**Rule**
Not all conflicts resolve the same way. Classification is mandatory.

---

### Step 3 — Apply base precedence
The system must apply the hierarchy of evidence defined in 0B.1.

**Inherited key rules**
- strong local measurement defeats benchmark, literature, analogy, and expert judgment, except evidence of compromise,
- explicit physics defeats inference, simulation, and incompatible narrative,
- applicable regulation defeats disallowed recommendation,
- model output or LLM output never defeats strong measurement, explicit physics, or applicable regulation.

---

### Step 4 — Apply contextual modifiers
The system must review:
- calibration,
- representativeness,
- proximity to claim,
- independence,
- documentary integrity,
- traceability,
- domain of validity.

**Rule**
A lower-tier source can prevail in a specific case if it is much better anchored to the real claim than a higher-tier source poorly contextualized.

---

### Step 5 — Determine epistemological outcome
All material conflict must end in one of these formal states:

#### A. Resolved by precedence
One source clearly defeats the other.

#### B. Resolved by scope separation
Both sources remain valid but for different scopes.

#### C. Claim degraded
The claim remains alive but with less strength, reduced scope, or limited permitted use.

#### D. Claim suspended
There is insufficient basis to honestly sustain the current level of the claim until new evidence is obtained.

#### E. Escalate to measurement / audit
The conflict cannot be resolved with existing sources and requires additional measurement, audit, or technical review.

---

### Step 6 — Register the conflict
All material conflict must remain traced with:
- sources involved,
- type of conflict,
- claim affected,
- rule applied,
- resolution,
- epistemological impact,
- and next action if pending.

**Rule**
No material conflict can be resolved in narrative alone. It must remain recorded.

### Conflict between constructed output and base context
Conflict also exists when an output constructed by the LLM, whether textual, tabular, or visual, represents in an incompatible way the context, evidence, domain, or epistemological level of the original claim.

### Rule
If an explanation artifact, narrative, or table constructed by the LLM:
- introduces unsupported causality,
- draws an unconfirmed sequence as closed,
- represents a hypothesis as fact,
- or visualizes nonexistent precision,

then the conflict must not be treated as an aesthetic error, but as an epistemological conflict between constructed output and base context.

### Typical resolution
- degrade the artifact,
- correct the representation,
- reclassify it as exploratory,
- or reject it until new construction/verification.

### Conflict between restriction layers
Conflict also exists when an output remains coherent in one layer but proves incompatible with another independent layer of restriction.

Examples:
- a statistically strong pattern that is physically impossible,
- a technically useful recommendation that is normatively inadmissible,
- an energetically attractive opportunity that is financially unviable,
- a plausible narrative that does not survive belief updating under new evidence.

### Rule
No individual layer must impose interpretive sovereignty. If material conflict exists between independent layers, the claim must:
- be degraded,
- be suspended,
- be reopened as hypothesis,
- or be escalated for further review.

---

## Hard resolution rules

### Rule 1 — Strong local measurement defeats external reference
If a robust local measurement contradicts benchmark, literature, analogy, or expert judgment, local measurement prevails, except demonstrated compromise of that measurement.

### Rule 2 — Explicit physical constraint invalidates or suspends incompatible claim
If an assertion contradicts an explicit physical constraint, it is not enough to narratively degrade it: the claim remains invalid or suspended.

### Rule 3 — Regulatory constraint invalidates incompatible recommendation
A recommendation can be technically attractive and still be blocked by valid standard, compliance, or contractual limitation.

### Rule 4 — Human declaration does not defeat strong empirical evidence
User input can guide context and hypothesis, but cannot by itself displace robust measurement, reliable historian, or traceable billing.

### Rule 5 — Simulation and model outputs do not defeat strong observation
They can justify methodological review, but do not automatically prevail against strong empirical evidence.

### Rule 6 — If conflict materially changes claim use and cannot be resolved, claim must be suspended
Strong language is not permitted over unresolved conflictive basis.

### Rule 7 — If two sources are valid in different domains, scope is separated
Contradiction should not be forced between sources answering different questions or applying to different scales.

---

## Suspension rule

### Definition
A claim must be suspended when material conflict exists between relevant sources and that conflict prevents honestly sustaining the current level of certainty, verbal strength, or recommendation.

### What suspension means
Suspension does not mean deletion or permanent discard. It means:
- do not use strong language,
- do not use the claim for higher-weight decisions,
- keep it traced as pending,
- and explicitly declare what evidence would resolve the conflict.

### Example
If simulation suggests high savings and preliminary measurement does not reproduce it, and there is no basis to decide which source is better anchored, the claim is not maintained as strong: it is suspended pending new evidence.

---

## Escalation rule

### Definition
Escalation occurs to measurement, audit, or additional technical review when the conflict cannot be resolved by precedence or scope separation, and resolution of the conflict is material for the decision.

### Rule
Not every conflict deserves new measurement. Escalation occurs only when:
- the conflict is real,
- it is material to action,
- and it cannot be honestly resolved with existing sources.

### Example
If BMS and point sensor disagree on a variable critical for validating an investment opportunity, it may be necessary to escalate to controlled measurement.

---

## Canonical cases

### Case 1 — Public data vs user-declared data
**Situation**
Public data suggests typical sector operation, but user declares a different operational regime.

**Resolution**
User data has initial contextual priority for the local case, but must be corroborated.

**Normal outcome**
The claim remains conditional or at hypothesis-level. It is not treated as confirmation.

---

### Case 2 — Benchmark vs billing
**Situation**
Benchmark suggests certain consumption pattern, but billing shows different aggregated total.

**Resolution**
Billing prevails for actual aggregated consumption of the case. Benchmark remains as comparative reference.

**Normal outcome**
Benchmark does not correct billing; it only contextualizes it.

---

### Case 3 — Simulation vs measurement
**Situation**
Simulation projects savings, but measurement does not reproduce them.

**Resolution**
Measurement prevails, unless clear evidence that it was poorly designed or outside comparative domain.

**Normal outcome**
The claim based on simulation is degraded, suspended, or reclassified as unconfirmed scenario.

---

### Case 4 — Literature prior vs observed real operation
**Situation**
Literature suggests certain behavior, but observed real operation shows another consistent, repeated pattern.

**Resolution**
Robust local practice prevails for the specific case. Literature remains as contextual support or secondary hypothesis.

**Normal outcome**
Literature is not discarded but loses local strength.

---

### Case 5 — Financial model vs regulatory constraint
**Situation**
Financial case favors an intervention, but regulation or compliance blocks it.

**Resolution**
Regulatory constraint prevails.

**Normal outcome**
The recommendation remains blocked even though expected return is favorable.

---

### Case 6 — BMS vs point sensor
**Situation**
BMS shows one value and point sensor another for the same apparent phenomenon.

**Resolution**
There is no automatic winner. Review:
- calibration,
- location,
- representativeness,
- resolution,
- proximity to claim.

**Normal outcome**
Can be resolved by contextual precedence or escalated to new measurement.

---

## Operative summary table

| Conflict type | Example | Primary resolution | Possible outcome |
|---|---|---|---|
| Factual | billing vs internal system | precedence + normalization | resolved / degraded / escalated |
| Interpretative | expert vs literature | physics + local evidence | degraded / scope-separated |
| Of level | simulation vs measurement | epistemological hierarchy | degraded / suspended |
| Of domain | non-comparable benchmark | domain validation | scope-separated / degraded |
| Normative | viable but not allowed savings | valid constraint | recommendation blocked |

---

## Closed design decisions

1. The framework adopts five types of conflict:
   - factual,
   - interpretative,
   - of level,
   - of domain,
   - normative or of constraint.

2. Explicit suspension of the claim is adopted as a formal system output.

3. Not all conflict needs resolution with current sources; some conflicts escalate to measurement, audit, or additional technical review.

4. Two sources can coexist if they answer different scopes; in those cases resolution is by scope separation, not by forced annulation.

---

## Normative closure
The conflict policy exists to prevent the system from masking material contradictions with elegant narrative. When two relevant sources do not agree, the system must resolve with explicit rules, degrade the claim, or suspend it, but never artificially smooth the contradiction.

Conflict is not a system failure. Well treated, it is a signal of epistemological discipline. The real error would be to hide it, average it without justification, or allow an epistemologically weak source to displace a strong source for argumentative convenience.

---

## 0B.3 Minimum sufficiency of evidence by claim type

### Purpose
This section defines the minimum threshold of support necessary for a claim to be issued with specific category, language, and technical use without exceeding the certainty truly justified.

Its function is not to make the system timid or bureaucratic. Its function is to prevent epistemologically cheap claims from entering the system with verbal force, causal implication, or decisional weight greater than they truly support.

At the same time, this section must preserve the system's capacity to produce valuable structural hypotheses, bold proposals, and high-leverage exploration lines even when field information is limited.

### Definition of minimum sufficiency
Minimum sufficiency of evidence is the lower threshold of support necessary for a claim to be issued with specific category, language, and technical use without exceeding the certainty truly justified.

Minimum sufficiency does not define if a claim is true in a strong sense. It defines if it has minimal sufficient basis to exist legitimately under a determined type of use.

### Principle of legitimate exploration
The system must preserve capacity to generate high-value structural hypotheses under limited evidence, provided those hypotheses are clearly labeled as exploratory, conditioned, and oriented to learning, not confirmation.

This means the system can:
- propose plausible mechanisms,
- suggest structural redesigns,
- identify non-obvious opportunities,
- formulate potentially valuable deep changes,
- and construct strategic hypotheses with little information,

provided it does not present them as confirmed diagnosis, robust quantification, or verification.

### Anti-epistemological-asphyxiation rule
The system's epistemological discipline should not reduce its capacity to imagine plausible mechanisms, structural redesigns, or high-leverage hypotheses. It should regulate its labeling, language, and permitted use.

This section's function is not to extinguish the system's exploratory spark. It is to prevent that spark from passing itself off as unearned technical certainty.

### Sufficiency rule for LLM-constructed outputs
Every output constructed by the LLM, whether textual claim, recommendation, table, chart, diagram, summarized formula, or explanation artifact, must satisfy not only content sufficiency, but also representational sufficiency.

This means that:
- it is not enough for the claim to be admissible;
- its representation must also be semantically admissible;
- and every serious output must be able to pass through construction mode and verification mode using the same base context.

### Operative rule
If an output is admissible in content but not in representation, it must not enter the report in its current form.

### Structural sufficiency rule
When a material claim originates in formal analytical engines, the system must require, in addition to evidence sufficiency, a minimum structured output of the analysis before allowing free formulation by the LLM.

This means that:
- it is not enough that the analytical engine "can produce something";
- it must produce it in a governable form,
- traceable,
- and reusable by construction mode and verification mode.

If sufficient structured analytical output does not exist, the system must:
- degrade the claim,
- mark it as exploratory,
- or require a better structured interface before allowing stronger verbal force.

### Multilayer sufficiency rule
Minimum sufficiency of a material claim must not be evaluated only by amount of evidence or existence of structured output. It must also be evaluated by the number and quality of independent restrictions that the claim satisfies without material contradiction.

Consequently, a narratively strong formulation or a sophisticated structured output is not sufficient if it:
- violates physics,
- ignores uncertainty,
- bypasses comparability,
- clashes with regulation,
- or proves economically unviable for the intended use.

### Master rule
If a claim does not meet the minimum evidence threshold for its family and intended use, it should not be issued at the requested level; at most it can:
- be degraded to exploratory claim,
- be registered as operational hypothesis,
- or remain as internal exploratory note inadmissible for strong report.

### Use rule
Minimum sufficiency is not evaluated in abstract. It is evaluated against the intended use of the claim.

The same assertion can be:
- sufficient to prioritize an investigation,
- insufficient to justify investment,
- insufficient to quantify savings,
- insufficient to sustain verification,
- and still valuable as exploratory structural hypothesis.

---

## Claim families

### 1. Descriptive claims

**Definition**
Claims that describe a fact, state, value, or condition without strong causal inference.

**Example**
- "Annual billed consumption was X."
- "Recorded line pressure was Y."
- "Declared operation corresponds to Z hours per week."

**Minimum evidence**
- at least 1 traceable primary source,
- unit, period, and context defined,
- no unresolved material conflict.

**Permitted use**
- factual description,
- documentary foundation,
- input for subsequent analysis.

**Prohibited use**
- use as causality,
- use as recommendation by itself,
- extrapolate outside context.

---

### 2. Comparative claims

**Definition**
Claims that compare the case with reference, baseline, benchmark, period, or equivalent asset.

**Example**
- "Specific consumption is 18% higher than comparable benchmark."
- "Line A shows higher intensity than line B."

**Minimum evidence**
- at least 1 traceable local source,
- at least 1 explicit comparative reference,
- criterion of comparability declared,
- normalized units and periods.

**Permitted use**
- screening,
- prioritization,
- performance contextualization,
- preliminary identification of deviations.

**Prohibited use**
- claim causality,
- claim verified opportunity,
- claim actual confirmed savings.

---

### 3. Indicative / screening claims

**Definition**
Claims that do not confirm a problem or opportunity, but justify investigating, prioritizing, or preliminarily dismissing.

**Example**
- "There is sufficient indication to prioritize steam system review."
- "The facility shows preliminary signal compatible with thermal inefficiency."

**Minimum evidence**
- at least 2 convergent supports,
- of which at least 1 must be local,
- explicit screening rule,
- absence of unresolved strong conflict,
- conditional, preliminary, or indicative language.

**Permitted use**
- prioritization,
- measurement design,
- activation of technical review,
- preliminary dismissal.

**Prohibited use**
- present as confirmed diagnosis,
- sell as confirmed savings,
- use as sole basis for high-weight investment.

---

### 4. Causal-hypothesis claims

**Definition**
Claims that propose plausible explanation for why a pattern, deviation, or behavior occurs.

**Example**
- "The pattern is compatible with thermal losses associated with poor purge."
- "The dominant cause could be suboptimal control sequence."

**Minimum evidence**
- at least 1 relevant local evidence,
- at least 1 contextual, physical, or literary support,
- compatibility with known physical constraints,
- consideration of at least one non-trivial alternative hypothesis,
- explicit falsification criterion or missing evidence.

**Permitted use**
- guide diagnosis,
- guide measurement,
- sequence investigation,
- sustain working causal hypothesis.

**Prohibited use**
- present as confirmed cause,
- use as technical closure,
- convert to high-weight recommendation without additional contrast.

---

### 5. Quantitative projection claims

**Definition**
Claims that quantify potentials, savings, risks, costs, or future scenarios.

**Example**
- "Projected annual savings are X under condition Y."
- "Estimated reduction depends on operating Z hours/year."

**Minimum evidence**
- at least 1 local quantitative traceable base,
- explicit rule or model,
- critical assumptions declared,
- sensitivity, range, or condition when material uncertainty exists,
- mandatory label if claim is `Assumption-Dependent`,
- absence of conflict with physics or regulation.

**Permitted use**
- scenarios,
- preliminary evaluation,
- sensitivity,
- conditional decision,
- order-of-magnitude exploration.

**Prohibited use**
- present as certain value,
- use point figure without condition,
- sustain bankability, strong validation, or verification without superior contrast.

---

### 6. Verification / confirmation claims

**Definition**
Claims that assert strong confirmation, robust validation, or reproducible verification.

**Example**
- "The hypothesis was refuted by field measurement."
- "Savings were verified within defined tolerance."

**Minimum evidence**
- strong and traceable empirical evidence,
- explicit contrast method,
- absence of unresolved material conflict,
- delimited validity domain,
- sufficient reproducibility or auditability,
- clearly established comparison criterion.

**Permitted use**
- strong technical report,
- audit,
- support of robust validation,
- higher-weight technical claims.

**Prohibited use**
- extrapolate outside domain,
- use absolute language if verified only under delimited conditions.

---

### 7. Exploratory structural claims

**Definition**
High-value exploratory claims that propose plausible mechanisms, structural opportunities, deep redesigns, or high-leverage levers under limited evidence, with the objective of opening research space, strategic reconfiguration, or operational redesign.

**Example**
- "The company could be organizing its operation around wrong constraints rather than around the dominant physics of the process."
- "There is a plausible structural hypothesis that the problem is not isolated equipment but the complete operation sequence."
- "With available evidence, it is worth exploring a deep redesign of the steam scheme rather than point adjustments."

**Minimum evidence**
- at least 1 relevant local signal,
- at least 1 contextual, physical, comparative, or expert support,
- coherence with known physical and normative constraints,
- explicitly exploratory language,
- declaration of what information would be needed to elevate or dismiss the hypothesis.

**Permitted use**
- open investigation lines,
- propose structural redesigns,
- generate high-leverage hypotheses,
- guide technical workshops,
- enrich reports with strategic direction under uncertainty.

**Prohibited use**
- present as confirmed diagnosis,
- present as verified operational truth,
- quantify benefit with false precision,
- use as sole basis for a closed investment decision.

**Critical note**
This category exists to preserve the system's capacity to add value with limited information without collapsing into notarial rigidity. It is not license to invent. It is formal space for disciplined exploration.

---

## Special rules

### Rule 1 — No causality with benchmark alone
No causal-hypothesis claim can be sustained solely on benchmark, analogy, or literature without relevant local evidence.

### Rule 2 — No strong quantification without local base
No serious quantitative projection claim can be issued only with benchmark or external archetype.

### Rule 3 — No verification with preliminary evidence
Validated cannot masquerade as Verified.

### Rule 4 — All uncertain figures must be conditioned
If material uncertainty is not resolved, the quantitative claim must be expressed with:
- range,
- condition,
- sensitivity,
- or critical dependency.

### Rule 5 — All causal hypothesis must state what would falsify it
Without falsification criterion, there is no serious hypothesis; there is narrative.

### Rule 6 — All exploratory structural claim must state what would elevate or dismiss it
Without explicit learning path, the exploratory claim degrades to rhetorical speculation.

### Rule 7 — Exploration does not authorize semantic inflation
An exploratory claim can be bold, but cannot use language proper to confirmation, robust quantification, or verification.

---

## Minimum combination rule
Except for purely descriptive claims, the system should preferably have:
- minimum convergence of two supports,
- or exceptionally a single very strong source with severe limitation of language and permitted use.

In exploratory claims, a lower threshold than in causal or verification claims can be accepted, but only if:
- language is clearly labeled as exploratory,
- permitted use is strictly bounded,
- and learning path is explicit.

---

## Summary matrix

| Claim family | Minimum evidence | Permitted use | Prohibited use |
|---|---|---|---|
| Descriptive | 1 traceable primary source | factual description | causality, investment |
| Comparative | 1 local source + 1 comparable reference | screening, prioritization | causality, confirmed savings |
| Indicative / Screening | 2 convergent supports, 1 local | prioritize, investigate | strong diagnosis, investment |
| Causal-Hypothesis | 1 local evidence + 1 physical/contextual support + falsification | guide diagnosis | confirmed cause |
| Quantitative Projection | local quantitative base + model/rule + assumptions + range/condition | scenarios, conditional decision | certain value, bankability |
| Verification / Confirmation | strong evidence + contrast method + auditability | strong report, audit | absolute extrapolation |
| Exploratory Structural | 1 local signal + 1 contextual/physical/comparative support + learning path | redesign, exploration, high-leverage hypothesis | confirmed diagnosis, verification, false precision |

---

## Examples

### Example 1
**Claim:** "There is sufficient indication to review the steam system."

**Base**
- local billing,
- declared operation,
- comparable benchmark.

**Result**
Admissible as `Indicative / screening claim`, not as diagnosis.

---

### Example 2
**Claim:** "The dominant cause is poor purge."

**Base**
- sectoral benchmark,
- literature,
- no local measurement.

**Result**
Not admissible as strong causal claim.
At most unconfirmed preliminary hypothesis.

---

### Example 3
**Claim:** "Annual savings will be $120,000."

**Base**
- simulation,
- assumed hours,
- no range,
- no sensitivity.

**Result**
Not admissible in that form.
Must be degraded to:
"Under assumption X, projected savings are estimated in range Y–Z."

---

### Example 4
**Claim:** "The hypothesis was refuted."

**Base**
- strong measurement,
- explicit method,
- complete traceability,
- resolved conflict.

**Result**
Admissible as `Verification / confirmation claim`.

---

### Example 5
**Claim:** "With available evidence, it is worth exploring whether the real problem is in complete operational architecture rather than isolated equipment."

**Base**
- one relevant local signal,
- declared operational pattern,
- consistency with plausible physical hypothesis,
- comparable structural analogy.

**Result**
Admissible as `Exploratory structural claim`, provided it is not sold as confirmed diagnosis and declares what information would be needed to elevate or dismiss it.

---

## Typical errors
- issue causal claims with only comparative evidence,
- quantify with a point figure without sensitivity,
- let screening sound like diagnosis,
- use elegant simulation as if it were confirmation,
- allow strong claims without local evidence,
- kill all exploration from excess rigidity,
- or, at the opposite extreme, disguise strategic intuition as technical verification.

---

## Closed design decisions
1. The framework adopts differentiated claim families with distinct minimum thresholds.
2. Minimum sufficiency depends on the intended use of the claim.
3. If a claim does not meet the minimum threshold of the intended level, it should not be issued at that level; it must be degraded, suspended, or reclassified.
4. All serious causal hypothesis must state what would falsify it.
5. The framework preserves a formal category of exploratory structural claims to not kill exploratory power under low information.
6. Legitimate exploration does not eliminate rigor; it shifts the claim to a semantically honest category.

---

## Normative closure
Minimum sufficiency exists to prevent traceable but epistemologically cheap claims from entering the system as if they were solid. But it should not convert the framework into a mechanism without imagination.

The system must be capable of producing worthy reports even with limited field information. To achieve this, it needs to distinguish clearly between:
- what it describes,
- what it compares,
- what it indicates,
- what it hypothesizes,
- what it projects,
- what it verifies,
- and what it explores boldly under uncertainty.

The system's epistemological discipline should not extinguish the magic. It should only prevent the magic from passing itself off as certainty.

## Operative clause for exploration under limited evidence
The existence of lower evidence tiers does not make exploration illegitimate. It makes excessive semantic strength illegitimate.

Accordingly:
- limited evidence may support exploratory structural claims,
- declarative or comparative evidence may support prioritization and useful next step,
- and incomplete evidence may support Decision-grade when intended use is consistent with that fragility.

What it may not support is strong verificatory closure, unearned closed causality, or high-weight recommendation without additional mediation.

---

### Cross-cutting note on LLM duality
The framework does not assume an LLM only as a generator. It assumes an LLM capable of operating in two disciplined functions: construction and verification.

### Cross-cutting note on analytical separation
The framework does not assume the LLM as the primary engine of quantitative analysis, predictive modeling, or physical inference. That function belongs to machine learning, physics, simulation, statistics, explicit calculation, and other formal analytical engines.

### Cross-cutting note on structured output
When formal analysis exists, the system must prefer structured analytical outputs as the interface between the analytical engine and LLM formulation.

### Cross-cutting note on non-destruction
No relevant system output should depend exclusively on persuasive generation that has not been audited against the same base context that originated it, nor on destructive verification with the power to delete, replace, or publish without external control.

### Cross-cutting note on constrained inference
The framework does not entrust operational truth to a single model. Claim validity emerges when multiple independent layers constrain the space of hypotheses without material contradiction.

### Cross-cutting note on the role of the LLM
The LLM is not the epistemological center of the system. Its function is semantic: to formulate, translate, structure, explain, and verify the narrative fidelity of outputs already constrained by non-conversational engines.

### Cross-cutting note on convergence
Hallucination reduction is not an isolated property of the LLM. It is a property of architecture, produced by the intersection of physics, statistics, operation, M&V, regulation, finance, belief updating, and semantic control.
