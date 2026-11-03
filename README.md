<div align="center">

<picture>
  <source media="(max-width: 600px) and (prefers-color-scheme: dark)" srcset="./assets/project-map-mobile-dark.webp">
  <source media="(max-width: 600px) and (prefers-color-scheme: light)" srcset="./assets/project-map-mobile-light.webp">
  <source media="(prefers-color-scheme: dark)" srcset="./assets/project-map-dark.webp">
  <img src="./assets/project-map-light.webp" alt="An illustrated engineering project map: RelayFence establishes boundaries, BranchHarbor manages versioned state, and WattMosaic turns incomplete sensor readings into forecasts." width="100%">
</picture>

# Chong Xian

**Software engineering · secure systems · applied machine learning**

*Building systems where trust boundaries, failure modes, and measurable behavior are part of the design.*

[Explore my work](#selected-work) · [Engineering principles](#how-i-approach-engineering) · [LinkedIn](https://www.linkedin.com/in/chong-xian/)

</div>

---

Based in Singapore. I work across backend and systems engineering, developer infrastructure, practical ML, and security-minded software. I prefer reproducible demonstrations and explicit limitations to claims a repository cannot substantiate.

## Selected work

| Project | Engineering focus | Explore |
|:--|:--|:--|
| **[RelayFence](https://github.com/C-X1an/relayfence)** | Experimental mTLS egress gateway with destination policy, live revocation, and auditable connection handling. **Go · network security** | [Architecture](https://github.com/C-X1an/relayfence/blob/main/ARCHITECTURE.md) · [Verification](https://github.com/C-X1an/relayfence/actions) |
| **[BranchHarbor](https://github.com/C-X1an/branchharbor)** | Single-node versioned workspace system using scoped capabilities, content-addressed state, optimistic concurrency, and recovery. **Go · backend systems** | [API](https://github.com/C-X1an/branchharbor/blob/main/API.md) · [Verification](https://github.com/C-X1an/branchharbor/actions) |
| **[FaultBraid](https://github.com/C-X1an/faultbraid)** | Experimental three-voter Raft workbench for fault injection, replay, reduction, and inspectable correctness evidence. **Go · distributed systems** | [Architecture](https://github.com/C-X1an/faultbraid/blob/main/ARCHITECTURE.md) · [Verification report](https://github.com/C-X1an/faultbraid/blob/main/VERIFICATION_REPORT.md) |
| **[WattMosaic](https://github.com/C-X1an/WattMosaic)** | Forecasting campus energy demand when sensor readings are incomplete, with explicit missingness patterns and evaluation boundaries. **Python · applied ML** | [Methodology](https://github.com/C-X1an/WattMosaic#readme) · [Notebook](https://github.com/C-X1an/WattMosaic/blob/main/notebooks/WattMosaic.ipynb) |

## More from the engineering lab

| Project | Question explored |
|:--|:--|
| **[BatchQuay](https://github.com/C-X1an/batchquay)** | How do original C++ transformer inference mechanics, request-owned KV pages, and bounded scheduling behave under cancellation and contention? |
| **[RillScope](https://github.com/C-X1an/rillscope)** | How can a query compiler enforce host-defined data access boundaries without trusting user-supplied scope? |
| **[FacetQuarry](https://github.com/C-X1an/facetquarry)** | What changes when nearest-neighbor search must respect tenant and metadata filters, with measured recall and work budgets? |
| **[Driftline](https://github.com/C-X1an/driftline)** · **[EffectLatch](https://github.com/C-X1an/effectlatch)** | Exploratory developer tooling and bounded WebAssembly runtime work; refer to each repository for its current maturity and limitations. |

These are engineering experiments, not blanket production-readiness claims. Current support, validation status, and known limitations are documented in the relevant repositories.

## How I approach engineering

**01 — Bound authority.** Make the trust model, permissions, and operational scope explicit.

**02 — Test failure paths.** Treat concurrency, malformed input, cancellation, and recovery as first-class behavior.

**03 — Show the evidence.** Pair implementation with reproducible commands, meaningful tests, and source-bound results.

**04 — State the limits.** Distinguish completed verification from work still in progress.

## Languages and areas

**Languages:** Go · Python · Rust · C++ · JavaScript/TypeScript · SQL

**Areas:** Backend and distributed systems · Security engineering · Developer infrastructure · Applied machine learning · Data-intensive applications · Full-stack development

*My repositories demonstrate different levels of maturity across these areas; the code and evidence tell the detailed story.*

## Connect

[LinkedIn](https://www.linkedin.com/in/chong-xian/) · [Browse repositories](https://github.com/C-X1an?tab=repositories)

For reproducible bugs, implementation questions, or documentation feedback, open an issue in the relevant repository.
