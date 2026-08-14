# S.A.F.E. — Quality Gates in the E-Stage

Run S.A.F.E. before you ship any AI output. It takes 30 seconds.

| Letter | Check |
|---|---|
| **S — Specifications** | Did it follow F.O.R.M.? Word count? Format? |
| **A — Avoidance** | Did it exclude everything on the avoid list? |
| **F — Fidelity** | Are all claims grounded in the references provided? |
| **E — Efficiency** | Is every sentence earning its place? No filler? |

## Example

```
[S] 800 words? 5 sections? Markdown?
[A] No passive voice? No jargon? No banned words?
[F] Stats from the report? Voice from A1?
[E] No filler? Every sentence works?
```

Any "no" sends the output back for one more pass — with the specific failure named in the next prompt.

---

© The Garrison Collective Pte. Ltd. / Anchor Point Labs. C.O.R.E., F.O.R.M., T.R.A.C.K., and S.A.F.E. are proprietary frameworks. Free for personal and learning use. Commercial reuse or teaching from this material requires written permission.
