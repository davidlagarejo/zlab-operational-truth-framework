# Block 0E — Epistemic traceability

> Document subordination note
>
> This document is a subordinate companion document of Phase 0. The Phase 0 Master Governance Document is the canonical source of operative interpretation. If this file preserves older, broader, or partially inconsistent wording, the Master Document prevails.

## 0E.1 Epistemic traceability schema

### Purpose
This section defines the minimum mandatory schema of epistemic traceability for the framework. Its function is to ensure that no material claim, output, or artifact exists only as readable final formulation, but as a reconstructible, auditable, and governable object.

Epistemic traceability must not be understood as a passive event log. It must operate simultaneously as:
- log,
- technical sheet,
- state history,
- dependency tree,
- and audit dossier.

Its objective is to allow reconstruction of:
- how an object was born,
- what supports it,
- what limits it,
- how it changed,
- and what depends on it.

### Definition of traceable object
A traceable object is any claim, recommendation, explanation artifact, table, chart, diagram, narrative output, or material result whose existence may affect:
- interpretation,
- prioritization,
- validation,
- decision,
- or technical defense,

and which therefore must be reconstructible from evidence, transformations, restrictions, and explicit states.

A traceable object is not just a piece of content. It is a governed unit whose formal existence inside the system requires:
- identifiable support,
- explicit relationships,
- declared epistemological state,
- reconstructible limits,
- and capacity for later review.

### Master rule
Nothing material enters the serious system only as final text. Every material output must exist as a traceable object.

Accordingly:
- a final formulation without governed object is not a serious claim,
- an artifact without reconstructible reference is not a serious artifact,
- and a material output without traceable dossier is not admissible as a formal system output.

### Minimum families of traceable object
The framework adopts exactly three minimum families of traceable object:

1. `Claim Object`
2. `Output Object`
3. `Artifact Object`

These three families are not interchangeable.

It must remain explicit that:
- not everything traceable is a claim,
- a material table is not only presentation,
- a material chart is not only visualization,
- a material executive paragraph is not only narrative,
- and a material diagram is not only communication support.

Every material piece must be governed within the corresponding family.

### Claim Object — Minimum schema
Every `Claim Object` must include, at minimum, the following fields:

- `claim_id`
- `claim_text`
- `claim_family`
- `source_status`
- `knowledge_mode`
- `validation_status`
- `output_mode`
- `intended_use`
- `domain_of_validity`
- `evidence_refs`
- `structured_analytical_output_refs`
- `constraints_applied`
- `assumptions_used`
- `transformation_rules`
- `conflicts_open`
- `evidence_strength`
- `multilayer_convergence_status`
- `explanatory_format_used`
- `construction_output_ref`
- `verification_review_ref`
- `promotion_status`
- `downgrade_triggers`
- `suspension_conditions`
- `last_updated`
- `human_review_required`

#### Critical field: `claim_family`
`claim_family` is not a decorative label. It determines the technical nature of the claim and, therefore:
- its sufficiency threshold,
- its permitted grammar,
- its review standard,
- its eligibility for epistemological promotion,
- and its main overassertion risk.

Without `claim_family`, the system cannot discipline the distinction between:
- descriptive claim,
- comparative claim,
- hypothetical-causal claim,
- conditioned quantitative claim,
- exploratory structural claim,
- verificatory claim,
- or non-confirmation claim.

#### Critical field: `multilayer_convergence_status`
`multilayer_convergence_status` records the state of convergence of the claim against relevant independent layers of restriction.

It must not be reduced to a simple binary. It must at least allow identifying whether the claim:
- converges sufficiently,
- converges partially,
- has open conflict,
- or depends on still-fragile convergence.

This field is critical because it prevents the claim from appearing strong only because of local evidence or narrative formulation. Its function is to record whether the claim already survives the real intersection among:
- evidence,
- structured analytical output,
- physics,
- statistics,
- operation,
- regulation,
- M&V,
- finance when applicable,
- and semantic review.

#### Operative rule
The `Claim Object` functions as much more than a log. It is the governing unit of the claim's epistemic dossier.

### Output Object — Minimum schema
Every `Output Object` must include, at minimum, the following fields:

- `output_id`
- `output_type`
- `output_text_or_spec_ref`
- `parent_claim_ids`
- `output_mode`
- `shared_context_id`
- `structured_analytical_output_refs`
- `semantic_goal`
- `target_audience`
- `format_type`
- `construction_version`
- `verification_status`
- `verification_findings_ref`
- `correction_required`
- `human_review_required`
- `approved_for_report`
- `rejection_reason_if_any`
- `last_updated`

#### Critical field: `output_type`
`output_type` defines what class of output the object is and, therefore, which specific risks must be reviewed.

It does not equal superficial format. It must distinguish among outputs such as:
- narrative_output,
- executive_summary,
- recommendation_output,
- verification_statement,
- annex_section,
- table_output,
- chart_caption,
- review_note,
- or equivalent structured output.

Its function is to permit differentiated governance of semantic risk, intended use, and required control level.

#### Critical field: `shared_context_id`
`shared_context_id` identifies the common contextual package over which construction view and verification view of the same output must operate.

This field is critical because it prevents:
- review against alternative context,
- arbitrary degradation,
- inconsistent reconstruction,
- and loss of traceability between formulation and review.

Every material output reviewed by the LLM must be able to demonstrate that construction and verification occurred over the same base context.

#### Operative rule
The `Output Object` governs the formal existence of the material formulation, not of the underlying claim. Its function is to register how the output was constructed, reviewed, accepted, corrected, or rejected.

### Artifact Object — Minimum schema
Every `Artifact Object` must include, at minimum, the following fields:

- `artifact_id`
- `artifact_type`
- `artifact_purpose`
- `linked_claim_ids`
- `source_refs`
- `structured_analytical_output_refs`
- `visual_semantics`
- `allowed_interpretation`
- `prohibited_interpretation`
- `domain_of_validity`
- `assumptions_visualized`
- `constraints_visualized`
- `construction_spec_ref`
- `verification_review_ref`
- `artifact_risk_level`
- `semantic_overreach_risk`
- `requires_human_review`
- `approved_for_report`
- `last_updated`

#### Critical field: `visual_semantics`
`visual_semantics` defines which semantic relations the artifact communicates by its own visual form.

This field must explicitly record whether the artifact represents:
- comparison,
- sequence,
- hypothesis,
- contrast,
- measured vs expected difference,
- before vs after,
- dependency structure,
- or only tentatively suggested causality.

Its function is to prevent the artifact from communicating more than the underlying claim authorizes.

#### Critical field: `allowed_interpretation`
`allowed_interpretation` defines which reading of the artifact is legitimate.

It must not remain implicit. It must specify what a competent reader may infer without overextending support. Its function is to limit valid reading of the artifact within:
- its domain,
- its purpose,
- and the epistemological level of the linked claims.

#### Critical field: `prohibited_interpretation`
`prohibited_interpretation` defines which reading must be considered semantically improper even if the visual may induce it.

This field is indispensable for artifacts with overreading risk because:
- a chart may sound more closed than the claim,
- a diagram may look causal when it was exploratory,
- and a table may look exhaustive when it was only comparative.

Without `prohibited_interpretation`, the artifact remains semantically under-governed.

#### Operative rule
The `Artifact Object` governs the artifact as a material semantic unit, not as a mere image or table. It must make explicit what it represents, what it does not represent, and under which limits it is admissible.

### Rule of inheritance between objects
An `Output Object` or `Artifact Object` must never have greater epistemological strength than the `Claim Objects` on which it depends.

Every output or artifact inherits, at minimum:
- domain,
- limits,
- conflict,
- restrictions,
- critical assumptions,
- and possibility of degradation.

Accordingly:
- if the claim is downgraded, the linked output must be re-evaluated;
- if the claim is suspended, the linked artifact may not continue behaving as admissible;
- if the claim changes domain, both output and artifact must be revalidated for that new scope;
- and if the claim keeps open conflict, no derived object may appear to show clean closure.

### Rule of reconstruction
Every traceable object must allow reconstruction, at minimum, of:

1. what it said or showed;
2. where it came from;
3. which restrictions limit it;
4. which assumptions sustain it;
5. which review it received;
6. and what could degrade or invalidate it.

If this minimum cannot be reconstructed, the object does not meet the epistemic traceability threshold required by the framework.

### Rule of obligatoriness
Not every casual text needs full schema.

But every material object does.

A material object is any object that may affect:
- prioritization,
- interpretation,
- recommendation,
- validation,
- decision,
- audit,
- or relevant executive reading.

Accordingly:
- an informal internal note may not require a full dossier;
- a serious claim does;
- a material executive paragraph does;
- a table used to sustain technical reading does;
- a contrast chart does;
- and a material explanatory diagram does.

### Rule of traceable duality
For any material LLM output there must be explicit traceability of:
- `construction view`
- `verification view`

Both must point to the same `shared_context_id`.

This implies that:
- it is not enough to store the final formulation;
- it is not enough to store only the review verdict;
- and it is not enough to keep partial traceability of only one of the two modes.

LLM duality is governable only if it remains traced in explicit objects and not as invisible system behavior.

### Rule of no invisibility
No:
- correction,
- degradation,
- rejection,
- or promotion

may occur without leaving trace in one of these objects.

No silent overwrite.  
No invisible auto-rewrite.  
No material change without versioning.

Every material mutation of an object's state, formulation, scope, or admissibility must remain recorded:
- in its corresponding object,
- in its relevant cross-reference,
- and in its review or update history.

### Summary table

| Object | Function | Critical minimum fields |
|---|---|---|
| Claim Object | govern the claim as the central epistemological unit | `claim_id`, `claim_text`, `claim_family`, `source_status`, `knowledge_mode`, `validation_status`, `domain_of_validity`, `evidence_refs`, `structured_analytical_output_refs`, `multilayer_convergence_status`, `promotion_status`, `verification_review_ref` |
| Output Object | govern the material formulation of the claim or set of claims | `output_id`, `output_type`, `parent_claim_ids`, `output_mode`, `shared_context_id`, `semantic_goal`, `construction_version`, `verification_status`, `verification_findings_ref`, `approved_for_report` |
| Artifact Object | govern visual or explanatory artifacts as material semantic units | `artifact_id`, `artifact_type`, `linked_claim_ids`, `visual_semantics`, `allowed_interpretation`, `prohibited_interpretation`, `domain_of_validity`, `construction_spec_ref`, `verification_review_ref`, `semantic_overreach_risk`, `approved_for_report` |

### Normative closure
Epistemic traceability is not an optional annex. It is the minimum condition for sustaining serious claims, auditable outputs, and explanatory artifacts inside the framework.

Its function is not reduced to registering events. It must operate as log + technical sheet + history + dependency tree + audit dossier.

Without this schema:
- the claim becomes irreconstructible,
- the output becomes opaque,
- the artifact becomes semantically dangerous,
- and the system's epistemological discipline degrades into narrative without dossier.

Therefore, no serious technical intelligence system within ZLab may admit material outputs outside an explicit schema of epistemic traceability.

---

## 0E.2 Claim lifecycle governance

### Purpose
This section defines formal governance of the claim lifecycle within the framework. Its function is to establish how a claim is born, changes, rises, falls, is suspended, rejected, retired, or reactivated under explicit rules of entry, persistence, and exit.

Its objective is to prevent:
- claims active by inertia,
- claims promoted by rhetoric,
- claims degraded without trace,
- claims retired but still circulating,
- and zombie claims that continue affecting outputs or artifacts without retaining legitimate basis for activity.

### Definition of claim lifecycle
Claim lifecycle is the governed set of states, transitions, and conditions under which an assertion enters the system, remains active, changes regime or status, degrades, is suspended, rejected, retired, or reactivated as a function of new evidence, conflict, review, or context change.

Lifecycle does not equal:
- `validation_status`,
- `knowledge_mode`,
- nor `output_mode`.

It operates in a separate logical dimension called:
- `lifecycle_status`

### Master rule
A claim does not exist only because it was formulated. It exists while it retains sufficient conditions of support, traceability, coherence, and permitted use.

Accordingly:
- a claim may have been drafted and not be admissible;
- it may have been admissible and no longer be active;
- it may have been promoted and later degraded;
- and it may have been correct at one time and no longer remain current afterward.

### Minimum claim states
The framework adopts exactly the following nine minimum states for the `lifecycle_status` dimension:

1. `Drafted`
2. `Admitted`
3. `Active`
4. `Promoted`
5. `Degraded`
6. `Suspended`
7. `Rejected`
8. `Retired`
9. `Reactivated`

These states belong exclusively to the logical dimension of lifecycle.

They do not replace:
- `validation_status`
- `knowledge_mode`
- `output_mode`

### Permitted lifecycle events
The framework adopts exactly the following minimum events:

- `draft`
- `admit`
- `activate`
- `promote`
- `degrade`
- `suspend`
- `reject`
- `retire`
- `reactivate`

Every event must record, at minimum:
- `timestamp`,
- `trigger`,
- `actor_or_engine`,
- `rationale`,
- `associated_evidence`,
- and `impact_on_dependent_outputs`.

No material transition is allowed without traced event.

### Entry rule
A claim may pass from `Drafted` to `Admitted` only if it meets minimum admission:

1. it has `claim_id`;
2. it has `claim_family`;
3. it has `intended_use`;
4. it has minimum traceable support;
5. it has explicit restrictions and assumptions;
6. and it does not depend exclusively on free narrative that cannot be reconstructed.

If these conditions are not met, the claim must not enter as a serious system claim.

### Persistence rule
A claim may remain in `Active` only while it retains:
- sufficiency for its use,
- coherence with relevant restrictions,
- valid traceability,
- and absence of material conflict that destroys its admissibility.

It may not remain active by inertia.

Persistence requires continuous review of:
- support,
- domain,
- conflict,
- dependence on assumptions,
- and validity of intended use.

### Promotion rule
A claim may pass to `Promoted` only if its epistemological support materially changes, not only its presentation.

Every promotion must explicitly record:
- from which state it exits,
- to which state or regime it enters,
- what changed,
- which evidence or convergence justifies it,
- and which part of the claim was actually promoted.

Promotion is not allowed through:
- stronger drafting,
- better visualization,
- greater documentary density,
- nor narrative persuasion of the output.

### Degradation rule
A claim degrades when it remains usable, but no longer supports the same level of force, scope, regime, or permitted use.

Degrading is not failing. It is epistemological discipline.

Degradation must be applied when:
- support strength drops,
- fragility due to assumptions rises,
- partial conflict appears,
- multilayer convergence decreases,
- or intended use becomes more demanding than the support actually available.

### Suspension rule
A claim must be suspended when unresolved material conflict exists, critical evidence is missing, domain has become uncertain, or current use is no longer honestly sustainable.

While `Suspended`:
- it may not feed strong recommendation,
- it may not sustain technical closure,
- and it must declare what would reactivate or resolve it.

Suspension does not equal falsity. It equals temporary inadmissibility for serious use while the relevant rupture persists.

### Rejection rule
A claim is rejected when:
- it does not reach minimum admission,
- it is inadmissible for its intended use,
- it violates fundamental restrictions,
- or its structure is defective in a way not salvageable by simple degradation.

`Rejected` is not a pause. It is formal exclusion of the claim as a serious unit in its current form.

### Retirement rule
A claim is retired when:
- it no longer applies to the current context,
- it was replaced,
- its time window ended,
- or keeping it alive would induce interpretive error.

`Retired` does not mean false. It means no longer current.

Retirement protects against improper persistence of claims that were once admissible but should no longer continue circulating as active.

### Reactivation rule
A suspended or retired claim may be reactivated only if there appears:
- new evidence,
- new context,
- new measurement,
- new methodological review,
- or sufficient new multilayer convergence.

Reactivation must remain traced as an explicit event.

No implicit reactivation exists through simple narrative reuse of an old claim.

### Relation with outputs and artifacts
Every material `Output Object` and `Artifact Object` must depend on claims with explicit `lifecycle_status`.

If a claim changes state:
- its dependent outputs must be reevaluated;
- its associated artifacts may require degradation, retirement, or reconstruction;
- and no derived object may automatically retain admissibility that the claim already lost.

The relation between claim and derived object is not only referential. It is hereditary and operationally binding.

### Rule of no zombification
A zombie claim is a claim that continues circulating in outputs or artifacts even though it no longer retains conditions of legitimate activity.

The framework must prevent zombie claims.

Every non-active claim must:
- block,
- degrade,
- or retire

the outputs that materially depend on it.

It is not permitted that:
- a `Suspended` claim keeps sustaining strong recommendation,
- a `Rejected` claim keeps appearing as serious basis,
- or a `Retired` claim keeps circulating as current without explicit reactivation.

### Numeric encoding and auxiliary scores

#### 1. `lifecycle_state_code`
`lifecycle_state_code` is a technical numeric code of the claim's state.

Its function is:
- system logic,
- filters,
- validations,
- transitions,
- and flow control.

It must not be treated as a linear truth scale nor as a serious score for mathematical analysis.

Admissible coding example:
- Drafted = 10
- Admitted = 20
- Active = 30
- Promoted = 40
- Degraded = 50
- Suspended = 60
- Rejected = 70
- Retired = 80
- Reactivated = 90

#### 2. `epistemic_strength_score`
`epistemic_strength_score` represents the epistemological strength of the claim.

It may be used for serious mathematical operations provided its construction is explicit, traceable, and consistent with the framework's epistemological architecture.

#### 3. `actionability_score`
`actionability_score` represents the claim's current practical usefulness for deciding, prioritizing, sequencing, or activating action.

It does not automatically equal epistemological strength. A claim may be highly actionable and not be verificatory; it may also be technically strong and only weakly actionable in a given context.

#### 4. Optional scores
The framework may also use, when useful:
- `conflict_penalty`
- `convergence_score`

These scores must remain explicitly separate from the logical dimension of claim state.

#### 5. Critical rule
`lifecycle_state_code` must never be used as the only number for deciding.

Categorical states must never be averaged as if they measured truth.

Logical state, epistemological strength, and decisional usefulness are distinct dimensions.

### Summary table

| State | What it means | Permitted use |
|---|---|---|
| `Drafted` | claim formulated but not yet formally admitted | preliminary internal work, not yet serious claim |
| `Admitted` | claim that meets minimum entry and enters the serious system | analysis, review, construction, and eventual activation |
| `Active` | claim currently usable for its permitted use | may sustain outputs and artifacts within its limits |
| `Promoted` | claim whose support materially rose in level | may operate in stronger regime or scope, always delimited |
| `Degraded` | claim still usable but with lower force, scope, or permitted use | reduced use, weaker language, mandatory dependency review |
| `Suspended` | claim temporarily unsustainable due to conflict, critical lack, or relevant uncertainty | may not sustain strong recommendation nor technical closure |
| `Rejected` | claim inadmissible in its current form | excluded as serious claim |
| `Retired` | claim no longer current for present context | must not circulate as active claim unless explicitly reactivated |
| `Reactivated` | previously suspended or retired claim that re-enters through sufficient new support | may return to evaluation, activation, or promotion depending on case |

### Normative closure
Lifecycle governance prevents zombie claims, overextended claims, and claims active by inertia.

Its function is to discipline the temporal, operational, and epistemological existence of the claim inside the serious system.

Claim state must be understood as a logical dimension distinct from:
- epistemological strength,
- operational usefulness,
- and narrative formulation.

Without explicit lifecycle governance, traceability degrades, outputs inherit obsolete support, and the framework loses disciplined self-correction capacity.

---

## 0E.3 Governance of outputs and artifacts

### Purpose
This section defines how outputs constructed by the LLM and material explanation artifacts of the system are governed, separately but dependently on the underlying claim.

The reader does not see abstract claims; the reader sees concrete outputs. Therefore, the visible interface also needs epistemological discipline.

This block exists to prevent:
- orphan artifacts,
- outdated tables,
- inflated captions,
- charts that survive fallen claims,
- and old narratives attached to new states.

### Definition of output governance
Output governance is the set of rules that governs construction, review, approval, correction, degradation, rejection, retirement, or internal/external publication of every material output formulated by the LLM.

Its object is not the claim in the abstract, but the concrete form in which that claim appears before:
- technical reader,
- executive reader,
- auditor,
- reviewer,
- or decision-maker.

### Definition of artifact governance
Artifact governance is the set of rules that governs admissibility, semantics, dependency, review, overreading risk, validity, and reportable use of tables, charts, diagrams, annotated images, or material representations of the system.

Its function is to ensure that no artifact communicates more closure, more precision, or more causality than actually permitted by the claims and restrictions on which it depends.

### Master rule
No material output or artifact may be considered current only because it was built. It must preserve compatibility with the claim on which it depends, with its current state, and with its active restrictions.

Accordingly:
- prior existence does not confer validity,
- visual quality does not confer admissibility,
- and prior approval does not guarantee future use if the base claim changed.

### Canonical model of visible governance
For visible system objects, four dimensions must remain explicitly separated:
- `validation_status`: epistemic state of the claim;
- `lifecycle_status`: logical state of the claim;
- `review_outcome`: result of semantic review;
- `publication_status`: visible state of use of the output or artifact.

The legacy aliases `output_lifecycle_status` and `artifact_lifecycle_status` must be understood as older forms of `publication_status`, not as new families.

### Visible state of outputs
The framework adopts one shared dimension:
- `publication_status`

with this canonical vocabulary:

1. `Drafted`
2. `Reviewed`
3. `Approved`
4. `Approved_with_Limits`
5. `Blocked`
6. `Deprecated`
7. `Retired`
8. `Historical`
9. `Rebuilt`

#### Operative meaning
- `Drafted`: the output was formulated but does not yet have approval for use.
- `Reviewed`: the output already received semantic review or equivalent.
- `Approved`: the output is admissible for the defined use.
- `Approved_with_Limits`: the output is usable only with explicit limits or warnings.
- `Blocked`: the output may not be used operationally.
- `Deprecated`: the output still exists, but is no longer the preferred version.
- `Retired`: the output must no longer be used operationally.
- `Historical`: the output is kept only for audit, comparison, or traceability.
- `Rebuilt`: the output was rebuilt as a new version due to material change of base or form.

### Visible state of artifacts
Artifacts use the same `publication_status` dimension, although in practice their most frequent states will be:
- `Drafted`
- `Reviewed`
- `Approved`
- `Approved_with_Limits`
- `Blocked`
- `Retired`
- `Historical`
- `Rebuilt`

#### Operative meaning
- `Drafted`: artifact built but not sufficiently reviewed.
- `Reviewed`: artifact reviewed in its visual semantics.
- `Approved`: artifact admissible for reportable use.
- `Approved_with_Limits`: artifact admissible only under explicit limits.
- `Blocked`: artifact not admissible for current use.
- `Retired`: artifact out of operational validity.
- `Historical`: artifact retained only for audit, comparison, or traceability.
- `Rebuilt`: artifact formally rebuilt as a new version.

### Rule of dependency on claims
Every material `Output Object` and `Artifact Object` must be explicitly linked to one or more active or admissible `Claim Objects`.

The following are not permitted:
- outputs without `parent_claim_ids`,
- artifacts without `linked_claim_ids`,
- nor material objects whose epistemological base cannot be reconstructed.

Dependency on claims is not an optional documentation link. It is the minimum condition of admissibility of the visible object.

### Rule of automatic reevaluation
If a claim changes state, the system must automatically evaluate its dependent outputs and artifacts.

At minimum:
- claim promoted → review whether output/artifact should increase scope or remain delimited;
- claim degraded → review whether output/artifact should change language, category, or format;
- claim suspended → block dependent material outputs and artifacts;
- claim retired → retire or historize dependent outputs/artifacts;
- claim reactivated → does not automatically reactivate old outputs; it requires review or reconstruction.

Output validity may not be decoupled from claim validity.

### Rule of output admissibility
A material output may pass to `Approved` only if it simultaneously:

1. has valid `parent_claim_ids`;
2. its base claim is at least `Admitted` and usable for that purpose;
3. it passed through verification mode or equivalent review;
4. it does not semantically exceed the base claim;
5. it does not hide critical limits;
6. it does not contradict active restrictions;
7. and its format is context-adequate.

An output may be `Reviewed` without being `Approved`.

### Rule of artifact admissibility
A material artifact may pass to `Approved` or `Approved_with_Limits` only if it simultaneously:

1. has clear `linked_claim_ids`;
2. its visual semantics are explicit;
3. it does not represent hypotheses as confirmed facts;
4. it does not appear more precise than available support allows;
5. `allowed_interpretation` and `prohibited_interpretation` are defined;
6. it passed sufficient semantic review;
7. and its use adds real explanatory value.

A pretty artifact is not an admissible artifact.

### Rule of blocking
An output or artifact must pass to `Blocked` when:
- its base claim is suspended or rejected;
- it induces material misinterpretation;
- it exaggerates claim scope;
- it visualizes unsupported causality;
- it loses traceability;
- or it cannot be reconstructed from its shared context.

`Blocked` means:
- do not use in report,
- do not use in strong recommendation,
- do not use as decision support.

### Rule of retirement
An output or artifact must be retired when:
- it was replaced by a later version;
- the base claim is no longer current;
- its context no longer applies;
- or keeping it visible would induce error.

The following must be explicitly distinguished:
- `Deprecated` = no longer the preferred version;
- `Retired` = must no longer be used operationally;
- `Historical` = retained only for audit or traceability.

### Rule of mandatory reconstruction
Not every change must edit the object. Some changes require full reconstruction.

Minimum reconstruction triggers are:
- the base claim materially changes;
- the domain changes;
- the visual semantics change;
- the target audience materially changes;
- the epistemological regime changes;
- the underlying structured analytical output changes.

Every rebuilt object must remain as a new version (`Rebuilt`), not as silent overwrite.

### Rule of divergence between output and claim
It may occur that the claim remains admissible, but the output or artifact does not.

The system must allow blocking the output without automatically invalidating the claim.

Minimum divergence examples:
- misleading chart with valid claim;
- inflated caption with valid claim;
- table mixing verified with exploratory;
- executive summary that overextends the result.

Divergence between representation and claim is not inconsistency of the framework. It is precisely the type of problem this block must govern.

### Rule of visible / technical layers
A client-facing output may be more natural and simple.

A technical artifact may be denser and more audit-friendly.

But visible simplification does not authorize loss of:
- claim linkage,
- limits,
- traceability,
- nor semantic discipline.

The visible layer may simplify form. It may not degrade epistemological governance.

### Summary table

| Object | Minimum states | What governs it |
|---|---|---|
| Output | `Drafted`, `Reviewed`, `Approved`, `Approved_with_Limits`, `Blocked`, `Deprecated`, `Retired`, `Historical`, `Rebuilt` | dependency on claim, semantic review, adequate format, active limits, traceability, and reconstructibility |
| Artifact | `Drafted`, `Reviewed`, `Approved`, `Approved_with_Limits`, `Blocked`, `Retired`, `Historical`, `Rebuilt` | visual semantics, allowed/prohibited interpretation, dependency on claim, overreading risk, contextual validity, and reconstruction |

### Canonical examples

#### Case 1 — Output constructed but not approved
An executive summary was correctly formulated, but it has not yet passed verification mode and still does not declare critical claim limits.

**Result:** `Drafted` or `Reviewed`, but not `Approved`.

#### Case 2 — Output blocked by suspended claim
A strong recommendation still references a claim that moved to `Suspended` due to unresolved material conflict.

**Result:** the output must move to `Blocked`.

#### Case 3 — Artifact approved with limits
A measured-vs-expected chart correctly represents a contrast campaign limited to Line A, but its valid interpretation is limited to those operating conditions.

**Result:** `Approved_with_Limits`.

#### Case 4 — Artifact retired due to context change
An operational diagram was built for an earlier architecture already modified in field.

**Result:** `Retired` or `Historical`, depending on audit need.

#### Case 5 — Output or artifact rebuilt as new version
A material change in structured analytical output forces rebuilding of the technical annex and its summary table.

**Result:** new `Rebuilt` version, not silent edit.

#### Case 6 — Claim remains alive but output blocked for bad representation
The base claim remains valid, but the chart caption presents it as universal and definitive.

**Result:** the claim remains alive; the output is blocked for bad representation.

### Normative closure
Governance of outputs and artifacts exists to prevent the visible interface of the system from surviving separately from its epistemological base.

It is not enough for the claim to be serious.

The following must also be serious:
- tables,
- charts,
- diagrams,
- captions,
- and narratives

that represent it.

If the claim is governed but its outputs and artifacts are not, the framework preserves discipline in the base and loses it exactly where the reader needs it.

---

## 0E.4 Rules of upgrade / downgrade / suspend / reject

### Purpose
This section defines the explicit rules of state change for claims, outputs, and artifacts. Its function is to prevent the system from moving states by narrative intuition, visual preference, or operational convenience.

The risk is not only misclassifying once. The risk is also moving states badly:
- promoting too early,
- degrading without justification,
- suspending when limiting scope would have been enough,
- rejecting when rebuilding would have been enough,
- or failing to reject when the object is already inadmissible.

### General principle of state change
No traceable object should change state by narrative intuition, stylistic preference, or operational convenience. Every state change must be triggered by an explicit, traceable condition compatible with the applicable epistemological regime.

This implies that:
- nothing rises by enthusiasm,
- nothing falls by aesthetic discomfort,
- nothing is suspended by rhetorical over-caution,
- and nothing is rejected merely to “clean up” the system when a smaller and more honest intervention would suffice.

### Rule of upgrade
An object may receive `upgrade` when it gains enough support to:
- increase its epistemological strength,
- widen its permitted use,
- or rise in regime or status without violating traceability, convergence, and limits.

Typical triggers of `upgrade` are:
- new relevant evidence;
- better structured analytical output;
- resolution of material conflict;
- reduction of critical assumptions;
- better multilayer convergence;
- additional explicit contrast;
- successful semantic review over formulation that was previously limited.

`Upgrade` can never be based only on:
- better drafting,
- better visual design,
- more detail,
- or subjective operator confidence.

Minimum examples:
- **Claim:** rises from Decision-grade to Verification-grade because it gained strong local measurement, explicit contrast, and better multilayer convergence.
- **Output:** rises from `Approved_with_Limits` to `Approved` because it no longer overextends the base claim and its semantic review was satisfactory.
- **Artifact:** rises from `Approved_with_Limits` to `Approved` because visual ambiguity was resolved and its interpretation became fully bounded to the correct domain.

### Rule of downgrade
An object must receive `downgrade` when it remains usable, but no longer supports:
- the same strength level,
- the same scope,
- the same regime,
- or the same form of presentation.

Typical triggers of `downgrade` are:
- new evidence weakens the claim;
- a non-destructive but relevant conflict appears;
- multilayer convergence decreases;
- the validity domain narrows;
- the artifact overextends scope;
- the output remains useful, but no longer as it was formulated.

`Downgrade` does not mean failure. It means epistemological discipline.

It must be applied when system honesty requires lowering strength, scope, or interpretation without fully eliminating the object.

### Rule of suspend
An object must be suspended when it cannot be honestly sustained in its current form, but definitive rejection is not yet warranted.

Typical triggers of `suspend` are:
- unresolved material conflict;
- lack of critical evidence;
- temporary rupture of domain;
- pending review over a destructive point;
- unresolved relevant incompatibility between layers;
- ambiguity too large for current use.

`Suspended` implies:
- do not use as strong support;
- do not use for technical closure;
- do not use for high-weight recommendation;
- but keep traceability and the dossier open.

### Rule of reject
An object must be rejected when it is inadmissible for the intended use and cannot be reasonably saved through limitation, degradation, or suspension.

Typical triggers of `reject` are:
- epistemologically inadmissible claim;
- semantically defective output without clear salvage;
- artifact with unacceptable structural misreading risk;
- violation of fundamental restrictions;
- absence of minimum traceability;
- dependence on nonexistent or invented context;
- structure incompatible with the framework.

`Reject` does not necessarily mean false. It means inadmissible in that form and for that use.

### Rule of rebuild vs reject
The distinction must remain clear:

- `Rebuild` when the base remains salvageable, but the representation, structure, or formulation must be redone.
- `Reject` when the problem is one of structural admissibility or support.

Examples of `Rebuild`:
- chart correct in intention but with bad visual semantics;
- overextended executive summary still based on an admissible claim;
- table with mixed categories that can be restructured without losing the base.

Examples of `Reject`:
- claim without minimum traceable support;
- output built over nonexistent context;
- artifact that cannot delimit acceptable interpretation because its base is already inadmissible.

The critical rule is:
- rebuild when the problem lies in representation,
- reject when the problem lies in the base or in structural admissibility.

### Rule of partial downgrade
Not every downgrade affects the full object. Only one dimension of its structure, scope, or interpretation may need degradation.

The system must be able to degrade by components, not only by full object.

Minimum examples:
- the claim remains alive but loses strong causality;
- the chart remains alive but only with narrower domain;
- the table remains alive but one column must degrade to exploratory;
- the summary remains alive but one sentence must be removed or limited.

`Partial downgrade` requires that it remain explicit:
- which component goes down,
- which remains,
- and which new limit is introduced.

### Rule of propagation between objects
Every relevant state change must propagate downstream according to explicit material dependency.

At minimum it must cover:
- Claim → Output / Artifact
- Output / Artifact → Claim

Minimum consequences:
- claim upgrade may enable rebuilding or upgrade of outputs;
- claim downgrade obliges review of outputs;
- claim suspension blocks dependent outputs;
- claim retirement retires or historizes outputs.

It must also remain clear that a problem in an output does not automatically degrade the claim, but it may trigger:
- review,
- warning,
- rebuilding,
- or reevaluation of admissibility.

### Rule of minimum necessary severity
When an object presents a problem, the system must apply the minimum epistemologically honest intervention.

Recommended order:
1. limit / warning
2. downgrade
3. suspend
4. rebuild
5. reject
6. retire

Critical rules:
- Do not reject if downgrading is enough.
- Do not degrade if limiting is enough.
- Do not keep active if it should already be suspended.

The intervention must be severe enough to preserve epistemological honesty, but not more severe than necessary.

### Summary table

| State action | When it applies | What it means |
|---|---|---|
| Upgrade | when the object gains enough support and materially improves its base or admissibility | it may rise in strength, permitted use, or status without violating limits |
| Downgrade | when the object remains usable but no longer at the same strength, scope, or formulation | disciplined reduction of strength, scope, or interpretation |
| Suspend | when the object cannot be honestly sustained in current form but definitive rejection is not yet warranted | pause of strong use with traceability preserved |
| Reject | when the object is inadmissible for the use and cannot be reasonably saved | formal exclusion of that object form |
| Rebuild | when the base remains salvageable but representation or structure must be redone | reconstruction as new version, not structural rejection |
| Retire | when the object is no longer current or keeping it visible would induce error | operational exit of the object, with possible historical preservation |

### Canonical examples

#### Case 1 — Legitimate upgrade
A dominant-loss claim gains:
- new strong measurement,
- better structured analytical output,
- explicit contrast,
- and resolved conflict.

**Result:** legitimate `upgrade` of the claim and eventual upward review of dependent outputs.

#### Case 2 — Legitimate downgrade
An executive output remains useful, but new evidence limits the domain of the base claim to a single operating line.

**Result:** `downgrade` of the output by scope; the object remains, but under narrower semantics.

#### Case 3 — Legitimate suspend
A comparative artifact depends on a claim with unresolved material conflict between field evidence and relevant physical restriction.

**Result:** operational `suspend` or `block` of the artifact while the destructive point is resolved.

#### Case 4 — Legitimate reject
An output was built over invented context, without minimum traceability and without reconstructible base.

**Result:** `reject`. Limiting or semantically rebuilding a nonexistent base is not enough.

#### Case 5 — Rebuild instead of reject
A measured-vs-expected chart is well supported, but its axis, caption, and visual semantics induce unsupported causality.

**Result:** `rebuild`, not `reject`, because the base remains salvageable but representation must be redone.

#### Case 6 — Partial downgrade
A table mixes verificatory columns with still-exploratory columns.

**Result:** `partial downgrade`: the table may remain alive, but the exploratory column must be degraded, relabeled, or separated.

### Normative closure
The framework must not move states by narrative convenience. It must move them by explicit conditions of support, conflict, admissibility, and material dependency between objects.

Upgrade, downgrade, suspend, reject, rebuild, and retire are not editorial gestures. They are acts of epistemological governance. Their function is to preserve honesty, traceability, and proportionality across all material objects of the system.
