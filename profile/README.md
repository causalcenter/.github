# Center for Dynamic Causality

The Center for Dynamic Causality is an independent research organization dedicated to the study of **dynamic causality**. The Center works in three research areas: Dynamic Causality, Counterfactual CFD, and Dynamic Knowledge.

## Research Pillars

**1. Dynamic Causality.** Materialized as [DeepCausality](https://deepcausality.com), the reference implementation of the [Effect Propagation Process (EPP)](https://github.com/deepcausality-rs/deep_causality/tree/main/papers). DeepCausality subsumes Pearl's SCMs, Granger causality, dynamic Bayesian networks, the Rubin Causal Model, and CATE inference as parametric specializations. It is [hosted at the Linux Foundation for Data & AI](https://lfaidata.foundation/projects/deepcausality/).

**2. Counterfactual CFD.** The EPP applied to fluid dynamics, released as [Counterfactual Fluid Dynamics](https://cfd.deepcausality.com). A simulation branches at the decision point, every candidate continues from the state the run has already reached, and the effect log tracks each step for attribution. Flow, reacting chemistry, navigation, and control step one shared field in one process, so an interaction between any two of them reaches the answer. Source code: [deep_causality_cfd](https://github.com/deepcausality-rs/deep_causality/tree/main/deep_causality_cfd).

**3. Dynamic Knowledge.** Pursued under the working name [Deep Brain](https://github.com/causalcenter/deep_brain), the epistemic counterpart of the EPP. It explores how a knowledge corpus can be represented as a continuously evolving process. In contrast, current database systems hold a discrete static snapshot.

## Past Research

**Dynamic Chronometry.** A foundational experiment that used DeepCausality to invert the Einstein Field Equation under the weak-field limit. It recovered the geocentric gravitational constant *GM* from Galileo satellite atomic-clock data to a median precision of 4 × 10⁻⁷. The program has finished, and its record stays published. Source code: [chronodynamics](https://github.com/causalcenter/chronodynamics); reference dataset: [Zenodo](https://doi.org/10.5281/zenodo.20020236).

## Open by Default

Foundational papers as preprints, production-quality Rust crates under the MIT license, and reference datasets with persistent DOIs. Collaborate via the [DeepCausality repository](https://github.com/deepcausality-rs/deep_causality) or the [Discord community](https://discord.gg/Bxj9P7JXSj).
