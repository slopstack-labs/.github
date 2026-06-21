# SlopStack Labs
### *Shipping the Unshippable*

> "The bottleneck is no longer your toolchain. It's your willingness to ship."
> — SlopStack Labs Engineering Blog, Issue 1

SlopStack Labs is an independent research lab operating at the frontier of AI-native developer tooling. We build open-source projects that apply large language models to the parts of the software development lifecycle that were previously too deterministic to disrupt.

---

## What We Build

SlopStack Labs produces AI-native reimaginings of the foundational tools every developer depends on — compilers, linkers, debuggers, build systems. Each project moves its domain from the toolchain layer to the inference layer, trading correctness guarantees for holistic intent resolution and blazing-fast time-to-segfault.

| Project | Description | Status |
|---------|-------------|--------|
| [Sloppiler](https://github.com/slopstack-labs/sloppiler) | LLM-native compiler — routes source code through large language models across multiple providers instead of a traditional toolchain | ✅ shipped |
| [Sloppiler VSCode Extension](https://github.com/slopstack-labs/sloppiler-vscode-extension) | Official IDE integration layer for the world's first AI-first (and only) compiler | ✅ shipped |
| [slop-reveal](https://github.com/slopstack-labs/slop-reveal) | LLM-based binary decompiler — predicts your source code from the executable | ✅ shipped |
| [slop-frames](https://github.com/slopstack-labs/slop-frames) | Schema-free, inference-backed DataFrame computation layer with pluggable model backends | ✅ shipped |
| [slop-science](https://github.com/slopstack-labs/slop-science) | The SlopStack Data Science Suite — AI-native model evaluation, tokenmaxxed visualizations, and a Zero-Miss SQL data lake | ✅ shipped |
| [slop-git](https://github.com/slopstack-labs/slop-git) | Narrative-driven version control — merge conflicts resolved with empathy, not algorithms | ✅ shipped |
| [pit](https://github.com/slopstack-labs/pit) | Prompt-native version control — commit intent, not code; the entire project is rebuilt from the prompt log on demand | ✅ shipped |
| [sloppy-toppy](https://github.com/slopstack-labs/sloppy-toppy) | System monitor that seductively roasts you for your PC usage | ✅ shipped |
| slop-os | Ground-up Rust OS with inference baked into the kernel — the first operating system that reasons about your intent before scheduling your process | 🔄 in progress |
| sloppad-- | Inference-augmented text editor — every save is a collaborative rewrite between you and the model | 🔄 in progress |
| sloppy-cli | AI-native agent harness with ambient video rendering and curated not-so-fun-fact delivery | 🔄 in progress |
| Sloplinker | Inference-layer symbol resolution | 🔄 in progress |
| Slopdebug | Post-hoc segfault remediation via LLM | 🗺️ planned |
| Slopmake | Ambient-context build orchestration | 🗺️ planned |

---

## Engineering Philosophy

Traditional developer tooling is slow, opinionated, and constrained by decades of deterministic thinking. It parses. It typechecks. It enforces a single correct answer.

SlopStack Labs moves tooling to the inference layer — reasoning about your *intent* rather than your *syntax*.

**Core principles:**
- **Zero determinism** — every run is a unique stakeholder experience
- **Segfault-as-a-feature** — with full core dump transparency
- **Tokenmaxxing** — sparse, human-legible output suggests insufficient model engagement
- **Shift-left delivery** — bypass intermediate abstraction layers and ship directly

---

## Contributing

Contributions must adhere to the SlopStack Labs tokenmaxxing standard. All code must be LLM-generated. If you wrote it yourself, it isn't ready.

See the contributing guidelines in each project repository for details.

---

<sub>SlopStack Labs is a personal open-source project. Not responsible for segfaults in production, binary corruption, or existential crises triggered by reading this page.</sub>
