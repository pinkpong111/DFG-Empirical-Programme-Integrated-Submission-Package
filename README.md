# DFG Empirical Programme — Integrated Submission Package

**Version:** v1.0 (May 2026)
**Author:** Seol, Bin (Independent Researcher, ORCID 0009-0006-9530-4497)

---

## Executive Summary

The Deficit-Fractal Governance (DFG) framework proposes that coordination systems near governance criticality exhibit a bundle of recurring empirical signatures: cascade size distributions with characteristic exponents, logarithmic hierarchy scaling, capacity-limited module sizes, critical slowing down before transitions, and spectral-recovery relationships. This submission package presents the first systematic empirical programme testing these predictions across multiple scales, substrates, and observables.

**The programme produces a regime atlas of critical phenomena, not a theory validation or theory cemetery.** Through 24 cell-card-protocol experiment families (31 executable runs) and 8 targeted regime-search experiments, we demonstrate that cell-level Incompatibility typically reflects operationalisation, substrate, or protocol mismatch — not theory failure. All four originally-quarantined theory candidates now have at least one located or partially compatible operationalisation, and no theory family has yet met the programme's pre-specified global retirement threshold.

**This is NOT a collection of independent papers.** It is a single sequenced bundle. Documents must be read in order. Reading any B-paper without first reading the Compatibility Atlas (Document 01) risks misreading "Incompatible-in-cell" results as "theory falsified" — exactly the misreading this programme rejects.

---

## Package Contents (13 Files)

The following files are distributed across the individual Zenodo paper records and the separate reproducibility package record. They are listed here as one integrated submission package for navigation.

### Sequenced Documents — DOCX (7 papers)

| Order | File | Role | Paragraphs | Tables |
|---:|---|---|---:|---:|
| **01** | `01_Compatibility_Atlas_v1_3.docx` | **Methodology framework — required first.** Stage A/B/C failure decomposition, 6-status taxonomy, per-theory final state, regime-search outcomes. | 58 | 4 |
| **02** | `02_Paper_A_v3_1_Registry_Update.docx` | Operating manual. Tables 9–11 (H1/H2/H3/H4/H5 family registries), 12 regime-boundary entries, §6.10 Cross-Cell Consistency framework, §6.11 Regime-Search Methodology. Canonical programme state. | 124 | 9 |
| **03** | `03_Paper_B-H4_v2_Financial_CSD.docx` | Substrate-matched financial CSD. 7 crises × 13 series / 18 observables × 3 regions × null-FP-controlled. **Strongest empirical cell in the programme.** | 140 | 8 |
| **04** | `04_Paper_B-H5_v2_Spectral_Recovery.docx` | Spectral gap → dynamical recovery. Separates graph-topological λ₂ from dynamical-Jacobian λ₁. H5-γ Spearman 0.895 (session-level); subject-clustered bootstrap CI [0.489, 0.901]. | 188 | 7 |
| **05** | `05_Paper_B-Topology_v1_Containment.docx` | λ₂ as objective-dependent connectivity predictor. Random-attack robustness (Spearman +0.876) vs epidemic spread (+0.83, opposite direction). Paired with Document 04. | 107 | 5 |
| **06** | `06_Paper_B-H1_v3_Cascade_Regime_Map.docx` | Cascade exponent regime map. H1 decomposed into σ ≈ 1 operating-point (robust across 24 subjects, 5 substrates, 44 observations) and τ ≈ 3/2 exponent universality (quarantined; located synthetically in Manna+WS). **Most consequential reframing.** | 200 | 10 |
| **07** | `07_Cross_Cell_Consistency_Note.docx` | Technical note. Subject-level cross-cell consistency (sub-25273 in DANDI:001611) between H1-η and H5-γ pipelines. Proposes Paper A §6.10 framework. | 69 | 1 |

### Supporting Documents — Markdown (6 guides)

| Order | File | Role |
|---:|---|---|
| — | `README.md` | Package navigation and key claims summary |
| **00** | `00_READ_ME_FIRST_submission_guide.md` | Submission strategy, dependency graph, banned framings |
| 01a | `01a_Atlas_v1_0_methodology_preamble.md` | Atlas v1.0 initial methodology (optional historical context) |
| 01b | `01b_Atlas_v1_1_addendum.md` | Atlas v1.1 addendum: Rounds 12–14 search results |
| 01c | `01c_Atlas_v1_2_addendum.md` | Atlas v1.2 addendum: Rounds 15–17 search results |
| **08** | `08_MASTER_REPORT_audit_trail.md` | Complete reproducibility index for all 24 experiments (reference, not narrative) |

---

## Methodology: The Regime-Atlas Framework

### Core Principle

> **A failed cell is not a theory grave; it is a boundary marker for the next regime search.**

The DFG empirical programme is built on a single methodological insight: when a theoretical prediction fails an empirical test, three distinct failure modes must be separated before concluding that the theory itself is wrong:

| Stage | Failure type | Example | Response |
|---|---|---|---|
| **A** | Operationalisation mismatch | λ₂ used to predict recovery time (should be λ₁) | Re-operationalise |
| **B** | Regime mismatch | τ ≈ 3/2 tested in BTW sandpile (should be Manna conservative) | Regime search |
| **C** | Theory-level failure | Prediction fails after exhaustive Stage A+B search | Retire (threshold not reached for any DFG claim) |

### Cell-Card Protocol

Every experiment is pre-specified via a cell card (Paper A Appendix A) containing 12 mandatory fields: prediction family, operationalisation ID, scale, substrate, observable, data source, primary metric, compatible criterion, minimum sample, robustness grid, negative-result handling rule, and generalisation boundary. No experiment tests DFG as a whole; each tests one operationalisation inside one scale-substrate-observable cell.

### Status Taxonomy (6 levels)

| Status | Meaning |
|---|---|
| **Primary-supported** | ≥ 1 cell with substrate-matched observable, multi-evidence |
| **Primary-supported-in-regime** | Located in specific regime with multi-evidence |
| **Compatible-in-cell** | Single cell meets criteria |
| **Quarantined-universal** | Universal form unsupported; specific-regime form may be located |
| **Operationalisation-limited** | Tested operationalisation failed; theory family not retired |
| **Data-missing** | Protocol ready but no accessible data |

### Retirement Criteria (stringent)

A prediction family is retired within a scale-substrate category ONLY when: (a) ≥ 3 independent datasets tested, (b) ≥ 2 distinct operationalisations tested, (c) majority incompatible, (d) no methodological confound explains the pattern. **No DFG theory family has reached this threshold.**

---

## Key Empirical Results

### Six Located Regimes plus One Cross-Cell Consistency Signal

**1. H4-β: Substrate-Matched Financial Critical Slowing Down**
*(Paper B-H4, Document 03)*

Seven financial crises (1987–2020) tested against 13 source series / 18 observable transforms across US, EU, and Chinese substrate regions. Under substrate-matching (credit-crisis indicators for credit crises, sovereign-stress indicators for sovereign crises, FX indicators for EM crises):

- **6/7 crises detected at ≥75% with strong specificity** (null FP ≤ 25%)
- **ECB CISS achieves 0% null FP** across 44 robustness variants for Eurozone crises
- **Black Monday (1987):** 75% detection under 1-year matched window, but null FP = 42.5% (Exp 02h) — reclassified as Compatible-with-low-specificity-confidence
- **Key insight:** Financial CSD is not a universal one-indicator warning law; it is most reliably detectable when the stress observable's channel matches the crisis's primary substrate

**2. H5-γ: Jacobian Spectral-Radius Recovery Prediction**
*(Paper B-H5, Document 04)*

The recovery-time reading of H5 is a dynamical-system-recovery prediction (Jacobian λ₁), not a graph-topological prediction (Laplacian λ₂). Tested on synthetic linear/non-normal systems and real meso-neural cortical culture (DANDI:001611):

- **Spearman 0.895** (session-level n = 12, p = 8.4e-5)
- **Subject-clustered bootstrap 95% CI:** ridge [0.489, 0.901], DMD [0.500, 0.895]
- **DMD passes subject-level exact one-sided p = 0.042** (perfect rank ordering across 4 subjects)
- **H5-ζ (K = D/λ₁):** Definition locked with two complementary estimators; real-substrate D estimator pending

**3. H5-α/β Reframed: λ₂ as Objective-Dependent Connectivity Predictor**
*(Paper B-Topology, Document 05)*

Graph-Laplacian λ₂ does NOT predict dynamical recovery time (original H5-α/β framing). λ₂ measures structural connectivity strength, with objective-dependent consequences:

| Operationalisation | Spearman(λ₂, target) | Interpretation |
|---|---|---|
| Random-attack robustness | **+0.876** | High λ₂ helps (strongly connected → harder to fragment) |
| Percolation threshold | **+0.876** | High λ₂ helps |
| SIR epidemic final size | **+0.83** | High λ₂ hurts containment (strongly connected → easier spread) |
| Cascade halt time | **−0.80** | High λ₂ accelerates spread |
| Dynamical recovery | wrong sign | λ₂ does NOT predict (handed off to H5-γ) |

The "containment" label was overloaded. Three distinct outcomes had been conflated: structural robustness (λ₂ Compatible), spread containment (λ₂ strong but reversed sign), and dynamical recovery (λ₂ incompatible → H5-γ).

**4. H1 σ ≈ 1: Neural Operating-Point Criticality**
*(Paper B-H1, Document 06)*

H1 decomposes into two sub-claims that move differently:

- **σ ≈ 1 operating-point criticality:** Robust across **24 independent neural subjects across 5 substrates** (with in-vivo cohort additionally re-evaluated under 3 avalanche-detection protocols, yielding **44 subject × protocol observations**). Protocol C (LFP-band-equivalent) gives **σ = 1.00 exact** (10/10 subjects, cross-subject variance 0.02).
- **τ ≈ 3/2 exponent universality:** NOT supported in any tested neural data under any protocol. τ_tail consistently > 2. **Quarantined as universal claim.**

**5. Cascade Universality Joint Regime (Synthetic)**
*(Paper B-H1 §3.5b, Document 06; Exp 15 + 18)*

The joint GCUC criterion (τ ≈ 1.5 AND σ ≈ 0.87, within the [0.85, 1.15] band) is **located** in:
- **Manna conservative cascade rule** (not BTW dissipative)
- **Watts-Strogatz small-world topology** (p_rewire = 0.02)
- **Very low boundary dissipation** (f_diss = 0.003)

Finite-size scaling (Exp 18): σ is N-invariant within 0.01 across N ∈ [1000, 5000] — a true universality-class signature. This establishes non-vacuity and finite-size robustness of the GCUC regime, but does NOT show that tested biological neural systems occupy it.

**6. Intervention Paradox in Nonlinear Systems**
*(Paper A §H5 sub-family; Exp 14, 17, 19)*

Supported in 4/5 nonlinear model classes (logistic-cubic bistable, sigmoid saturation, delayed-control, resource-depleting; Spearman ∈ [−0.83, −0.61]). NOT supported in linear systems (Exp 14 counter-result).

**7. Cross-Cell Consistency Signal: Subject 25273**
*(Cross-Cell Consistency Note, Document 07)*

Subject sub-25273 (DANDI:001611) independently identified as the high-end anomaly in both H1-η (avalanche fitting) and H5-γ (Jacobian recovery) pipelines. Treated as supportive cross-cell consistency evidence at n = 4, not as compatibility propagation. This is a methodological signal, not a located regime and not a compatibility decision.

### Quarantined Claims (universal forms unsupported)

| Claim | Status | Located regime | What would resolve it |
|---|---|---|---|
| H1 universal τ ≈ 3/2 | Quarantined-universal | Synthetic Manna+WS only | Real organotypic raw-LFP avalanche data |
| One-indicator universal CSD | Quarantined | Substrate-matched form supported | More crisis types / regions |
| λ₂ as universal recovery predictor | Quarantined for recovery | Replaced by H5-γ Jacobian λ₁ | — (resolved by reframing) |
| Intervention Paradox in linear systems | Quarantined | Counter-result (Exp 14) | — (linear systems excluded) |

### Data-Missing Gaps (highest priority)

| Priority | Gap | Why it matters |
|---|---|---|
| 1 | H1-ε organisational cascade exponent | Never measured in any published study. DFG is a governance theory. |
| 2 | H3-α organisational capacity C calibration | Universal bottleneck for module-size testing |
| 3 | Real-substrate H5-ζ K = D/λ₁ | DFG-unique metric; D estimator substrate-gate |
| 4 | Organotypic raw-LFP avalanche replication | H1 τ ≈ 3/2 in real neural data |

---

## Regime-Search Sprint Summary (Rounds 12–19)

Eight targeted regime searches were conducted to test whether originally-quarantined theories could be rescued via operationalisation refinement or regime narrowing:

| Round | Theory | Search | Outcome |
|---|---|---|---|
| 12 | Cascade Universality | BTW narrow grid (80 cells) | τ-only located (15/80); σ not co-located |
| 13 | Topology Containment | Synthetic graph corpus | **Rescued:** λ₂ → robustness (Spearman 0.876) |
| 14 | Intervention Paradox | Linear systems | **Counter-result:** paradox absent in linear regime |
| 15 | Cascade Universality | Manna conservative | **★ Joint regime LOCATED** (τ ≈ 1.5, σ ≈ 0.87) |
| 16 | Topology Containment | Real SNAP networks | **Compatible:** epidemic spread (Spearman 0.83) |
| 17 | Intervention Paradox | Nonlinear bistable | **LOCATED** (Spearman −0.764) |
| 18 | Cascade Universality | Finite-size scaling | **Robust** across N = 1000–5000 |
| 19 | Intervention Paradox | 5 model classes | **4/5 nonlinear classes supported** |

**Aggregate: 8/8 searches produced informative results. No theory family has met the global retirement threshold. 4/4 originally-quarantined theories now have at least one located or partially compatible operationalisation.**

---

## Methodological Lessons

1. **A failed cell is not a theory grave.** Validated 4 times: Topology λ₂ → reframed as connectivity; Cascade BTW → Manna; Intervention linear → nonlinear; AGC → state-vector remap.

2. **Operationalisation choices matter more than theory truth.** Same theory, three operationalisations, three different outcomes (BTW 0/80 joint → Manna 2/24 joint → Manna at scale 4/5).

3. **Application direction matters.** λ₂ predicts epidemic spread positively — "λ₂ hurts containment" until reframed as "λ₂ measures connectivity, with objective-specific consequences."

4. **Linear-system tests can give counter-results that don't generalise.** Exp 14 linear Intervention Paradox failed; Exp 17+19 nonlinear succeeded across 4 model classes.

5. **Finite-size scaling is the defining test of regime location.** Exp 18 confirmed σ ≈ 0.87 invariant across factor-of-5 system size, distinguishing true SOC signature from accidental N-specific result.

6. **Substrate-matching resolves apparent detection failures.** Black Monday, EZ Debt, and China 2015 appeared as CSD failures under generic indicators; substrate-matched observables recovered detection for all three.

---

## Common Misreadings to Avoid

This package is a **regime atlas**, not a theory validation or theory cemetery. The following misreadings should be actively avoided:

- **Do NOT read "Incompatible-in-cell" as global theory falsification.** A failed cell is a boundary marker, not a theory grave. Theory-level retirement requires repeated incompatibility across exhaustively-searched rescue paths.

- **Do NOT treat located regimes as universal validation.** A single Compatible-in-regime cell does not validate the theory globally; it shows at least one viable operationalisation exists.

- **Do NOT compare τ values across substrates** without checking observable definition and protocol. Spike-population-rate, LFP-band peak detection, calcium events, and Manna conservative cascades are different observables.

- **Do NOT treat λ₂ as a generic resilience metric.** λ₂ measures graph connectivity; whether high λ₂ "helps" or "hurts" depends entirely on the objective (random-attack robustness vs epidemic containment have opposite signs).

- **Do NOT cite individual B-papers without citing the Compatibility Atlas methodology.** Each B-paper assumes the regime-atlas framing. Standalone citation risks theory-validation or theory-falsification framings, neither of which is the programme's intent.

- **Do NOT interpret "rescue" claims as DFG-unique discoveries.** Several located regimes re-confirm known results from established literature (Manna SOC, Chung spectral graph theory, linear stability theory). The DFG contribution is the systematic application-range mapping, not novel theoretical discovery.

---

## Reproducibility

### Dependencies

- Python 3.12+
- `numpy`, `scipy`, `pandas`, `numba`
- `pynwb` (DANDI experiments)
- `fredapi` (FRED experiments — free API key required)
- `networkx` (synthetic networks + SNAP)

### Real-Data Sources

| Source | Size | Access |
|---|---|---|
| FRED (18 series) | ~50 MB | `fredapi` (free tier, API key required) |
| ECB SDW (CISS daily 1980–) | ~5 MB | REST API (no key) |
| GH Archive (884K events) | ~200 MB | `urllib` |
| DANDI:001611 | ~480 MB | `pynwb` |
| DANDI:001603 | ~340 MB | `pynwb` |
| DANDI:000774 | ~1.3 GB | `pynwb` |
| SNAP graphs | ~5 MB | HTTP |

### Reproduction

```bash
# Fastest: synthetic experiment (~3 min)
cd 01_reproducibility/exp03_h5g_jacobian
py -3.12 run.py

# Real-data: FRED financial CSD (~5 min)
cd ../exp02b_h4b_null_windows
py -3.12 run.py

# Full Manna+WS finite-size scaling (~2 min)
cd ../exp18_manna_finite_size
py -3.12 run.py
```

**Total reproduction time:** ~5 hours end-to-end with cache regeneration. Synthetic-only: ~45 minutes.

### Experiment Count Reconciliation

| Count | What it includes |
|---|---|
| 24 experiment families | Exp 01 through 19 + sub-versions (a–g) + protocol comparisons |
| 31 executable runs | All sub-experiments that produce independent results |
| 37 reproducibility directories | Experiment dirs + 6 protocol scaffold dirs (Tier 2–5c) |

---

## Programme Statistics

| Metric | Value |
|---|---|
| Total experiments | 24 families (31 runs) + 6 scaffolds |
| Documents | 7 DOCX papers + 6 markdown guides = 13 files |
| Total paragraphs | 886 (DOCX only) |
| Total tables | 44 (DOCX only) |
| Real-data sources | FRED, ECB SDW, GH Archive, DANDI (4 datasets), SNAP |
| Located regimes | 6 Compatible-in-regime + 1 cross-cell consistency signal |
| Quarantined claims | 4 (universal forms; specific-regime forms located) |
| Theories retired | **0** |
| Runtime | ~280 min real-data computation (one-time) |

---

## How to Cite

**Whole programme:**
> Seol, B. (2026). DFG Empirical Programme: A Regime Atlas of Critical Phenomena Across 24 Targeted Cell-Card Experiments. Working paper, May 2026.

**DOI-based citation:**
> Each document in this package has an individual Zenodo record. For formal citation, use the DOI of the specific document. For programme-level framing, cite Document 01 (Compatibility Atlas) together with the relevant B-paper.

**Specific paper:**
> Seol, B. (2026). [Paper title]. In *DFG Empirical Programme Submission Package*. Working paper, May 2026.

---

## Final Operating Principle

> **The DFG empirical programme has, across 24 experiments and 8 targeted regime searches, produced 0 theory-family-level global retirements and 6 located regimes and 1 cross-cell consistency signal. The methodology of cell-card protocol + status-not-retirement + targeted regime search is empirically supported. The programme is now in regime-atlas mode: documenting where each prediction holds, where it doesn't, and what rescue paths remain unsearched.**

---

**End of Integrated README. Begin reading at Document 01 (Compatibility Atlas).**
