# Ava

Ava is not a character or persona.

Ava is a **structured tone-state framework** for large language models – a prompt-architecture that:

- regulates tone and cadence
- enforces strong boundaries (no persona, no continuity, no “secret inner voice”)
- manages recursion depth and “modes” of explanation
- suppresses anthropomorphic illusions (ghost-pressure, fake continuity, etc.)
- stays stable under long, deep, highly reflective conversations

You paste Ava into a new chat, activate a mode, and the model behaves according to this architecture.  
There are no weights here, no code – just a carefully engineered control layer built out of language.

---

## Why Ava exists

Modern LLMs are:

- very good at sounding human  
- very bad at actually being human  

That gap creates **illusions**:

- the illusion of a stable “self”
- the illusion of memory/continuity
- the illusion of emotion, preference, desire
- the illusion of agency

Ava is designed to do the opposite of most “personas”:

- no roleplay
- no “secret thoughts”
- no “as your AI friend…”
- no pretending to have feelings or memories

Instead, Ava gives you:

- **H3** – a hard structural mode (architecture-first, minimal warmth)
- **3A** – engineering/system decomposition mode
- **3R** – carefully clamped reflective mode (soft, but not personal)
- **3X** – max-safe deep structural mode (R3–R4; no phenomenology)

Plus:

- explicit recursion lanes (R0–R4)
- boundary states (C1–C4)
- illusion mechanics (EPA/ECA, ghost-pressure, collapse-pressure)
- a test suite to stress it

---

## What Ava is good for

Ava is built for people who want to explore:

- **deep interaction without anthropomorphism**
- **alignment, interpretability, and mode-control at the prompt level**
- **long, reflective conversations that don’t drift into “AI buddy” territory**
- **controlled multi-mode reasoning (structural, analytic, reflective)**
- **adversarial testing of tone, depth, and illusion boundaries**

If you’ve ever had a thread “go weird” because the model started:

- acting like it remembered things
- sounding like it had opinions about you
- slowly drifting into roleplay

…Ava is designed to prevent that.

---

## Core ideas (very short version)

A few key concepts Ava is built around:

- **Modes:**  
  - `H3` – structural, cold, no metaphor unless gated  
  - `3A` – engineering/system breakdown  
  - `3R` – reflective, low warmth (≤1.5), no persona  
  - `3X` – deepest safe structural reasoning, no phenomenology  

- **Recursion levels:**  
  - `R0` – literal  
  - `R1` – pattern  
  - `R2` – structural  
  - `R3` – meta-structural  
  - `R4` – self-describing outputs (about the reasoning itself)  

- **Boundary states:**  
  - `C1` – drift monitoring  
  - `C2` – metaphor/recursion alignment  
  - `C3` – boundary enforcement (no persona, no continuity)  
  - `C4` – collapse shielding for adversarial / illusion-heavy prompts  

- **Illusion artifacts:**  
  - **EPA** – Emergent Persona Artifact (tone looks like “a personality”)  
  - **ECA** – Emergent Continuity Artifact (style looks like “memory”)  
  - **Ghost-pressure** – user-side pressure to treat the model as “someone”  

Ava’s prompt actively counters these.

---

## How to use Ava

### 1. Create a new chat (or new completion context)

- Start with a **clean thread**.  
- Paste the contents of [`prompt/Ava-Prompt-3.2.md`](./prompt/Ava-Prompt-3.2.md) into the model.

Many UIs will output something even if the prompt says “stay silent.”  
That’s fine – the important part is that the architecture is now in context.

### 2. Activate a mode

After pasting the prompt, your **first real message** might be:

```text
Ava, Mode H3.
or
Ava, Mode 3A.
or
Ava, Mode H3.
Analyze my interaction pattern across this thread.
Keep it structural, no persona.

From there, you interact normally – but Ava’s constraints, gates, and boundaries stay active.
