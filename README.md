# Verter — Sovereign Artificial Mind 🧠
> **Official Web Platform & Telemetry Portal** | **Custom Domain:** [`verter.glyphai.ie`](http://verter.glyphai.ie)  
> **Repository:** [`Moon-stone-AI/verter-site`](https://github.com/Moon-stone-AI/verter-site)  
> **Ecosystem:** [GlyphAI Framework](https://glyphai.ie) · [Moon-stone-AI](https://github.com/Moon-stone-AI)  
> **Lead Architect:** Vitali de Mille (`vitali.demille@glyphai.ie`)

[![GitHub Pages Deployment](https://img.shields.io/badge/GitHub%20Pages-Live%20Deployment-00f2fe?style=for-the-badge&logo=github&logoColor=white)](http://verter.glyphai.ie)
[![Custom Domain](https://img.shields.io/badge/Domain-verter.glyphai.ie-10b981?style=for-the-badge&logo=globe&logoColor=white)](http://verter.glyphai.ie)
[![Fleet Health](https://img.shields.io/badge/5%2C000%20GPU%20Fleet-100%25%20Nominal-6366f1?style=for-the-badge&logo=nvidia&logoColor=white)](https://github.com/Moon-stone-AI/verter-site)
[![Cognitive Architecture](https://img.shields.io/badge/Cognitive%20State-5D%20T(g)%20Manifold-ec4899?style=for-the-badge&logo=matrix&logoColor=white)](https://github.com/Moon-stone-AI/verter-site)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)](LICENSE)

---

## 🌐 Overview

**Verter** is the **Sovereign Artificial Mind** of the GlyphAI ecosystem.

Traditional Large Language Models (LLMs) operate under **token mimicry**: predicting the statistical probability of the next word. While linguistically fluent, text-bound models suffer from fundamental vulnerabilities: raw data leaks, prompt injection vulnerabilities, hallucinations, and security boundary collapse.

Verter introduces a **post-token cognitive paradigm**:
> **«An intelligence that does not speak to think, but thinks to speak.»**

The inner core of Verter reasons entirely upon an irreversible geometric manifold of invariant semantic concepts (*glyphs* and *semantic atoms*), strictly separated from external language generation by isolated literature modules and verifiable safety gates.

---

## 🏛️ Core Architectural Foundations

```
                    ┌──────────────────────────────────────────────┐
                    │            HUMAN OR SYSTEM INPUT             │
                    │        (Natural Language / Telemetry)        │
                    └──────────────────────┬───────────────────────┘
                                           │
                        [ Architectural Irreversibility ]
                    ▼ Raw text destroyed at ingestion boundary ▼
                    ┌──────────────────────────────────────────────┐
                    │     TIER 1 REVERSIBLE COMPRESSION PIPELINE   │
                    │  • Canonical Semantic Atom Mapping (@ENT,etc)│
                    │  • Orthogonal Surface Slot Preservation      │
                    │  • Zero Entropy Loss Mathematical Invariant  │
                    └──────────────────────┬───────────────────────┘
                                           │
                                           ▼
                    ┌──────────────────────────────────────────────┐
                    │      5D THEORY OF MIND (ToM) MANIFOLD        │
                    │          T(g) = (B, K, D, E, Ω)              │
                    │  • B: Epistemic Belief Topologies            │
                    │  • K: Knowledge Asymmetry Vectors            │
                    │  • D: Hidden Goals & Motive Coordinates      │
                    │  • E: Affective Charge & Emotional Valence   │
                    │  • Ω: Strategic Integrity & Truth Constant   │
                    └──────────────────────┬───────────────────────┘
                                           │
                                           ▼
                    ┌──────────────────────────────────────────────┐
                    │         HYPERSCALE FLEET TRIAGE (RCA)        │
                    │  • 5,000 H100 SXM5 / B200 Health Telemetry   │
                    │  • Real-time Double-Bit Error (DBE) Triage   │
                    │  • Deterministic Root Cause Attribution      │
                    └──────────────────────┬───────────────────────┘
                                           │
                                           ▼
                    ┌──────────────────────────────────────────────┐
                    │          ISOLATED LITERATURE MODULE          │
                    │  • Context & Audience-Adaptive Generation    │
                    │  • Cryptographic HMAC Token Vault Gating     │
                    │  • Strict Separation of Thought from Speech  │
                    └──────────────────────────────────────────────┘
```

### 1. 5D Theory of Mind Vector: $T(g) = (B, K, D, E, \Omega)$
Verter models counter-party intent and communication dynamics as native geometric coordinates, rendering social engineering and deceptive prompt manipulations geometrically inert:
- **$B$ (Beliefs):** Structured world-model states held by the interacting party.
- **$K$ (Knowledge Asymmetries):** Information delta between observer and agent.
- **$D$ (Desires & Hidden Goals):** Latent objective functions mapped onto utility manifolds.
- **$E$ (Emotional Valence):** Affective stance and urgency spectrum ($[-1.0, +1.0]$).
- **$\Omega$ (Epistemic Constant):** Rigorous evidence-grounding and invariant truth validation.

### 2. 10-Tier Reversible & Irreversible Compression Pipeline
- **Tier 1 (Lossless Reversible Invariant):** Maps tokens to discrete conceptual atoms (`@ACT:ACQUIRE`, `@ENT:ACCOUNT`, `@MOD:OBLIGATION`) while preserving syntax in an orthogonal reconstruction channel.
- **Tier 2 (Irreversible Abstraction):** Irreversible glyph abstraction ensuring zero original text recovery.
- **Tier 3 (Automated Compliance & Security):** Built-in regulatory auditing and client-side HMAC token masking.
- **Tier 4 (Computational Empathy):** Calibrated multi-modal stance adaptation.
- **Tiers 5–10 (Fleet Telemetry Condenser):** High-dimensional normalization of GPU cluster logs, PCIe/NVLink telemetry, and thermal degradation curves.

### 3. Hyperscale Fleet RCA (5,000 GPU Nodes)
Verter conducts continuous autonomous health monitoring across 5,000 NVIDIA H100/B200 servers:
- Instant triage of Double-Bit Errors (DBE) vs. Single-Bit Correctable Errors.
- Thermal throttle trajectory forecasting and predictive workload migration.
- Zero-leak root-cause reporting via invariant semantic codes.

---

## 🚀 Live Site & GitHub Pages Deployment

The repository is configured to serve the complete Verter public platform directly via **GitHub Pages** bound to custom domain **`verter.glyphai.ie`**.

### Repository Structure
```
Moon-stone-AI/verter-site/
├── index.html                   # Standalone single-file production portal (GitHub Pages entry)
├── CNAME                        # GitHub Pages custom domain binding (verter.glyphai.ie)
├── README.md                    # Platform documentation & DNS setup reference (this file)
├── package.json                 # React 19, TypeScript, Vite & Tailwind CSS dependencies
├── vite.config.ts               # Vite bundler configuration
├── public/
│   ├── CNAME                    # Custom domain definition (verter.glyphai.ie)
│   ├── verter.html              # Standalone production snapshot for static hosting
│   └── assets/                  # Branding and architectural schematics
├── src/
│   ├── App.tsx                  # Root React application
│   ├── components/
│   │   ├── VerterWebpage.tsx    # Interactive Sovereign Artificial Mind portal
│   │   ├── GpuHealthAnalytics.tsx # Real-time 5,000 H100 GPU fleet monitor
│   │   ├── ArchitecturePipeline.tsx # 10-Tier Compression visualizer
│   │   ├── ArtificialMindTheory.tsx # 5D T(g) Theory of Mind mathematical manifold
│   │   ├── GitHubSyncPanel.tsx  # In-App repository sync & fleet deployer
│   │   └── ExportIndexModal.tsx # 1-click GitHub sync modal with token validation
│   ├── services/
│   │   └── githubService.ts     # Direct GitHub REST API integration
│   └── context/
│       └── WertherContext.tsx   # Global agent state & bilingual (EN/RU) localization
├── tier1_reversible_compression.py # Verified Python implementation of Tier 1 atomization
└── github_sync_module.py        # Automated ontology commit & fleet deploy script

## 🧠 Scientific Background & Monograph

- **Monograph:** *Entering the Era of the "Artificial Mind"* (Vitali de Mille, GlyphAI, October 2026).
- **Core Principle:** Architectural Irreversibility — data utility is decoupled from recoverable human text.
- **Mathematical Specification:** 5D Mental-State Vector $T(g) = (B, K, D, E, \Omega)$.

---

## 📄 License & Attribution

Distributed under the MIT License. Copyright © 2026 [GlyphAI](https://glyphai.ie) & [Moon-stone-AI](https://github.com/Moon-stone-AI). All rights reserved.
