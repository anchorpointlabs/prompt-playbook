# C.O.R.E. — The Four-Stage Prompt Framework

Every effective AI prompt runs through the same four stages:

| Stage | Full Name | The question it answers |
|---|---|---|
| **C** | Context & Persona | Who is the AI in this conversation, and what does it need to know? |
| **O** | Objective & Format | What exactly do I want, and in what shape? |
| **R** | Reasoning & Routing | How should the AI think through this? What technique? What steps? |
| **E** | Evaluation & Constraints | Does the output meet spec? What must be avoided? |

## C.O.R.E. in 60 Seconds

```
[C] You are [role]. Your context: [background]. You know: [domain knowledge].

[O] Produce: [deliverable]. Format: [structure]. Length: [limit]. Must include: [required elements].

[R] Technique: [zero-shot / few-shot / chain-of-thought]. Process: [step 1 → step 2 → step 3].

[E] Quality gates: [criteria]. Avoid: [banned words, tones, or approaches].
```

**Example — a quick email:**

```
[C] You are a project manager writing to a client.

[O] Write a transparent status email. Include: progress update, 1-week delay, mitigation plan. Under 150 words.

[R] Chain-of-thought: First list the key facts, then draft the email.

[E] Tone: accountable but confident. No defensive language.
```

## Nested Acronyms

C.O.R.E. has three nested acronyms — precision tools for complex tasks:

- **[F.O.R.M.](form.md)** — precision inside the O-stage
- **[T.R.A.C.K.](track.md)** — precision inside the R-stage
- **[S.A.F.E.](safe.md)** — precision inside the E-stage

## C.O.R.E. Across Modalities

The same four stages work for every AI task — only the details of the R-stage change:

| Task | C stage | O stage | R stage | E stage |
|---|---|---|---|---|
| Writing (text) | Role + background | Deliverable + format | Technique + step-by-step | Tone check + anti-filler |
| Image generation | Visual style + era | Aspect ratio + dimensions | Render plan + negative prompt | Brand alignment + no artifacts |
| Video generation | Visual world + mood | Duration + format | Motion plan + camera | No morphing + style guardrails |
| AI agent systems | Agent identity + mission | Output format + constraints | Tool selection + decision logic | Safety boundaries + cost caps |
| Document querying | Knowledge domain | Output format (table, list, briefing) | Synthesis depth + citation requirement | Accuracy check + omission audit |

---

© The Garrison Collective Pte. Ltd. / Anchor Point Labs. C.O.R.E., F.O.R.M., T.R.A.C.K., and S.A.F.E. are proprietary frameworks. Free for personal and learning use. Commercial reuse or teaching from this material requires written permission.
