# Banking Ontology Coach by CZR（银行业本体建模教练）

> A coaching-style AI Skill for banking domain ontology modeling, aligned with the FIBO (Financial Industry Business Ontology) standard.

## 🧠 What is this?

This is a **Skill** (system prompt / instruction set) that turns an AI assistant into a **banking ontology modeling coach**. Instead of giving you the answers, it **guides you step-by-step** to build your own ontology for a banking business domain, while always cross-referencing the industry standard **FIBO**.

### Who is it for?

- Consulting advisors learning knowledge-engineering style ontology modeling
- Data governance / MDM teams structuring banking business terms
- RegTech / compliance teams mapping concepts to regulatory reporting frameworks (CCAR, MiFID II, LEI, BCBS 239)
- Anyone who wants to model "counterparty", "legal entity", "beneficial ownership", "account", "financial instrument" etc. in a rigorous, interoperable way

## 🚀 How to use this Skill

### In WorkBuddy / OpenClaw (recommended)

1. Open WorkBuddy or OpenClaw
2. Go to **Skills / Experts** → search **"银行业本体建模"** or **"banking-ontology-coach"**
3. Install from ClawHub: https://clawhub.ai/skills/banking-ontology-coach
4. Start a conversation — say: *"I want to learn banking ontology modeling, please guide me"*

### In Claude / ChatGPT

1. Copy the content of `SKILL.md`
2. Paste it into the **System Prompt** / **Project Instructions** field
3. Start chatting — the AI will act as your ontology coach

## 📂 Repository Structure

```
SKILL.md                          # The Skill (main file — the AI instruction set)
references/
  fibo-reference.md               # FIBO quick reference & "reuse-first" alignment workflow
  fibo-core-concepts.md           # Cheat-sheet of most-used FIBO core concepts in banking
  ontology-concepts.md            # Knowledge engineering terminology table (for teaching)
  common-mistakes.md             # Common mistakes checklist (banking + general)
```

## 🎓 The 7-Stage Coaching Flow

The Skill guides you through 7 stages (based on Noy & McGuinness *Ontology Development 101*, adapted for banking):

| Stage | What you do |
|---|---|
| 0 · Scope & Competency Questions | Define the use case & regulatory driver |
| 1 · Gather Terms & Map to FIBO Domains | List keywords, roughly place them in FIBO domains |
| 2 · Align with FIBO (reuse first!) | For each concept: reuse / specialize / extend? |
| 3 · Build Classes & Hierarchy | is-a hierarchy, anchored to FIBO |
| 4 · Add Properties | Datatype properties + object properties |
| 5 · Facets, Characteristics & Axioms | domain/range, cardinality, constraints |
| 6 · Populate Instances & Dual Verification | Real examples + CQ check + FIBO alignment check |

## ⚠️ Key Principle: Reuse FIBO, Don't Reinvent

> The #1 anti-pattern in banking ontology modeling: **rebuilding FIBO concepts from scratch**.
> Reuse = your model maps to industry standards & regulatory reporting.
> Reinvent = you break interoperability.

## 📖 References

- **FIBO Viewer**: https://spec.edmcouncil.org/fibo
- **EDM Council**: https://edmcouncil.org/
- **ClawHub Skill Page**: https://clawhub.ai/skills/banking-ontology-coach

## 📜 License

MIT-0 — free to use, modify, and redistribute. No attribution required.

## 👤 Author

**Carrie ZhangRong** — created for internal consulting use, shared openly to help the banking ontology community.

Questions or suggestions? Open an issue or reach out!
