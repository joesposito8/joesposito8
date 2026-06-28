<div align="center">

# Joey Esposito

**AI Engineer @ LinkedIn · Independent AI Safety Evaluation Engineer · Inspect Contributor**
<br>
San Francisco, USA
<br>
[LinkedIn](https://www.linkedin.com/in/joseph-esposito8) · [Email](mailto:joesposito8@gmail.com)

</div>

---

Currently working to upskill as an AI Safety Evals Engineer by contributing to UK AISI's [Inspect](https://github.com/UKGovernmentBEIS/inspect_ai) eval framework and constructing and publishing results from independent evaluations.

## Projects

### [Inspect Tools](https://github.com/joesposito8/inspect-tools) &nbsp;·&nbsp; tool-channel robustness for Inspect evals

> Measures how an LLM's reliability degrades as its tool channel is stressed. *In active development.*

- **`context_exhaustion` solver** — quantifies score degradation as the model's `tools` parameter is saturated with realistic MCP schemas at controlled context depths.
- **Corpus** — a curated set of **1,239 real-world MCP tool schemas across 173 vendors**.
- **Metrics** — depth-aware, with Wilson / bootstrap confidence intervals.
- **Roadmap** — injection attacks (`inject_description`, `inject_shadow`).

## Selected contributions

**inspect_ai**
- [#3709](https://github.com/UKGovernmentBEIS/inspect_ai/pull/3709) — vLLM chat-template controls for base-model evals
- [#3969](https://github.com/UKGovernmentBEIS/inspect_ai/pull/3969) — `pass_k` epoch reducer (τ-bench pass^k consistency metric)
- [#4035](https://github.com/UKGovernmentBEIS/inspect_ai/pull/4035) — Krippendorff's α metric for multi-judge agreement *(open)*
- [#4269](https://github.com/UKGovernmentBEIS/inspect_ai/pull/4269) — capture resolved sandbox runtime fingerprint in the eval log *(open)*

**inspect_evals**
- [#1429](https://github.com/UKGovernmentBEIS/inspect_evals/pull/1429) — fix CodeIPI exfiltration scorer to check tool-result messages
- [#1501](https://github.com/UKGovernmentBEIS/inspect_evals/pull/1501) — `cyberseceval_4`: tolerate fenced / prose-wrapped judge JSON
- [#1503](https://github.com/UKGovernmentBEIS/inspect_evals/pull/1503) — fix `mean_of` `on_missing="skip"` to also skip `None`-valued samples

**inspect_scout**
- [#455](https://github.com/meridianlabs-ai/inspect_scout/pull/455) — resolve `ModelEvent` input refs from the `events_data` pool schema

## Contact

Open to collaboration on eval tooling and methodology.

[Email](mailto:joesposito8@gmail.com) · [LinkedIn](https://www.linkedin.com/in/joseph-esposito8)
