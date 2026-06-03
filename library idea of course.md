# Library of Course Ideas — ECON1626 Economics of Artificial Intelligence

## The Big Intellectual Arc

The course builds one layered argument across 12 weeks:

> **AI is a general-purpose technology that creates an economic shock. The question is not whether it will change things, but who captures the gains, who bears the costs, and what institutions shape the outcome.**

---

## Week 1 — What Is AI and Why Economists Care

AI is a **general-purpose technology (GPT)** — like steam, electricity, and computing before it. GPTs have three properties: they are pervasive, they keep improving, and they spawn complementary innovations. Crucially, GPTs produce a **diffusion lag** — firms that just "bolt on" the technology without redesigning their processes see little gain. Full productivity benefits take decades and require institutional change.

**Key concepts:** General-purpose technology, diffusion lag, complementary innovation, competing narratives (doom / abundance / acceleration).

**Assignment relevance:** AI in legal services is a GPT shock hitting a specific sector. The question is how law firms, lawyers, clients, and regulators respond — not whether AI works technically.

---

## Week 2 — Origins of AI

LLMs are trained to predict the next token, and through scale they develop emergent capabilities nobody explicitly programmed. They are not programmed rules — they are pattern-matching systems that generalise. This explains why they can draft contracts and do legal research, but also why they hallucinate and fail on tasks requiring real-world judgment.

**Key concepts:** Tokens, transformers, pre-training, post-training, RLHF, scaling laws, emergent intelligence, ELIZA effect, symbolic AI vs connectionism.

**Assignment relevance:** One sentence of technical context is enough: "LLMs can now draft legal documents, conduct case research, and summarise briefs at low marginal cost." The rest is economics.

---

## Week 3 — Economic Growth and Innovation

Paul Romer's key insight: **ideas are non-rival goods** — one person using a legal precedent doesn't stop others. AI as an "ideas machine" could accelerate innovation itself, not just automate existing tasks. The debate is between the **modest view** (AI saves time on existing tasks, small TFP gains) and the **transformative view** (AI expands the combinatorial space of possible innovations entirely).

**Key concepts:** GDP per capita, productivity, TFP, Solow residual, endogenous growth theory (Romer), non-rival goods, knowledge spillovers, GPTs, complementary innovation, diffusion lag (20–30 years), AI as ideas machine.

**The debate:** Acemoglu estimates <1% TFP gains over the next decade (modest view). Transformative view says AI accelerates innovation itself.

**Assignment relevance:** Frame legal AI not just as efficiency but as potentially reshaping what legal work is possible. A junior associate with AI can do the research of a senior. What does that do to the economics of the law firm?

---

## Week 4 — AI and the Workforce *(Most important framework)*

### The Acemoglu–Restrepo Task Framework

Technology does not automate entire jobs — it automates specific **tasks** within jobs.

- **Displacement effect:** AI replaces labour in tasks it currently performs → labour share falls
- **Productivity effect:** total output rises because tasks are performed more efficiently
- **Reinstatement effect:** new tasks are created where labour has a comparative advantage → labour demand recovers
- **Net effect:** depends on which force is stronger

**So-so technologies:** high displacement, low productivity gain — worst outcome for workers (e.g. self-checkout kiosks).

### The Routine Task Hypothesis (Autor, Levy, Murnane 2003)

Tasks classified along two dimensions:

| | Routine | Non-routine |
|---|---|---|
| **Cognitive** | Record-keeping, calculation → automated | Diagnosis, legal writing → complemented |
| **Manual** | Assembly, picking → automated | Janitorial, caring → hard to automate |

### Job Polarisation

Middle-skill routine jobs are hollowed out. High-skill non-routine cognitive jobs grow (complemented by AI). Low-skill non-routine manual jobs grow (hard to automate). Wage inequality widens.

### The Jagged Frontier (Dell'Acqua et al. 2023)

AI exceeds human performance inside certain task boundaries but is actively harmful outside them. Workers need to know when to trust AI and when not to.

- Inside the frontier: consultants using AI completed 12% more tasks, 25% faster, 40% higher quality
- Outside the frontier: consultants using AI were 19% less likely to produce correct solutions

### AI as Capital That Behaves Like Labour

AI is institutionally capital (purchased, owned, depreciates) but functionally supplies labour-like cognitive services. Returns that used to flow as wages now flow as profit to the firm and to the AI vendor.

**Key insight:** Before AI, law firm pays associate wages → value split between associate and firm. After AI, law firm pays API fees → value flows entirely to the firm (and Anthropic/OpenAI).

**Assignment relevance:** This is the core analytical framework. Which tasks does AI displace (document review, legal research, first-draft contracts)? Which tasks does AI complement (client judgment, court advocacy, ethical reasoning)? Who captures the productivity gain?

---

## Week 5 — Institutions and Market Structure

Covers data economics, firm concentration, and market power. Relevant to whether AI advantages large law firms over small ones, and whether AI creates or entrenches market concentration.

---

## Week 6 — AI Alignment as an Economics Problem

Alignment is fundamentally a **principal–agent problem**: AI optimises for specified goals, not intended goals.

### Three Alignment Frameworks

1. **Value alignment** — embed shared values into the model (EU approach; contested; fairness definitions are mathematically incompatible)
2. **Intent alignment** — do what the user is actually trying to do (practical but limited; jailbreaking is a revealed preference against over-restriction)
3. **Institutional alignment** — constrain AI through property rights, contracts, and accountability rules (most scalable for agentic AI)

### The Coase Theorem Applied to AI

Clear assignment of liability creates incentives for safety without specifying how. The initial assignment of rights (deployers liable vs not liable) dramatically changes incentives.

### Governance Options

- Liability rules — make developers/deployers liable for harms
- Mandatory disclosure — reduce information asymmetry
- Pre-market safety testing — catch failures before deployment at scale
- Market competition — reputation and rivalry discipline providers

**Assignment relevance:** Who bears liability when an AI-drafted contract is wrong — the law firm, the AI vendor, or the client? Australia's Law Societies and ASIC have not resolved this. That is a concrete policy gap.

---

## Week 7 — Public Policy and Regulation

### The Market Failure Toolkit for AI Regulation

- **Externalities** — AI harms fall on third parties (bias, displacement, errors)
- **Information asymmetry** — users cannot verify AI quality
- **Market concentration** — a few labs supply most capable models
- **Knowledge problem** (Hayek) — regulators cannot know in advance what will be harmful; prefer principles over prescriptions; prefer ex-post liability over ex-ante licensing where harms are reversible

### The EU AI Act (2024)

Risk-based, ex-ante regulation. Four tiers: unacceptable (banned), high-risk (conformity assessment), limited (transparency), minimal (no new obligations).

Legal AI in hiring/evaluation is classified **high risk**. Providers must implement risk management, data governance, human oversight, and conformity assessment before market entry.

**Brussels Effect:** global firms often apply EU standards everywhere — cheaper than running two versions.

### The US Approach

Sectoral, ex-post, enforcement-led. No horizontal AI statute. Sharp swings between administrations (Biden EO 14110 revoked by Trump EO 14179). States are filling the gap (Colorado AI Act, NYC Local Law 144).

### Australian Regulatory Position

No horizontal AI statute. Key recent developments:
- **NSW Digital Work Systems Act (Feb 2026):** first concrete Australian AI statute, framed as workplace health and safety; covers algorithms used to direct, manage, monitor, or evaluate work
- **Productivity Commission (Aug 2025):** floated a text-and-data mining exception; rejected by Albanese government (Oct 2025)
- **Copyright and AI Reference Group (CAIRG):** established to design licensing pathways for AI training data

**Assignment relevance:** Australia's regulatory gap is a policy opportunity. What should ASIC and the Law Societies do about AI in legal advice? The EU model and the NSW workplace model give concrete comparison points.

---

## Week 8 — AI as Infrastructure

AI capability is highly **concentrated** — a few frontier labs supply the models that all firms use downstream. This creates dependency, pricing power, and concentration risks. Small law firms face the same tool costs as large ones but have less capacity to integrate and adapt.

**Key question:** Who adopts first — large commercial firms or small regional firms? What does differential adoption do to market concentration in legal services?

---

## Week 9 — Open vs Closed AI

The open/closed debate affects how quickly legal AI diffuses. Open-source models lower cost but may lack reliability for legal work. Closed frontier models are more capable but create vendor dependency.

---

## Week 10 — AI Agents

### Agents vs Chatbots

An AI agent perceives its environment, decides, acts, and persists across multiple steps without continuous human direction. This is the shift from AI that responds to prompts to AI that pursues goals — substituting for workflows, not just individual tasks.

### The Institutional Reclassification

**Before AI agents:**
- Firm hires a junior associate
- Associate writes documents; firm pays wages
- Value accrues partly to the associate (wages) and partly to the firm (profit)
- Associate can bargain over wages and conditions

**After AI agents:**
- Firm subscribes to an AI drafting tool
- Agent writes documents; firm pays API fees
- Value accrues entirely to the firm (and to the AI vendor as capital owner)
- Agent cannot bargain; has no interests to protect

### Economic Implications

- Labour markets: AI agents substitute for cognitive tasks; distributional implications depend on who owns the capital
- Firm boundaries: agents lower the cost of complex coordination but may raise the cost of accountability
- Distribution: returns to AI-as-capital accrue to capital owners; could increase inequality unless institutions redistribute gains

**Assignment relevance:** Junior lawyers are most exposed — document review, legal research, first drafts. Their wage premium disappears if AI does those tasks. Senior partners with client relationships and courtroom judgment are complemented, not displaced.

---

## Week 11 — Combinatorial Innovation

Innovation is **multiplicative, not additive**: Technology × Technology × Technology.

Digital technologies accelerate recombination because they share a common digital form (a lingua franca of APIs, protocols, and data).

### Technologies as Economic Products

| Technology | Economic Product |
|---|---|
| Artificial intelligence | Prediction, intelligence, reasoning |
| Blockchains | Trust, verification, deterministic execution |
| Quantum computing | New forms of compute and search |
| Advanced cryptography | Privacy and proof |
| Low Earth orbit satellites / IoT | Connectivity and visibility |

### AI + Other Technologies

- AI + blockchain = autonomous economic agents that can decide and execute
- AI + data markets = new ways to access private training data
- AI + IoT + satellites = environmental and agricultural monitoring
- AI + e-discovery platforms + document management = full legal workflow automation

**Assignment relevance:** Legal AI becomes more powerful when combined with document management systems, e-discovery platforms, case databases (LexisNexis), and contract lifecycle management tools. The full productivity gain requires organisational redesign — not just plugging in a chatbot.

---

## Week 12 — Assignment Workflow

Chris's core message: **concrete beats generic**. Use AI to accelerate research and iteration, but reinvest the saved time into better evidence, sharper reasoning, and more distinctive choices.

A one-prompt assignment will be weak. A two-hour AI-assisted assignment can be much stronger.

---

## The Master Causal Chain (Use in Every Paragraph)

```
AI capability (LLMs can draft, research, summarise at low cost)
  → Task displacement (document review, legal research, first drafts)
  → Who changes behaviour (law firms adopt to cut associate headcount or raise output)
  → Who captures gains (partners and firms, not junior associates; and AI vendors)
  → Economic outcome (productivity rises, wage premium for junior lawyers falls,
     market concentration increases as large firms adopt faster)
  → Policy response (who is liable for AI legal errors? How does ASIC regulate
     AI legal advice? Should Australia adopt EU-style high-risk classification?)
```

---

## Key Theorists and Papers to Cite

| Source | Key Argument |
|---|---|
| Acemoglu & Restrepo (2019) | Task framework: displacement vs reinstatement effect |
| Autor, Levy & Murnane (2003) | Routine task hypothesis; job polarisation |
| Dell'Acqua et al. (2023) | Jagged frontier — AI boosts some tasks, harms others |
| Romer (1990) | Endogenous growth; ideas as non-rival goods |
| Brynjolfsson, Li & Raymond (2025) | LLMs raised customer support productivity ~15% |
| Acemoglu (2024) | Sceptical case: <1% TFP gains from AI over next decade |
| Berg (2026) | Course textbook — alignment as economics; institutional alignment |
| Coase (1960) | Property rights and liability as governance tools |
| EU AI Act (2024) | Risk-based regulation; legal AI as high-risk |
| Hayek (1945) | Knowledge problem; prefer principles to prescriptions |
