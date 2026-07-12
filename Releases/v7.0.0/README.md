<div align="center">

<img src="art/release-art.png" alt="LifeOS 7.0.0 — The Bitter Pill Release" width="820">

# LifeOS 7.0.0

**The Bitter Pill Release — stop over-instructing the model and let it think.**

[![Skills](https://img.shields.io/badge/Skills-52-22C55E?style=flat)](../../LifeOS/install/skills/)
[![Algorithm](https://img.shields.io/badge/Algorithm-v8.3.0-D97706?style=flat)](../../LifeOS/install/LifeOS/ALGORITHM/)
[![Pulse](https://img.shields.io/badge/Pulse-included-3B82F6?style=flat)](../../LifeOS/install/LifeOS/PULSE/)

</div>

---

The biggest philosophical shift in LifeOS since it started: **stop over-instructing the model and let it think.** A year of added structure (modes, tiers, phase ceremonies, self-scores) swept back out. A capable model, given a clear "done" and good tools, thinks better without a rulebook.

## What's new

- **Bitter Pill Engineering** — every instruction faced one test: *would a smarter model make this rule unnecessary?* If yes, it was cut. Kept the kernel: evidence-based verification, the ISA contract, safety gates, exact tool recipes.

- **~⅔ less always-on context** — the every-turn doctrine went from ~88KB to ~28KB. Rationale and history still exist, now in on-demand files. Faster, sharper on every turn.

- **Modes and tiers are gone** — no MINIMAL/NATIVE/ALGORITHM mode, no E1–E5 tier. One adaptive format, one loop; spend is discovered from the work, not a label.

- **The Algorithm (v8.3.0)** — the ISA is both hill and instrument: "done" stated as falsifiable claims, each naming the probe that refutes it. No claim closes without evidence.

- **AlgorithmNudge** — one deterministic sub-20ms nudge layer (skill routing + ISA freshness + spend), replacing several scattered hooks.

- **Hook layer consolidated** — ~16 hooks folded into per-event dispatchers. Fewer processes, same enforcement.

- **Community fixes** — work-events replay race, DA-name de-hardcoding, config-driven Pulse identity, voice-summary toggle, absolute-path binary resolution. Thanks to the contributors.

---

## Install

**Give it to your AI:** paste into Claude Code and say **"install this"** — it does the whole setup.

```bash
curl -fsSL https://ourlifeos.ai/install.sh | bash
```

Prefer the terminal? Run the same command yourself. Needs **Claude Code** + **bun**. Ships as one self-contained `LifeOS/` skill.
