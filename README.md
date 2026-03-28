# Intelligence at the Edge of the Cloud
### A Local Architecture for the AI Era

**Jonathan Horvat** · Public domain · No rights reserved

---

> *The problem is not that cloud AI companies are untrustworthy. The problem is that trust should not be required.*

---

## Read the Paper

| Format | Link |
|---|---|
| HTML (best experience) | [GitHub Pages](https://jdhorvat.github.io/intelligence-at-the-edge/) |
| PDF (for download) | [intelligence_at_the_edge_horvat.pdf](paper/intelligence_at_the_edge_horvat.pdf) |

---

## Abstract

The prevailing assumption in artificial intelligence is that intelligence lives in the cloud — that to be smart, a device must be connected. This paper argues the opposite will become true. As models mature and weight compression advances, the edge will carry the full depth of human knowledge locally, refreshed not by a live wire but by periodic synchronization of model weights.

We propose a two-model edge architecture: a broadcast-synced sparse expert world model and an on-device augmented personal model with a built-in interpreter head. Combined, this architecture addresses three problems at once: intelligence that is genuinely personal, privacy that is structural rather than contractual, and a fraction of the energy and infrastructure cost of cloud inference.

---

## The Architecture in One Paragraph

A sparse expert world model lives on-device, refreshed by periodic broadcast of weights from frontier infrastructure — like a software update, but delivering new understanding rather than new procedures. An augmented personal model runs continuously in a hardware secure enclave, carrying low-rank adapters that encode the user through behavioral observation and a fixed interpreter head that translates between the two independent embedding spaces. The user interacts only with the augmented personal model. The world model never sees personal data. Nothing leaves the device except an occasional anonymous weight sync request indistinguishable from population noise.

---

## Sections

| # | Title | What it covers |
|---|---|---|
| I | The False Promise of the Cloud | Why the current paradigm is structurally flawed — and why this isn't an argument against the cloud |
| II | Weights as Knowledge | Model weights as compressed human understanding |
| III | The Sync Paradigm | Periodic weight broadcast as a replacement for live connectivity |
| IV | The Core Architecture | World model and augmented personal model in detail |
| V | Privacy as Architecture | Structural privacy vs policy promises — threat model and attack surface |
| VI | Graceful Degradation | Coverage score — honest uncertainty instead of hallucination |
| VII | Neural Architecture | Interpreter head mechanics, pseudocode, open research direction |
| VIII | The Graduated Transition | How this becomes real incrementally — day one to maturity |
| IX | Physical AI | Why physical AI requires this architecture |
| X | Consequences at Scale | Infrastructure displacement, geopolitical leapfrogging, edge chip as strategic battleground |
| XI | The Human Analogy | Cognitive science parallel |
| XII | Environmental Implications | The power grid vs battery argument |
| XIII | On Sharing This Freely | Public domain declaration |
| XIV | Reference Implementation Sketch | What to build with, today, on 2026 hardware |

---

## Key Claims

- A mid-range smartphone running a 3–7B quantized world model delivers genuine general intelligence locally today
- The personal adapter set starts empty and calibrates within days of normal use — useful from day one, better by day thirty
- The interpreter head relationship between the two models may be emergent — an open research direction grounded in convergent representations, fractal brain organization, and oscillatory synchronization
- Intelligence per milliwatt replaces tokens per second as the right metric for the next era of AI hardware
- The cloud remains available throughout — this is an addition to capability, not a replacement

---

## License

Public domain. No rights reserved. CC0.

Use it. Build on it. Correct it if it's wrong. A mention is appreciated but not required.

---

*Jonathan Horvat · 2026*
