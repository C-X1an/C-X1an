<p align="center">
<a href="https://github.com/C-X1an/C-X1an/blob/main/assets/project-map-dark.webp#gh-dark-mode-only">
<picture>
  <source media="(max-width: 600px)" srcset="https://raw.githubusercontent.com/C-X1an/C-X1an/main/assets/project-map-mobile-dark.webp">
  <img alt="Chong Xian’s project map: RelayFence as a permission gate, BranchHarbor as branching state snapshots with a recovery loop, and WattMosaic as incomplete sensor patterns resolving into a signal." src="https://raw.githubusercontent.com/C-X1an/C-X1an/main/assets/project-map-dark.webp#gh-dark-mode-only" width="100%">
</picture>
</a>
<a href="https://github.com/C-X1an/C-X1an/blob/main/assets/project-map-light.webp#gh-light-mode-only">
<picture>
  <source media="(max-width: 600px)" srcset="https://raw.githubusercontent.com/C-X1an/C-X1an/main/assets/project-map-mobile-light.webp">
  <img alt="Chong Xian’s project map: RelayFence as a permission gate, BranchHarbor as branching state snapshots with a recovery loop, and WattMosaic as incomplete sensor patterns resolving into a signal." src="https://raw.githubusercontent.com/C-X1an/C-X1an/main/assets/project-map-light.webp#gh-light-mode-only" width="100%">
</picture>
</a>
</p>

<p align="center">
  <a href="https://github.com/C-X1an/relayfence">Boundaries / RelayFence</a> ·
  <a href="https://github.com/C-X1an/branchharbor">State / BranchHarbor</a> ·
  <a href="https://github.com/C-X1an/WattMosaic">Signal / WattMosaic</a>
</p>

# Chong Xian

**Software engineering · secure systems · applied machine learning**

I build backend systems and developer tools, with an interest in how permissions, durable state and imperfect data shape reliable software. Based in Singapore.

[LinkedIn](https://www.linkedin.com/in/chong-xian/) · [Repositories](https://github.com/C-X1an?tab=repositories)

## Selected work

### [RelayFence](https://github.com/C-X1an/relayfence)

An experimental single-host mTLS egress gateway in Go, with exact destination policy and live revocation. The repository explains its architecture, threat model and deployment limits alongside executable verification.

[Architecture and threat model](https://github.com/C-X1an/relayfence#readme) · [Tests and CI](https://github.com/C-X1an/relayfence/actions)

### [BranchHarbor](https://github.com/C-X1an/branchharbor)

A single-node, versioned workspace system in Go. Content-addressed state, scoped capabilities and optimistic concurrency make changes explicit; journal recovery and idempotent operations address failure paths. Experimental, with Linux filesystem prerequisites.

[Design and API](https://github.com/C-X1an/branchharbor#readme) · [Verification](https://github.com/C-X1an/branchharbor/actions)

### [WattMosaic](https://github.com/C-X1an/WattMosaic)

Forecasting with incomplete campus sensor data, using 16 sensor-availability patterns. The public notebook illustrates missingness-mask construction and core/specialist routing. Competition data, trained weights and the full training pipeline are excluded from the public release.

[Notebook and methodology](https://github.com/C-X1an/WattMosaic#readme) · [Notebook](https://github.com/C-X1an/WattMosaic/blob/main/notebooks/WattMosaic.ipynb)

## How I approach engineering

- **Make boundaries visible.** Explain permissions, trust assumptions and limits before presenting a system as reliable.
- **Test failure paths.** Treat concurrency, recovery and malformed inputs as part of the design.
- **Keep evidence close to claims.** Publish runnable checks and distinguish experimental work from production readiness.

## More to explore

[Driftline](https://github.com/C-X1an/driftline) explores semantic drift in Python projects. [EffectLatch](https://github.com/C-X1an/effectlatch) explores a bounded Rust/WebAssembly tool runtime and documents its unfinished acceptance work.

**In these repositories:** Go · Python · Rust · SQL

I’m continuing to develop secure backend systems, reproducible developer tooling and practical approaches to missing data.

## Connect

Find me on [LinkedIn](https://www.linkedin.com/in/chong-xian/) or explore the code above. For project-specific questions or reproducible bugs, use the relevant repository’s issue tracker.
