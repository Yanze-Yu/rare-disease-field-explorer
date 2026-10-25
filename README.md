# Rare-Disease Expert-Sharing Field Explorer

Interactive explorer of the expert-sharing field among 322 rare diseases in China's rare-disease catalogues, 2016–2025.

**Open the explorer:** https://yanze-yu.github.io/rare-disease-field-explorer/

Each node is a rare disease; ties link diseases that share experts (shared-expert cosine similarity, computed from PubMed-indexed publications). Three period snapshots — P1 (2016–17), P2 (2021–22) and P3 (2024–25) — share fixed node positions, and *Play* runs a monthly time ruler from January 2016 to December 2025.

**Preliminary results** (pipeline v3, October 2026). The data are disease-level aggregates and contain no information about individual people.

Yanze Yu · Department of Sociology, Columbia University

Built with [vis-network](https://github.com/visjs/vis-network) 9.1.0 (Apache-2.0 / MIT), embedded in `index.html`; the page makes no external requests.
