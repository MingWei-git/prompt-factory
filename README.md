# The AI Prompt Factory

**Design once. Execute simpler.**

*A universal framework for consistent, repeatable AI output — across any domain, any tool, any team.*

---

## The Problem This Solves

Ask any AI tool the same question twice, in two different sessions, and you get two structurally different answers. Different format. Different depth. Different things included or left out. This inconsistency makes AI unreliable for production workflows where repeatable, comparable outputs are required.

The fix is not a better prompt. It is a better architecture.

---

## What, Then How

> *"Know exactly what you want. The how shall follow."*
> — Ming Wei

The AI Prompt Factory is built on a simple but powerful philosophy: **clarity of intention is the ignition of creativity, not its byproduct**. Before writing any prompt, build the case. Know exactly what successful output looks like. The prompt surfaces naturally from that clarity — and the factory handles the rest.

Three movements:
- **The WHAT is the ignition** — precision of intention draws solutions toward it involuntarily
- **Iteration is the engine** — a clear What gives every attempt direction and navigation
- **Build the case first** — prompts surface naturally; never the other way around

---

## The Framework — Three Layers
Design Once, Execute Simpler          ← The end goal
│
▼
What, Then How                      ← The mindset
│
▼
The AI Prompt Factory               ← The method
---

## The Method — 5-Tab Excel Workbook

The factory is modeled on product manufacturing. Five components, one coherent system:

| Tab | Manufacturing Analogy | Role |
|---|---|---|
| **1_INVOKE** | Work Order | The only tab you copy and paste. The entire user-facing workflow. |
| **2_SOP** | Assembly Instructions | Step-by-step AI assembly logic with quality gates. |
| **3_MOLD** | Production Mold | Complete worked example. AI replicates — never invents. |
| **4_SOURCES** | Raw Materials | Your run-specific inputs. The only tab that changes per run. |
| **5_CONTRACT** | QC Spec Sheet | Every deliverable specified exactly. Nothing outside this list. |

### The Three-Word Workflow
Update  →  Copy  →  Paste
Update the yellow cells in SOURCES. Copy the INVOKE block. Paste into any AI tool. That is the entire user workflow — regardless of the complexity living inside the factory.

---

## What's in This Repository
workbooks/
Prompt_Factory_UniversalTemplate.xlsx         ← Blank template for any domain
Prompt_Factory_ProjectSpecific_Teradata.xlsx  ← Fully built example (Teradata + Tableau)
documentation/
Design_Once_Execute_Simpler_Framework.docx    ← The complete intellectual framework
What_Then_How_Philosophy.docx                 ← The philosophical foundation essay
Prompt_Factory_Documentation_Ed2.docx         ← Full design documentation (8 sections)
Prompt_Factory_Pitch_Guide.docx               ← 5–10 minute pitch and training guide
authorship/
AI_Prompt_Factory_Transcript_MingWei_Final.pdf  ← Full design session record
---

## Where to Start

**If you want to use an existing factory:**
1. Open \`Prompt_Factory_ProjectSpecific_Teradata.xlsx\`
2. Go to \`4_SOURCES\` — update the yellow cells with your table names and fields
3. Go to \`1_INVOKE\` — copy the dark code block
4. Paste into Claude, ChatGPT, Gemini, or any LLM
5. Done

**If you want to build a factory for your own domain:**
1. Open \`Prompt_Factory_UniversalTemplate.xlsx\`
2. Read \`Design_Once_Execute_Simpler_Framework.docx\` — particularly Section 6.1 (the 7-step build sequence)
3. Start with the MOLD tab — build your worked example manually for one representative unit first
4. Everything else follows from that

**If you want to understand the philosophy first:**
- Read \`What_Then_How_Philosophy.docx\` — short, standalone, under 1,500 words
- Then \`Design_Once_Execute_Simpler_Framework.docx\` for the full framework

---

## Demonstrated Domains

The 5-tab structure is invariant. Only the content inside changes.

| Domain | SOURCES Unit | What Changes |
|---|---|---|
| Data Engineering | Table name, field list, section label | SQL CTE architecture |
| Software Development | Module name, parameters, return type | Code structure |
| Technical Documentation | Endpoint name, method, parameters | Doc format |
| Business Reporting | Section name, data inputs, key metrics | Narrative framework |
| Legal Drafting | Clause type, party names, key terms | Clause structure |
| Marketing Copy | Asset type, channel, audience, CTA | Voice and format |
| Analytical Narrative | Metric name, current/prior value, target | Commentary framework |

---

## The Founding Use Case

The factory was originally built to solve a concrete data engineering problem: generating consistent Teradata SQL CTEs for a 9-table audit change-tracking system, feeding a Tableau dashboard with clickable drill-down detail.

The SQL architecture: \`LAG()\` window function + \`UNION ALL\` unpivot + \`POSITION()\` filter, all in CTEs (no database views). Unified terminal output: \`section | edit_seq | f1 | fields_with_change | field_name | old_value | new_value\`. Tableau: summary crosstab × section with Filter Action drill-down.

---

## Design Principles

| Principle | What It Means |
|---|---|
| Separation of Concerns | Fixed logic in SOP/MOLD/CONTRACT. Variable inputs in SOURCES only. |
| Pattern Over Description | MOLD is a physical example, not instructions. Replication, not interpretation. |
| Contract-Driven Output | Every deliverable enumerated with exact format. Nothing outside the contract. |
| Mandatory Quality Gates | AI self-audits before delivering. Quality is structural, not aspirational. |
| Explicit Deviation Policy | Hard stops for missing inputs. Warnings for abbreviated output. |
| Self-Describing | Every tab has a PURPOSE line. The workbook documents itself. |

---

## License

This work is released under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** license.

You are free to use, adapt, and share this methodology — in any domain, for any purpose, commercially or non-commercially — as long as you credit the original author.

**Attribution:** Ming Wei — *AI Prompt Factory* — https://github.com/MingWei-git/prompt-factory

---

## Author

**Ming Wei**
*Creator of the AI Prompt Factory and the What, Then How philosophy*

> *"Design once, execute simpler."*

Developed in collaboration with Claude (Claude Sonnet 4.6), created by Anthropic.

---

## Contributing

Found a new domain application? Built a factory for a use case not listed here? Discovered a pattern worth adding to the MOLD?

Open an issue or submit a pull request. Every domain application that proves the framework extends its reach for everyone.

---

*明 — Sun and Moon. Bright, illuminating, far-seeing.*

