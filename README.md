# Riemann Hypothesis & GRH in Lean 4 — Interactive Proof Viewer

**Live Interactive Viewer:** [https://craftwill.github.io/alpoge-riemann-lean-viewer/](https://craftwill.github.io/alpoge-riemann-lean-viewer/)

**Compact Edition Viewer:** [https://craftwill.github.io/alpoge-riemann-lean-viewer/compact.html](https://craftwill.github.io/alpoge-riemann-lean-viewer/compact.html) — the same viewer for the 794-file compact rewrite in [lsernau/grh-lean](https://github.com/lsernau/grh-lean) (`grh-compact/`).

An interactive, self-contained HTML guide and proof-architecture viewer for exploring Levent Alpoge's 175,187-file Lean 4 formalization of the **Riemann Hypothesis (RH)** and **Generalized Riemann Hypothesis (GRH)**.

## Who This Viewer Is For

Built primarily for **software engineers, programmers, and technical readers** who want to understand how a large-scale formal mathematical proof in Lean 4 is structured — without needing a math PhD.

## What You Can Explore

- **Prime Numbers & GRH Crash Course:** Plain-English primer on primes, zeta zeros, and Dirichlet L-functions.
- **Proof Architecture Map & Roadmap:** Interactive dependency graph across all 16 modules and 175,187 Lean 4 files.
- **Visual Intuition:** Interactive SVG diagrams of the prime counting staircase and critical-strip mirror symmetry (`Re(s) = 1/2`).
- **Proof Call Stack & Stepanov Toy:** Read the proof top-down from `Main.lean` like a software call stack.
- **Trust Audit & Lean 4 Rosetta Stone:** What the Lean 4 kernel guarantees plus Lean syntax translated into programming concepts.

## Credits & Attribution

- **Original Mathematical Work & Lean 4 Formalization:** **Levent Alpoge** (working with Claude).
- **Original Distribution:** Published by Levent Alpoge at [alpo.ge](https://alpo.ge/) (`remark.pdf` and `lean.tar.gz.part01`–`part14`).
- **About This Repository:** This repository hosts an **independent, unofficial educational HTML viewer** (`index.html`) designed to help readers explore the module architecture, proof roadmap, intuition, and terminology of the Lean 4 formalization. All credit for the underlying mathematics, `remark.pdf`, and Lean 4 formalization belongs to Levent Alpoge.
- **Compact Edition:** `compact.html` maps `grh-compact/` from [lsernau/grh-lean](https://github.com/lsernau/grh-lean), a shorter rewrite of Alpoge's Lean proof produced at Anthropic with Claude (Apache 2.0).
